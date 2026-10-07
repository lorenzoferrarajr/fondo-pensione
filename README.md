# fondo-pensione

Tool single-page per calcolare quanto versare sul fondo pensione restando entro il massimo deducibile (default 5300 €).

- File unico `index.html` (HTML + CSS + JS, zero dipendenze).
- Persistenza locale separata per anno via `localStorage` + Export/Import JSON.
- L'anno corrente cambia automaticamente; il selettore compare solo quando esistono archivi di più anni. I dati salvati dalla versione senza anno restano disponibili per il download o per l'associazione esplicita a un anno.
- Ogni versamento ricorrente può essere applicato a mesi scelti singolarmente; i vecchi intervalli da mese iniziale a mese finale vengono convertiti automaticamente.
- Italiano, responsive, temi Chiaro (predefinito), Scuro e Automatico selezionabili dalla pagina.

## Uso in locale

Apri `index.html` nel browser.

## Pubblicazione

Il workflow `.github/workflows/pages.yml` pubblica automaticamente su GitHub Pages a ogni push su `main`. Per attivarlo la prima volta: Settings → Pages → Source = "GitHub Actions".
