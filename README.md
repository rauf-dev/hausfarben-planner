# Hausfarben-Planer V4e

## Neu
- Farb- und Presetdaten aus `data/*.json` statt aus `index.html`
- drei Kollektionen:
  - RAL Classic – Fassadenauswahl
  - Caparol 3D-EXTERIOR A1 – kuratierte Auswahl
  - Caparol 3D-System PLUS – erweiterte Auswahl
- Caparol Siena 10, 20, 25, 30, 35 und 40 enthalten
- Suche, Kategorien und Pagination für Farbfelder
- zwei Preset-Bibliotheken:
  - Klassisch & zurückhaltend
  - Kontrastreich & ausdrucksstark
- jeweils 14 Varianten, mit Pagination
- Save/Load, JSON und PNG/Gestaltungsblatt bleiben erhalten

## Wichtiger Hinweis zu Farbdaten
Caparol stellt offizielle digitale RGB-Werte als Download bereit. In dieser V3i-Version sind
Caparol-Farbcodes und -Familien erweitert, die Hex-Werte aber als unverbindliche
Bildschirmnäherungen gekennzeichnet. Die Kollektion `3D-EXTERIOR A1 – kuratierte Auswahl`
ist ausdrücklich **nicht** die vollständige offizielle 222er-Liste.

## Lokal testen
Wegen der externen JSON-Dateien sollte die App über GitHub Pages oder einen lokalen Webserver
geöffnet werden. Direktes Öffnen von `index.html` als `file://` kann Browser-CORS-Fehler erzeugen.

Auf dem Mac im Projektordner:
```bash
python3 -m http.server 8000
```
Dann `http://localhost:8000` öffnen.

## GitHub aktualisieren
1. Den Inhalt dieses Ordners in deinen lokalen Repository-Ordner kopieren/ersetzen.
2. GitHub Desktop öffnen.
3. Änderungen prüfen.
4. Commit-Nachricht: `Add V3i palette architecture and preset pagination`
5. **Commit to main**
6. **Push origin**


## Neu in V4e
- Fotovorschau als zusätzlicher Ansichtsmodus
- Toggle zwischen SVG-Ansicht und Fotovorschau
- Näherungsweise Farbüberlagerung auf Basis eines Originalfotos

Die Fotovorschau ist absichtlich als Annäherung gekennzeichnet. Bäume, Schatten, Perspektive und Materialstruktur bleiben aus dem Foto erhalten.


V4e behebt den Ansichtswechsel und verwendet einen sehr kompakten SVG/Foto-Schalter direkt über der Hausansicht.


## Neu in V4e
- fein kalibrierte Fotomasken aus der manuellen Fotoabstimmung
- Masken liegen extern in `data/photo-masks.json`
- Fotoflächen sind direkt anklickbar
- sehr dünne Auswahlkontur in der Fotovorschau
- unangepasste Zonen bleiben vollständig im Originalfoto
- dunkle Vordergrundobjekte wie Baum, Lampe und Büsche werden weitgehend von der Umfärbung ausgeschlossen
- Licht, Schatten und Putzstruktur bleiben erhalten


## Neu in V4e
- massive Caparol-Erweiterung
- `Caparol 3D-System PLUS` jetzt mit 177 Tönen
- `Caparol 3D-EXTERIOR A1` jetzt mit 119 kuratierten Tönen
- viele zusätzliche Codes aus Familien wie:
  - Palazzo
  - Ginster
  - Siena
  - Granit
  - Tundra
  - Patina
  - Oliv
  - Rose
  - Cameo
  - Lachs
  - Onyx
  - Pacific
  - Lazur
  - Coelin
  - Verona
  - Arctis

## Hinweis
Die Caparol-Erweiterung ist für die aktuelle Entwurfsarbeit gedacht. 
Die Codes sind stark erweitert, die angezeigten Bildschirmfarben bleiben aber weiterhin
unverbindliche Arbeitswerte.
