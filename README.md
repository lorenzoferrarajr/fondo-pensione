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

Il workflow `.github/workflows/pages.yml` pubblica solo `index.html` su GitHub Pages a ogni push su `main`. Dopo aver unito la pull request su `main`, attiva Pages in Settings → Pages → Source = "GitHub Actions" e controlla il risultato in Actions. L'indirizzo previsto è `https://lorenzoferrarajr.github.io/fondo-pensione/`.

I dati salvati aprendo il file locale non passano automaticamente al sito pubblicato: esporta il JSON dal file locale e importalo sul sito per trasferirli.
