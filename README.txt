Daily Word 360 Journal App — GitHub Pages package
====================================================
This folder is the link version of the app, fixed for home-screen install.

Files:
- index.html — the app (calendar, time, devotional / encouragement / prayer, 30 prompts)
- manifest.json — name "Daily Word 360 Journal", standalone, theme #0e2417
- icon-192.png, icon-512.png — gold Daily Word 360 logo
- icon-maskable-512.png — logo inset on black for Android maskable icon
- apple-touch-icon.png — 180px logo for iOS
- .nojekyll — tells GitHub Pages to serve files as-is, no Jekyll processing

GitHub Pages (free, permanent):
1. Create a public repo, e.g. daily-word-360-journal
2. Upload all files in this folder to the repo root (index.html at top level)
3. Settings -> Pages -> Deploy from a branch -> main / root -> Save
4. Live at https://<username>.github.io/daily-word-360-journal/
5. Open that link in Chrome on your phone, three dots -> Install app. Icon should be the gold logo.

Saving (updated 2026-11-11): this link version DOES save entries — everything
written is kept on the buyer's own device (localStorage), so it is still there
when they come back. It saves on the device and browser where it is used; it
does not sync between devices. "Download a backup of everything" in the app
exports all entries as one JSON file.
