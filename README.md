
# Tungen Invest AS – Lagerseksjon landing

Enkel statisk side (HTML/CSS/JS) uten byggsteg. Klar for GitHub Pages.

## Deploy (GitHub Pages)

1. Opprett et nytt repo, f.eks. `tungen-lager`.
2. Last opp alle filer i denne mappen til repoet.
3. I repoet: **Settings → Pages**.
   - Source: **Deploy from a branch**
   - Branch: **main** / `/(root)`
4. Legg til CNAME under **Custom domain**: `www.tungen.net`. (Filen `CNAME` ligger allerede i repoet.)
5. I DNS: pek `www` (CNAME) til `your-username.github.io`.
6. Vent på at GitHub Pages aktiveres. Test på `https://www.tungen.net`.

## Struktur
- `index.html` – landingsside
- `styles.css` – enkel styling
- `script.js` – lazy-load av kart (ingen cookies før bruker klikker)
- `assets/` – bilder, logo og plantegning
- `CNAME` – custom domain

Ingen analytics, ingen kontaktskjema – kun e‑post og telefon.
