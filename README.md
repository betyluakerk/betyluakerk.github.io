# Betyluakerk website

## Publiceren op GitHub Pages
1. Zet alle bestanden uit deze map in de root van je GitHub-repository (of in een `/docs`-map).
2. Ga naar **Settings → Pages** in je repo en kies de branch/map waar deze bestanden staan.
3. Je site is dan bereikbaar op `https://<gebruikersnaam>.github.io/<repo-naam>/`.

## PDF's toevoegen
Plaats je drie PDF-bestanden in `assets/pdfs/`, met precies deze bestandsnamen (spaties gewoon toegestaan):

- `Septuagint bijbel met psalmen.pdf`
- `Savoy declaratie.pdf`
- `Bijvoegsel Savoy.pdf`

De downloadknoppen in de Bronnen-sectie verwijzen al naar deze paden — zodra de bestanden er staan, werken de links direct.

## Zelf tekst aanpassen
- **Introductie** en **Over Ons**: de lorem-ipsum-alinea's in `index.html` (secties `#intro` en `#over-ons`) kun je vervangen door je eigen tekst.
- **Bezoekers Informatie**: vervang de placeholders tussen `[blokhaken]` in de sectie `#bezoekers` door je echte adres, diensttijden en contactgegevens.

## Lettertypes en kleuren
De site gebruikt Cormorant Garamond (koppen) en Source Serif 4 (lopende tekst) via Google Fonts, en een perkamentbeige kleurpalet gedefinieerd bovenaan `style.css` onder `:root`. Pas de hex-waarden daar aan om de sfeer te verfijnen.
