# fondo-pensione

Tool single-page per calcolare quanto versare sul fondo pensione restando entro il massimo deducibile (default 5300 €).

- File unico `index.html` (HTML + CSS + JS, zero dipendenze).
- Persistenza locale via `localStorage` + Export/Import JSON.
- Italiano, responsive, tema chiaro/scuro automatico.

## Uso in locale

Apri `index.html` nel browser.

## Pubblicazione

Il workflow `.github/workflows/pages.yml` pubblica automaticamente su GitHub Pages a ogni push su `main`. Per attivarlo la prima volta: Settings → Pages → Source = "GitHub Actions".
