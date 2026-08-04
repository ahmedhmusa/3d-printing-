# 3D Printing

A sales &amp; expense tracker for a small 3D printing business, built as a
static web app. Currency: Maldivian Rufiyaa (MVR). Data saves to the
browser's local storage — fully offline after the first load, no backend,
no account.

## Deploy it with GitHub Pages (free, ~2 minutes)

1. **Create a repository**
   - Go to [github.com/new](https://github.com/new)
   - Name it anything, e.g. `spool-ledger`
   - Keep it **Public** (required for free GitHub Pages)
   - Click **Create repository**

2. **Upload the files**
   - On the new repo's page, click **"uploading an existing file"**
   - Drag in all the files from this folder: `index.html`, `manifest.json`,
     `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`
   - Scroll down, click **Commit changes**

3. **Turn on GitHub Pages**
   - Go to the repo's **Settings** tab → **Pages** (left sidebar)
   - Under "Build and deployment" → **Source**, choose **Deploy from a branch**
   - Under **Branch**, choose `main` and folder `/ (root)`, click **Save**
   - Wait ~1 minute, then refresh — GitHub will show you a live URL like:
     `https://YOUR-USERNAME.github.io/spool-ledger/`

4. **Open it on your iPhone**
   - Open that URL in **Safari**
   - Tap the **Share** icon → **Add to Home Screen**
   - It now behaves like a real installed app — its own icon, full-screen,
     no browser bar — and saves data locally on that device.

## Updating later

To change anything (colors, categories, features), edit `index.html`
directly on GitHub (click the file → pencil/edit icon → commit), or edit
it locally and re-upload. Pages redeploys automatically within a minute
of any commit.

## Notes

- Data lives in that browser's local storage. Clearing Safari's site data,
  or switching devices/browsers, means starting fresh — this isn't synced
  anywhere. If you need multi-device access, ask for the cloud-storage
  variant instead.
- Everything runs client-side; nothing is sent to any server other than
  GitHub Pages serving the static files themselves.
