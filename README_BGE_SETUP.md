# BGE Tanulólabor – magyar és angol változat

## Feltöltés a meglévő BGE repositoryba

1. Csomagold ki a ZIP-et.
2. A tartalmát, a mappákkal együtt töltsd fel a BGE repository gyökerébe. A meglévő azonos nevű fájlokat cseréld az új változatra.
3. A külső ZIP-mappa és a ZIP-fájl nem kerül a repositoryba.
4. A már beállított GitHub Pages maradjon main / (root). A feltöltés után a webcím nem változik.
5. Frissítsd a weboldalt Ctrl+F5-tel, ha még a régi változat jelenik meg.

## Szerkezet

- index.html, hub.css: egyszerű főoldal a három gyakorló linkjével, tantárgynév és kiegészítő blokkok nélkül.
- language.js, language.css: közös magyar–angol nyelvválasztó zászlókkal.
- forward-lab/: határidős gyakorló, ±2%-os válaszelfogadással.
- options-lab/: böngészőben futó opciós gyakorló. A korábbi Python-változat interaktív grafikonját, háromrészes feladatát és összefoglalóját tartalmazza.
- normal-distribution/: az eredeti v7 angol és magyar gyakorló, nyelvválasztóval és főoldali visszalinkkel. A 4 tizedesjegyes válasz és a Casio fx-991CW útmutató megmaradt.
- .nojekyll: közvetlen statikus kiszolgálás.

## Nyelvváltás

A HU és EN zászlós gombok jobb felül láthatók. A választás a böngészőben megmarad, és a főoldalról a játékba is átkerül. A határidős és opciós játék nyelvváltása nem törli az aktuális feladatot. A normális eloszlásos gyakorló nyelvváltása a megfelelő korábbi nyelvi változatot tölti be, ezért új feladatot generálhat.

Az opciós és határidős eredményeknél a ±2%-os tolerancia a helyes válasz abszolút értékére vonatkozik, legalább 0,01 eltérést elfogadva. Az opciós gyakorló minden új feladatra egyszer ad pontot. A számítások nem tartalmazzák a pénz időértékét, költséget vagy adót.

A ZIP nem írja felül a repository meglévő licencét. A tanári beállítások nem vizsgabiztonsági védelem. Nincs élő árfolyam-adatkapcsolat vagy valódi kereskedés.
