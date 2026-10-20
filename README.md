# Ekolod Studio – Öjen (GitHub Pages)

Statisk kartvisare för Öjen, Njurunda. **Inga verifierade djupdata ingår.** Kartbakgrund från OpenStreetMap; kartbibliotek Leaflet via CDN. Internet behövs för bakgrundskartan.

## Publicera på GitHub Pages

1. Logga in på https://github.com och skapa ett **Public** repository, till exempel `ekolod-studio`.
2. Välj **Add file → Upload files**, ladda upp `index.html` från detta paket i repositoryts rot och klicka **Commit changes**.
3. Öppna repositoryts **Settings → Pages**.
4. Under **Build and deployment**: välj **Deploy from a branch**, `main` och `/ (root)` och spara.
5. När GitHub visar webbplatsens adress, öppna den i Safari. Normalt ser den ut som `https://DITT-ANVANDARNAMN.github.io/ekolod-studio/`.

Du behöver inte lägga upp README-filen, men den är praktisk att behålla. Publiceringen kan ta några minuter. Kontrollera Pages-sidan för faktisk adress och publiceringsstatus.

## Funktioner

- OpenStreetMap-bakgrund, ungefärligt centrerad på Öjen.
- Import av CSV med `lat,lon,depth` i WGS84 decimalgrader och meter.
- Visa importerade mätpunkter, rensa och exportera GeoJSON.
- En tydligt markerad **simulerad** exempelpunkt.
- GPS-knapp som ber om tillåtelse i Safari (HTTPS krävs).

## Begränsningar

Detta är en offentlig prototyp, inte en privat kartdelningstjänst. Filer som publiceras i ett publikt GitHub-repository kan läsas av andra. Importerade CSV-filer behandlas i webbläsaren och laddas inte upp av denna prototyp. Ingen serverlagring, djupinterpolering, ACU-import eller offlinefunktion ingår. Använd inte för navigation.
