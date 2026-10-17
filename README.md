# Lernkalender

Web-App für Lernsessions (Timer mit Etappen), Wochenplan, To-Dos pro Fach und Statistik.
Die Daten liegen als `lernkalender.json` im App-Ordner des eigenen OneDrive (`Apps/Lernkalender`).

- Läuft auf GitHub Pages: https://maeexl.github.io/Lernkalender/
- Installieren: Windows → in Edge öffnen, Menü → „Apps“ → „Diese Website als App installieren“.
  iPhone → in Safari öffnen, Teilen → „Zum Home-Bildschirm“.
- Anmeldung: Microsoft-Konto (OAuth 2.0 mit PKCE, ohne Zusatzbibliothek), Berechtigung nur `Files.ReadWrite.AppFolder`.

## Dateien
- `index.html` – die komplette App (Oberfläche, Logik, OneDrive-Sync)
- `sw.js` – Service Worker, damit die App offline startet
- `manifest.webmanifest`, `icons/` – App-Name und Symbole
