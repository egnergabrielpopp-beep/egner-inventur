EGNER INVENTUR – Smartphone-/Tablet-App (PWA)

DATEIEN
- index.html: die Inventur-App
- manifest.json: Installationsinformationen
- sw.js: Offline-Caching nach dem ersten Laden
- icons/: App-Symbole

VERÖFFENTLICHEN ÜBER GITHUB PAGES
1. Lade ALLE Dateien und den Ordner icons in das Repository egner-inventur hoch.
2. Die Datei index.html muss direkt im Hauptordner (Root) liegen.
3. Aktiviere GitHub Pages: Settings > Pages > Deploy from a branch > main > /(root) > Save.
4. Öffne die veröffentlichte HTTPS-Adresse auf dem Smartphone oder Tablet.
5. Android/Chrome: Menü ⋮ > „App installieren“ oder „Zum Startbildschirm hinzufügen“.
   iPhone/iPad/Safari: Teilen > „Zum Home-Bildschirm“.

OFFLINE
Die App muss zunächst einmal online über die veröffentlichte HTTPS-Adresse geöffnet werden, damit die App-Dateien zwischengespeichert werden. Die Inventurdaten werden auf diesem Gerät im Browser gespeichert (localStorage). Sie werden nicht automatisch mit anderen Geräten synchronisiert. Browserdaten nicht löschen, wenn die erfassten Daten erhalten bleiben sollen.

HINWEIS
Die App ist eine installierbare Web-App (PWA), keine native App aus Play Store oder App Store.
