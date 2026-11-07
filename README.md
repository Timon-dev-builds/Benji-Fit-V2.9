# Benji-Fit

Een fitness-app met Benji. Geen server nodig.

## Zetten op GitHub Pages
1. Maak op github.com een nieuwe **publieke** repository, bijvoorbeeld `benji-fit`.
2. Kies **Add file > Upload files** en sleep ALLE bestanden en mappen uit deze map erin (index.html, app.js, style.css, sw.js, manifest.webmanifest, de icon-bestanden en de mappen `img` en `lang`). Klik op **Commit changes**.
3. Ga naar **Settings > Pages**. Kies *Deploy from a branch*, branch `main`, map `/ (root)`. Opslaan.
4. Na een minuut staat de app op `https://JOUWNAAM.github.io/benji-fit/`.

## Op je telefoon
- iPhone: open de link in **Safari**, tik op Delen en kies **Zet op beginscherm**.
- Android: open de link in **Chrome**, tik op het menu en kies **App installeren**.

## Goed om te weten
- Je gegevens blijven in de browser van je telefoon.
- De taalpakketten staan in `lang/` en worden pas geladen als je een andere taal kiest.
- Het vriendenbord werkt alleen in de versie binnen Claude.
- Nieuwe versie? Vervang de bestanden in de repository en verhoog in `sw.js` het nummer bij `V` (bijvoorbeeld `benji-fit-v8`), anders blijft je telefoon de oude versie tonen.
