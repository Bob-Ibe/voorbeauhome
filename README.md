# Content Engine, voorstel voor Beau Home Inspiration

Teaser-pagina van IBE MOTION voor Beau Home Inspiration in Weert:
elke maand nieuwe reels van hun eigen collectie, zonder draaidagen.

Statische site, geen build-stap. Vanilla HTML en CSS.
Vormgeving afgeleid van beauhome.nl: crème, espressobruin en champagne,
met Playfair Display, Montserrat en Raleway.

## Opbouw

| Bestand | Wat het is |
|---|---|
| `index.html` | De teaser |
| `style.css` | Alle vormgeving |
| `assets/reels/` | Twee demoreels, 15 seconden, 720x1280 |
| `assets/beau-embleem.webp` | Embleem van Beau Home, in de kop |

## Let op

Dit is een teaser: de pakketten staan erin zonder bedragen.
De tarieven komen pas in het gesprek aan bod.

De pagina staat op `noindex` en er ligt een `robots.txt`, dus hij is
alleen te vinden via de link die je zelf deelt.

## Lokaal bekijken

```bash
python3 -m http.server 8160
```
