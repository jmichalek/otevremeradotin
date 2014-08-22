#Web volebního sdružení Otevřeme Radotín

*Jednoduchý a volně šiřitelný web pro kandidátní listinu do voleb v České republice a volební program.*

1. Pro správu webu a zobrazování na vlastním počítači je třeba mít nainstalovaný ``jekyll``. To uděláte v Ubuntu příkazem ``sudo apt-get install jekyll``.

2. Web stáhnete příkazem ``git clone https://github.com/jmichalek/otevremeradotin.git``.

3. Základní vlastnosti můžete nastavit v konfiguraci webu v souboru ``_config``

4. Profily kandidátů se vkládají do složky ``_post``. V profilech je třeba nastavit správně číslo na kandidátce, citát a relativní cestu k obrázku. V postech můžete používat i tučné písmo nebo jiné formátování v [syntaxi markdown](http://www.edgering.org/markdown/).


5. Fotografie kandidátů se vkládají do složky ``media/candidates/``. Doporučený tvar fotografie je A4 naležato s šířkou aspoň 1000 px (poměr výšky a šířky je přibližně 0.71). 

6. Miniatury fotografií zobrazované na kandidátní listině se skladují v adresáři ``media/candidates/thumbnails``, kam je vytvoří příkaz ``media/candidates/generate_thumbnails.sh``, který je třeba spustit. Komprimaci souborů v tomto příkazu zajišťuje program ``imagemagick``, který lze nainstalovat příkazem ``sudo apt-get install imagemagick``.

7. Pro přípravu webu jako celku na vlastním počítači použijte příkaz ``jekyll serve --watch``. Ten vytvoří instanci pro testování v prohlížeči (Firefox, Chromium apod.) na adrese ``localhost:4000``. Uložené změny v souborech se projeví po obnovení stránky i v prohlížeči. Stránku můžete v prohlížeči obnovit klávesou ``F5``.

8. Výsledky uložte v gitu (``git add _/posts/jmeno-kandidata.md``, ``git commit -m "Přidání kandidáta"``) a nahrajte do repozitáře (``git push``). Pokud nemáte oprávnění nahrávat na repozitář, připravte [pull request](https://help.github.com/articles/creating-a-pull-request) do [mého repozitáře](https://github.com/jmichalek/otevremeradotin).

9. Na Internetu se díky funkci [github pages](https://pages.github.com/) zobrazuje web, jak je vytvořený ve větvi ``gh-pages``. 

Použité materiály s jejich licencemi můžete zobrazit v [přehledu použitých materiálů](_posts|2014-08-20-cited.md). Tento web je svobodný software za podmínek [licence GNU AGPL v3](LICENSE), není-li na něm uvedeno jinak.
