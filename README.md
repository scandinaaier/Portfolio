# Portfolio App — Install on Android

## Files in this folder
```
index.html     ← the entire app
manifest.json  ← makes it installable
sw.js          ← offline support
icon-192.png   ← home screen icon
icon-512.png   ← home screen icon (large)
```

## How to get it on your phone

### Option A — GitHub Pages (recommended, free, 5 min)

1. Go to **github.com** and sign in (or create a free account)
2. Click **New repository** → name it `portfolio` → set to **Public** → click Create
3. Click **uploading an existing file** and drag in ALL 5 files from this folder
4. Commit the files
5. Go to **Settings → Pages → Source → main branch → / (root)** → Save
6. Your app will be live at: `https://YOUR-USERNAME.github.io/portfolio`

Then on your Android phone:
1. Open **Chrome** and go to that URL
2. Tap the **⋮ menu → "Add to Home screen"**
3. Tap **Add** — it now lives on your home screen like a native app
4. Open it — full screen, no browser bar, no chrome

### Option B — Quick local test first
If you have Python installed on your computer:
```
cd this-folder
python3 -m http.server 8080
```
Then on your phone (same WiFi): open Chrome → `http://YOUR-COMPUTER-IP:8080`

---
## Using the app
- **Single tap** a tile → full screen company detail
- **Double tap** a tile → QR code (other person scans to go to the URL)
- **Long press** a tile → edit / add company details
- Empty dimmed tiles → tap to add a new company
