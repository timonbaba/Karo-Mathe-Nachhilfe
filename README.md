# Stift und Blatt – Mathe-Nachhilfe Website

Statische Website, kein Build-Schritt nötig.

## Struktur
- `index.html` – die Seite
- `impressum.html`, `datenschutz.html` – Rechtliches (gelb markierte Stellen vor Livegang ergänzen)
- `assets/timon.jpg` – Porträt
- `fonts/` – lokal eingebundene Schriften (Albert Sans, Caveat; SIL Open Font License, siehe OFL-*.txt)
- `favicon.svg`
- `FOTOS.md` – Shot-Liste für eigene Fotos

## Häufige Anpassungen (ganz unten in index.html, Abschnitt „Hier anpassen“)
- `PREMIUM_PLAETZE` – freie Premium-Plätze (0 = Warteliste)
- `WHATSAPP` / `EMAIL` – Kontaktziele des Formulars
- `CAL_LINK` – Cal.com-Link für die Terminbuchung

## Änderungen veröffentlichen
Datei in GitHub bearbeiten oder neu hochladen („Add file“ → „Upload files“) und committen.
Cloudflare (Workers) veröffentlicht automatisch nach jedem Commit auf `main`.

## Frühere Version
Der Stand vor dem Redesign liegt im Branch `backup/vor-redesign`.
