#Web volebního sdružení Otevřeme Radotín

##Správa webu

Pro web je třeba mít nainstalovaný ``jekyll``. 

    sudo apt-get install jekyll

* Web stáhnete příkazem 

    git clone https://github.com/jmichalek/otevremeradotin.git

* Profily kandidátů se vkládají do složky ``_post``.
* Fotografie kandidátů se vkládají do složky ``media/candidates/``.
* Miniatury fotografií se skladují v adresáři ``media/candidates/thumbnails``, kam je vytvoří skript ``media/candidates/generate_thumbnails.sh``, který je třeba spustit.
* Pro přípravu použij příkaz ``jekyll serve``. Ten vytvoří instanci pro testování na adrese v prohlížeči ``localhost:4000``.
* Výsledky ulož v gitu (``git add filename.md``, ``git commit``) a nahraj na server (``git push``). Pokud nemáš oprávnění nahrávat na server, připrav pull request.
