# Renovaut · Domeinstrategie

Strategische analyse en consolidatievoorstel voor het samenbrengen van renovaut.be en slotenmaker-evergem.be.

**Voorbereid door** Conversal · Digital Intelligence Agency
**Voor** Renovaut
**Datum** mei 2026

## Live versie

Zie GitHub Pages instellen hieronder.

## Lokaal bekijken

Open `index.html` rechtstreeks in een browser. Geen build-stap nodig.

## GitHub Pages activeren

1. Push deze repo naar GitHub (Public of Private + Pro-account voor Pages).
2. Repo settings → Pages → Source: `Deploy from a branch` → Branch: `main` → Folder: `/ (root)`.
3. Save. Na 1-2 minuten staat de site live op `https://[username].github.io/[repo-naam]/`.

## Custom domein (optioneel)

Voor een nettere URL zoals `renovaut.steven.conversal.be`:

1. DNS: voeg een CNAME-record toe die naar `[username].github.io` wijst.
2. Repo settings → Pages → Custom domain → vul het subdomein in.
3. Vink `Enforce HTTPS` aan zodra het certificaat is uitgereikt.

## Structuur

```
.
├── index.html      Volledige pitch in één bestand
└── README.md       Dit bestand
```

Alle CSS en JS zit inline in `index.html`. Chart.js wordt geladen via CDN.
