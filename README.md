# Purreløken

Intern lunsjønskeliste for Kravia AS. Ansatte foreslår matvarer og stemmer på hverandres forslag. Topp 3 vises alltid øverst for innkjøpsansvarlig.

## Bruk

Åpne [purreløken](https://eirlindhovd-oss.github.io/kravings/) og foreslå hva du vil ha til lunsj.

## Teknologi

- Frontend: én HTML-fil med embedded CSS og JavaScript
- Database: Supabase (PostgreSQL) — tabell `wishes`, kolonner `id`, `product_name`, `votes`, `created_at`
- Hosting: GitHub Pages
- Anti-dobbeltstemming: localStorage per bruker

## Deploy

Push til `main` deployer automatisk via GitHub Actions.

Første gang: gå til **Settings → Pages → Source** og velg **GitHub Actions**.
