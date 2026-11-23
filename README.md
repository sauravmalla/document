# DocTools

Offline web app. Tabs: **Convert** (Word <-> PDF), **Photos** (edge-detecting scanner, passport photos, editor, crop, add/remove objects), **Edit metadata**, **Compress**. Everything runs on the device. Saved files keep your original filename with "-updated" added. Install on iPhone from Safari: **Share -> Add to Home Screen**.

## Put it on GitHub Pages
1. On github.com click **New repository**, name it `doctools`, set **Public**, create it.
2. Click **uploading an existing file**, then drag in **everything inside** the unzipped `doctools` folder (not the folder itself). Wait for all files, then **Commit changes**.
3. **Settings -> Pages**: Source **Deploy from a branch**, Branch **main**, folder **/ (root)**, **Save**.
4. After 1-3 minutes it is live at `https://YOUR-USERNAME.github.io/doctools/`

## Install on iPhone
Open that address in **Safari**, tap **Share -> Add to Home Screen -> Add**. While on Wi-Fi, open Photos -> Passport once so the AI model (~55 MB) downloads. After that it all works offline.
