# Kamphuis.co

Statische, dependency-vrije site (HTML/CSS, geen build-stap): één pagina met
een illustratie, zelfde opzet als tomkamphuis.nl.

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
- `assets/family-farm.svg` — illustratie (eigen ontwerp, geïnspireerd op een boerderij-/gezinsthema)
- `assets/favicon.svg` — favicon

## Afbeelding vervangen

`assets/family-farm.svg` is een eigen illustratie — geen stockfoto. Wil je de
Vecteezy-afbeelding (of een andere) gebruiken, koop dan de licentie en
vervang het bestand (pas evt. `index.html` aan als je een `.jpg`/`.png` gebruikt
in plaats van `.svg`).
