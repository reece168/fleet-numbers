BUS FLEET & RUNNING BOARD MANAGER — PWA PACKAGE

This package keeps the existing fleet manager and adds the files required for installation as a Progressive Web App (PWA).

IMPORTANT: To install as a PWA on Android, the files must be hosted on an HTTPS website (or localhost). Opening index.html directly from Files will run the page but will not enable PWA installation/offline caching.

EASY HOSTING OPTION (GitHub Pages):
1. Extract this ZIP on a computer.
2. Create a GitHub repository and upload all files/folders inside this package (index.html, manifest.webmanifest, sw.js, icons/).
3. In the repository, open Settings → Pages. Choose deploy from a branch, select main and /(root), then Save.
4. Wait for GitHub Pages to publish the HTTPS website.
5. Open the published website in Chrome on your Android phone.
6. Tap Chrome ⋮ → Install app (or Add to Home screen), then confirm.

DATA NOTE: Existing app data is stored in the browser/device where you use it. It does not automatically sync between phones or browsers. Use the in-app Backup/export tools regularly. The PWA cache allows the app shell to load offline after the first successful visit; imports/exports should be tested on your device.
