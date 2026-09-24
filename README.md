# Karo – Mathe-Nachhilfe Website

Statische Website, kein Build-Schritt nötig.

## Struktur
- `index.html` – die Seite
- `impressum.html`, `datenschutz.html` – Rechtliches (gelb markierte Stellen vor Livegang ergänzen)
- `assets/timon.jpg` – Porträt
- `fonts/` – lokal eingebundene Schriften (Newsreader, Instrument Sans, Caveat; SIL Open Font License, siehe OFL-*.txt)
- `favicon.svg`

## Häufige Anpassungen (ganz unten in index.html, Abschnitt „Hier anpassen“)
- `PREMIUM_PLAETZE` – freie Premium-Plätze (0 = Warteliste)
- `WHATSAPP` / `EMAIL` – Kontaktziele des Formulars
- `THEMEN` – Themen im Laufband

## Änderungen veröffentlichen
Datei in GitHub bearbeiten oder neu hochladen („Add file“ → „Upload files“) und committen.
Netlify veröffentlicht automatisch nach jedem Commit.
