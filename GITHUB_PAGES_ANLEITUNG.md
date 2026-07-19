# GitHub Pages – Schritt-für-Schritt-Anleitung

Diese Anleitung verwendet **GitHub Desktop**, weil damit Änderungen, Commits und Pushes leichter nachvollziehbar sind.

## 1. Projekt entpacken
1. ZIP-Datei herunterladen.
2. In einen dauerhaften Ordner entpacken, zum Beispiel:
   `Dokumente/Hausfarben-Planer`
3. Prüfen, dass `index.html` direkt im Hauptordner liegt.

## 2. GitHub Desktop installieren und anmelden
1. GitHub Desktop installieren.
2. Mit deinem GitHub-Konto anmelden.
3. In GitHub Desktop: **File → Add local repository**.
4. Den entpackten Projektordner auswählen.
5. Falls der Ordner noch kein Repository ist, **create a repository here** wählen.

Empfohlene Angaben:
- Name: `hausfarben-planer`
- Description: `Interaktiver Hausfarben-Planer`
- Git ignore: None
- License: None oder nach eigener Wahl

## 3. Ersten Commit erstellen
1. Links unten als Summary eingeben:
   `Initial version of house color planner`
2. **Commit to main** anklicken.

## 4. Repository auf GitHub veröffentlichen
1. Oben **Publish repository** anklicken.
2. Repository-Name prüfen.
3. Für eine öffentliche GitHub-Pages-Seite das Repository öffentlich veröffentlichen.
4. **Publish Repository** anklicken.

## 5. GitHub Pages aktivieren
1. Repository im Browser öffnen.
2. **Settings** öffnen.
3. Links **Pages** auswählen.
4. Unter **Build and deployment**:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/(root)`
5. **Save** anklicken.

Nach der Bereitstellung erscheint dort die öffentliche Adresse, typischerweise:
`https://DEIN-BENUTZERNAME.github.io/hausfarben-planer/`

## 6. Spätere Änderungen veröffentlichen
1. Lokale Dateien ersetzen oder bearbeiten.
2. GitHub Desktop öffnen.
3. Änderungen links prüfen.
4. Eine kurze Summary eingeben, zum Beispiel:
   `Add new color presets`
5. **Commit to main** anklicken.
6. **Push origin** anklicken.
7. Einige Minuten warten und die Webseite neu laden.

## 7. Entwürfe über Git verwalten
Exportierte JSON-Entwürfe können in den Ordner `designs/` kopiert werden.

Danach:
1. GitHub Desktop öffnen.
2. JSON-Datei als Änderung prüfen.
3. Commit erstellen.
4. Push origin.

Dadurch wird der Entwurf im Repository versioniert. Die aktuelle App lädt diese Dateien noch nicht automatisch in die Oberfläche; sie dienen zunächst als archivierte, versionierte Entwürfe.

## Wichtige Hinweise
- Keine Passwörter, Tokens oder privaten Daten ins Repository legen.
- Bei einem öffentlichen Repository sind Projektdateien und JSON-Entwürfe öffentlich sichtbar.
- Die Datei `.nojekyll` ist bereits enthalten.
