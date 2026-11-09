Trendfloor Bodenplan 015 – GitHub Pages / PWA

Dateien:
- index.html: App-Version 015
- manifest.json: Installationsdaten der Handy-App
- sw.js: Offline-Cache (PWA Service Worker)
- icons/: App-Symbole
- Version-014-Sicherheitskopie.html: unveränderte Originaldatei 014

GitHub:
1. Neues Repository anlegen (z. B. Trendfloor-Bodenplan-015).
2. Den INHALT dieses Ordners direkt in das Hauptverzeichnis des Repositorys hochladen.
3. Settings > Pages öffnen.
4. Bei Build and deployment: Deploy from a branch wählen.
5. Branch main und Ordner /(root) auswählen, speichern.
6. Nach Veröffentlichung die angezeigte GitHub-Pages-Adresse mit HTTPS öffnen.

Android:
Die veröffentlichte HTTPS-Adresse in Chrome öffnen, Menü (drei Punkte) > App installieren.

Wichtig:
- Version 014 bleibt als separate Sicherheitskopie erhalten.
- Der bisherige lokale Speicher-Schlüssel der App bleibt absichtlich unverändert.
- Browser-Speicher bleibt grundsätzlich an Browser/Gerät gebunden. Vor Gerätewechsel die Sicherung in der App exportieren.
- Nach dem ersten Online-Aufruf und erfolgreichem Laden kann die App über den Service Worker offline starten.
