# RegalScan – Deployment & Update-Anleitung

## Einmalig einrichten (15 Minuten)

### 1. GitHub-Konto erstellen
- Gehe auf **github.com** → Sign up (kostenlos)

### 2. Repository erstellen
- Klicke auf **"New repository"**
- Name: `regalscan` (oder beliebig)
- **Public** auswählen
- Klicke **"Create repository"**

### 3. Dateien hochladen
- Klicke **"uploading an existing file"**
- Diese 5 Dateien hochladen:
  - `index.html`
  - `manifest.json`
  - `sw.js`
  - `icon-192.png`
  - `icon-512.png`
- Klicke **"Commit changes"**

### 4. GitHub Pages aktivieren
- Gehe zu **Settings → Pages**
- Source: **"Deploy from a branch"**
- Branch: **main** → Ordner: **/ (root)**
- Klicke **Save**
- Nach 1–2 Minuten ist die App erreichbar unter:
  `https://DEIN-USERNAME.github.io/regalscan`

---

## Updates einspielen (2 Minuten)

Wenn du eine neue Version der `index.html` hast:

1. Gehe auf dein GitHub Repository
2. Klicke auf `index.html`
3. Klicke das **Stift-Symbol** (Edit)
4. Oder: Klicke **"Add file → Upload files"** und lade die neue `index.html` hoch
5. Klicke **"Commit changes"**

**→ Alle Kollegen sehen beim nächsten Öffnen automatisch einen Hinweis "Neue Version verfügbar" und können mit einem Klick aktualisieren.**

---

## App auf iPad/iPhone installieren

1. Safari öffnen → URL eingeben
2. Teilen-Symbol (Quadrat mit Pfeil nach oben) tippen
3. **"Zum Home-Bildschirm"** wählen
4. Name bestätigen → **Hinzufügen**

Die App erscheint jetzt wie eine native App auf dem Homescreen – ohne Browser-Leiste, im Vollbild.

---

## Daten

Alle Daten werden **lokal** im Browser gespeichert (localStorage). Jedes Gerät hat seine eigenen Daten. Für geräteübergreifende Synchronisation wäre ein Backend nötig.
