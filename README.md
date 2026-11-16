# Mantelmap

Gratis app voor wie de papieren van een ouder regelt. Mantelmap toont welke steun er mogelijk blijft liggen, zet deadlines in je agenda, geeft kant-en-klare brieven (ook een volmacht) en heeft een luik met rechten voor de mantelzorger zelf.
Geen server, geen account: alles blijft op het toestel van de gebruiker.

## Bestanden
- `index.html`: de app zelf
- `manifest.webmanifest`, `sw.js`: maken de app installeerbaar en offline bruikbaar
- `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`: de iconen

## Bijwerken op GitHub
1. Ga naar je repository op github.com.
2. Klik op **Add file**, dan **Upload files**.
3. Sleep alle bestanden hierboven erin. Bestanden met dezelfde naam worden vervangen.
4. Klik op **Commit changes**. Na een minuut of twee staat de nieuwe versie online.

## Regels onderhouden
Alle bedragen staan bovenaan het script, in het object `R`. Kijk ze na:
- op 1 januari (indexering),
- op 1 maart (IGO),
- op 1 september (verhoogde tegemoetkoming),
- bij elke indexering van de zorgbudgetten,
- bij elke nieuwe BIPT-prijsstudie.

Na elke aanpassing:
1. Zet `NAGEKEKEN` op de juiste maand.
2. Voeg bovenaan `NIEUWS` een bericht toe (datum, titel en tekst). Gebruikers die de app al gebruikten, zien dat bericht bij de volgende opening.
3. Verhoog `VERSION` in `sw.js`.
