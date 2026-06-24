# Rebellsystem Leads — Verkaufs-Website

Statische, eigenständige Landingpage für das Produkt **„B2B-Leads mit echtem Kaufsignal + Kaufbereitschafts-Analyse"** (ab 500 €). GitHub-Pages-ready, keine externen Tracker, keine externen Fonts (DSGVO-schonend).

## Dateien
- `index.html` — Hauptseite (Hero, Kaufsignale, Was-du-bekommst, Ablauf, Premium-Gate, Preise, FAQ, CTA).
- `impressum.html` / `datenschutz.html` — Rechtstexte.
- `.nojekyll` — verhindert Jekyll-Verarbeitung bei GitHub Pages.

## Vor dem Livegang — eine Zeile anpassen
In `index.html` ganz unten im `<script>`:

```js
const CALENDLY = ""; // -> hier deinen echten Calendly-Link eintragen
```

Solange leer, fallen alle „Termin buchen"-Buttons sauber auf `mailto:emilio@rebellsystem.com` zurück.

## GitHub Pages aktivieren
1. Repo `rebellmitherz/leads` pushen (siehe unten).
2. GitHub → Settings → Pages → Source: `Deploy from a branch` → Branch `main` / `/ (root)`.
3. Optional: eigene Domain (z. B. `leads.rebellsystem.com`) eintragen + DNS-CNAME setzen + „Enforce HTTPS".

## Lokal ansehen
`index.html` einfach im Browser öffnen.
