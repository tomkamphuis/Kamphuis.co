# Kamphuis.co

Statische, dependency-vrije site (HTML/CSS, geen build-stap): één pagina met
een schermvullende afbeelding, zelfde opzet als tomkamphuis.nl.

## Lokaal bekijken

```
python -m http.server 8792
```

Open daarna `http://localhost:8792`.

## Hosten

Werkt direct op elke statische host, zonder build-stap:

- **GitHub Pages**: repo aanmaken, deze bestanden pushen, Pages aanzetten op de `main`-branch. `CNAME` bevat al `kamphuis.co`.
- **Netlify / Vercel**: map slepen naar hun dashboard, of repo koppelen.

## Bestanden

- `index.html` — de pagina
- `css/styles.css` — styling (afbeelding vult het scherm)
- `assets/KamphuisCo.png` — de foto/illustratie
- `assets/favicon.svg` — favicon

## Afbeelding vervangen

Zet een nieuw bestand in `assets/` en pas het `src`-attribuut van de
`<img class="hero-image">` in `index.html` aan.
