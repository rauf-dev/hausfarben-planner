# Hausfarben-Planer V4c – Photo Mask Calibration

Diese Version ist bewusst ein reines Kalibrierungswerkzeug.

## Enthalten
- Originalfoto
- sichtbare Masken pro logischer Zone
- Auswahl per Klick oder Zonenliste
- Umschaltung alle Masken / nur aktive Maske
- Drag-and-drop der Polygonpunkte
- JSON-Export und -Import
- Reset auf Ausgangsmasken

## Noch nicht enthalten
- keine Farbanwendung
- keine Paletten
- keine Speicherung von Hausentwürfen

## Lokal testen
Wegen `fetch()` bitte nicht direkt per `file://` öffnen.

```bash
python3 -m http.server 8000
```

Dann `http://localhost:8000` öffnen.


## Revision 2
- Fehler behoben, durch den die Foto-/SVG-Bühne im Flex-Layout auf 0 × 0 kollabieren konnte.
- Die Bühne nutzt nun zuverlässig die verfügbare Höhe.
- Verständliche Fehlermeldung, falls `data/photo-preview.jpg` fehlt.
