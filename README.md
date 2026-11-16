# Latin Lab

A Latin reading and writing course that runs in the browser. Open `index.html` through a web server (not by double-clicking: the offline cache and audio need `http`).

## Put it on your phone with GitHub Pages
1. Create a new public repository on GitHub, for example `latin-lab`.
2. Upload **every file in this folder** to the **root** of the repository (including the `audio` folder, `sw.js`, `manifest.webmanifest` and the icons).
3. Repository **Settings → Pages → Build and deployment**: choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then Save.
4. After a minute your app is at `https://YOUR-NAME.github.io/latin-lab/`. Open it on your phone.
5. **iPhone (Safari):** Share → **Add to Home Screen**. **Android (Chrome):** menu → **Install app** / **Add to Home screen**.

The first visit downloads the app and the first voice (about 3 MB); after that it opens without a connection. Your progress is stored on the phone, in the browser, and is separate from any progress you made in the single-file version.

## Updating
Replace the files in the repository with a newer build. The app keeps your progress. If an old copy keeps showing, close the app fully and reopen it once online.
