# lp-recruiting-report-2026

Landingpage für den GreenCareers Recruiting-Report 2026.

**Live:** https://frdlnk-gc.github.io/lp-recruiting-report-2026/
(nach Deploy via GitHub Pages)

## Inhalt

- `index.html` – Komplette Landingpage (self-contained)
- `logo-white-sm.png` – GreenCareers Logo weiß (Nav, Footer, Buch)
- `favicon-32.png`, `favicon-64.png`, `apple-touch-icon.png` – Favicons
- `hero-images/hero-2-web.jpg` – Hero-Hintergrundfoto
- `cust-logos/` – 16 Kundenlogos für die scrollende Bar

## Make-Webhook Setup

In `index.html`, suche nach:
```js
const MAKE_WEBHOOK_URL = 'HIER_MAKE_WEBHOOK_URL_EINTRAGEN';
```

Und ersetze mit der Webhook-URL aus deinem Make-Szenario.
