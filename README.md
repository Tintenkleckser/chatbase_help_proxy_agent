# Chatbase Help Proxy (Vercel)

Dieses Projekt schreibt `/help` auf die Chatbase-Help-Seite deines Agents um.

- Agent-ID ist bereits gesetzt: `Vj3UshuMv93LH37DTH-pV`
- Die Rewrites findest du in `vercel.json`.

## Deploy zu Vercel
- Repo auf Git pushen und in Vercel importieren **oder**
- Vercel CLI nutzen (`npm i -g vercel` → im Ordner `vercel`)

Nach dem Deploy: `https://<dein-projekt>.vercel.app/help`

## FlutterFlow-Einbindung
- **Mobile (iOS/Android):** WebView → URL: `https://<dein-projekt>.vercel.app/help`
- **Web:** Launch URL (neuer Tab) oder IFrame (falls erlaubt).
