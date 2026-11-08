# BGE Learning Lab – feltöltési útmutató

## Feltöltés a BGE repositoryba

1. Csomagold ki a ZIP-et a gépeden.
2. A BGE repository gyökerébe töltsd fel a kicsomagolt fájlokat ÉS mappákat. Ne magát a ZIP-et töltsd fel, és ne tedd őket még egy külső mappába.
3. A GitHubon a feltöltéskor a mappákat is húzd be, hogy a belső szerkezetük megmaradjon.
4. Settings → Pages → Deploy from a branch → main → / (root) → Save.
5. A GitHub által megadott Pages-cím a főoldalt nyitja meg. A Forward Lab az alatta található forward-lab/ útvonalon érhető el.

## Fájlok

- index.html: angol hallgatói főoldal
- hub.css és hub.js: a főoldal stílusa és rövid bemelegítő kérdése
- forward-lab/: a teljes játék, ±2%-os válaszelfogadással
- materials/: a 8 feladatos PowerPoint gyakorló
- .nojekyll: közvetlen statikus kiszolgálás GitHub Pages alatt

A főoldalról megnyílik a játék, a játék fejlécéből vagy az „All activities” linkkel vissza lehet térni a főoldalra. Minden belső link relatív, ezért a /BGE/ alatti Pages-oldalon is működik.

## További játékok

Minden új játék kerüljön külön mappába, a saját index.html fájljával. Például normal-distribution/index.html vagy bond-pricing/index.html.
Az új játékhoz az index.html Games & simulations szakaszába vehető fel új hivatkozás az adott mappa relatív útvonalával. Csak a ténylegesen feltöltött játékokat jelenítsd meg.

## Használat

A főoldal és a játék angol nyelvű. A játék szimulált árakkal dolgozik, nem tölt le élő tőzsdei adatokat. A hallgatók eredményei a saját böngészőjükben tárolódnak, és CSV-be letölthetők. A tanári beállítások demonstrációt szolgálnak, nem védett vizsgakörnyezetet.

A főoldal egyszerű BGE szöveges megjelölést használ, nem hivatalos egyetemi logót. A repositoryban már kiválasztott licencet ez a csomag nem cseréli le.
