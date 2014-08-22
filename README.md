#Web volebního sdružení Otevřeme Radotín

##Správa webu

1. Pro web je třeba mít nainstalovaný ``jekyll``. 
```
sudo apt-get install jekyll
```
2. Web stáhnete příkazem 
```bash
git clone https://github.com/jmichalek/otevremeradotin.git
```

3. Základní konfigurace webu se dělá v souboru ``_config``

4. Profily kandidátů se vkládají do složky ``_post``. V profilech je třeba nastavit správně číslo na kandidátce, citát a relativní cestu k obrázku. V postech můžete používat i tučné písmo nebo jiné formátování v [syntaxi markdown](http://www.edgering.org/markdown/).


5. Fotografie kandidátů se vkládají do složky ``media/candidates/``. Doporučený tvar fotografie je A4 naležato s šířkou aspoň 1000 px (poměr výšky a šířky je přibližně 0.71). 

6. Miniatury fotografií zobrazované na kandidátní listině se skladují v adresáři ``media/candidates/thumbnails``, kam je vytvoří příkaz ``media/candidates/generate_thumbnails.sh``, který je třeba spustit. Komprimaci souborů v tomto příkazu zajišťuje program ``imagemagick``, který lze nainstalovat následovně: 
```bash
sudo apt-get install imagemagick
```

7. Pro přípravu webu jako celku na vlastním počítači použijte příkaz ``jekyll serve --watch``. Ten vytvoří instanci pro testování na adrese v prohlížeči ``localhost:4000``. Uložené změny v souborech se projeví po obnovení stránky i v prohlížeči. Stránku můžete obnovit klávesou ``F5``.

8. Výsledky uložte v gitu (``git add filename.md``, ``git commit``) a nahraj na server (``git push``). Pokud nemáš oprávnění nahrávat na server, připravte [pull request](https://help.github.com/articles/creating-a-pull-request) do [mého repozitáře](https://github.com/jmichalek/otevremeradotin).
