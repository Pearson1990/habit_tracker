HABIT TRACKER (standalone)

Files
  index.html            the app
  manifest.webmanifest  lets phones and browsers install it as an app
  sw.js                 saves the app for offline use
  icons/                app icons

Quickest ways to use it

1) Host it (best: gives you install + offline on every device)
   - Netlify: go to app.netlify.com/drop and drag this whole folder onto the page.
   - GitHub Pages: put these files in a repository, then Settings > Pages.
   Open the address it gives you. It must be https for install and offline to work.
   - iPhone: open the address in Safari > Share > Add to Home Screen.
   - Android / PC: open it in Chrome or Edge and choose Install app.

2) Just open index.html on your computer
   Works in any browser. Offline install is not available this way.

Your data
  Habits are saved in the browser on the device you use. Different devices do not
  sync. Use "Export backup" on the Today page to save a file, and "Import backup"
  on another device to load it. Back up now and then, because clearing browser
  data erases your habits.

Updating
  If you change any files, edit the CACHE name in sw.js (for example habit-tracker-v2)
  so installed copies pick up the new version.
