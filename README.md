# landingpagetests

SunMini-Landingpage für LumenHaus: `index.html` (eigenständig, Inline-CSS/JS).

## Vor Go-Live anpassen (alle Stellen im Code mit `TODO` markiert)
- `SALE_PRICE`, `OFFER_END_DATE`, `UNITS_LEFT` – Konfigurationsblock oben im `<script>` am Seitenende
- Händler-URLs (aktuell Startseiten) und Händler-Logos (aktuell Platzhalter-Wortmarken)
- `assets/sunmini-poster.jpg` – derzeit Standbild aus dem Video, durch das Keyvisual ersetzen
- Award-Badge im Hero verifizieren oder entfernen
- Canonical-/Open-Graph-URLs, Social-Media-Links, Impressum/Datenschutz/AGB-Pfade
- FAQ-Antworten mit der Live-Seite abgleichen

## Assets
| Datei | Zweck | Größe |
|---|---|---|
| `sunmini-loop-1080p.mp4` / `-540p.mp4` | Hero-Loop (aktiv), 14 s Installationssequenz | 4,5 MB / 1,2 MB |
| `sunmini-video-1080p.mp4` / `-540p.mp4` | Volles Video (Alternative, im Code kommentiert) | 18,6 MB / 5,4 MB |
| `sunmini-video.mp4` | Rohvideo 4K – nicht auf der Seite verwendet, nicht mit deployen | 77,6 MB |
| `sunmini-poster.jpg` / `sunmini-og.jpg` | Poster/Fallback, Open-Graph-Bild | |

Lokal ansehen: `python3 -m http.server` im Ordner, dann http://localhost:8000
