git init -> git inicializálása a git-vizsga könyvtárban
git clone https://github.com/szabopeter92/git-vizsga.git   -> a projekt klónozása a saját gépre
git status -> gyűjtemény státuszának ellenőrzése (legutóbb létrehozott fájlok: readme.md, .gitignore)
git branch console -> egy új, console nevű ág létrehozása
git add . -> a main ágon lévő módosítások (2 új fájl) hozzáadása a staging area-hoz
git commit -m ".gitignore és readme.md fájlok létrehozva" -> eddigi változtatások rögzítése
git checkout console -> váltás a console ágra, hogy itt tudjuk végrehajtani a módosítást az app.js fájlban
git add app.js -> a console ágon az app.js-ben történő váltatás hozzáadása a staging area-hoz
git commit -m "app.js: console-ba kiírás kész van." -> a változtatások rögzítése a console ágon
git add . -> readme és a style.css fájlokban történő változatások hozzáadása a staging area-hoz
got commit -m "style.css: háttérkép megváltozatva." -> a változtatások rögzítése a console ágon