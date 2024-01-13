git clone https://github.com/szabopeter92/git-vizsga.git - klónozom a repositoryból a projectet

git init - létrehozom a "mappát" - minden ebben lesz rögzítve

git status - elenőrzöm a fájlok státuszát, milyen változások jöttek létre

git add . - hozzáadom a fájlokat a (gitignore fájlban leírtakon kívül) staging areahoz

clear - törlöm a git bashből az eddigi parancsokat, jobban átlátható lesz a továbbiakban

git remote add origin https://github.com/zsocesz/GIT-vizsga.git - megadni a repository elérési útját

git pull --rebase origin main - Frissítem a könyvtárat a repositoryból

git push -u origin main - Feltültöm a frissített, változtatott adatokat

git branch console - létrehozom a console mellékágat 

git checkout console - átlépek a console mellékágba, ezentúl itt mentem el a változtatásokat, nem a 'main' főágon

git commit -m - egy megjegyzést adok hozzá, hogy milyen módosítást hajtottam végre

