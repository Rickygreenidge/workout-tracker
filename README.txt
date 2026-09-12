# 8-Week Workout Tracker Pro — iPhone App

This package is a Progressive Web App (PWA). It can be installed on an iPhone
Home Screen and opened like an app.

## Important
The app must be served from HTTPS (or localhost) for service-worker/offline
features. A normal `file://` link is not enough.

## iPhone installation
1. Put this folder on an HTTPS web host.
2. Open the site's address in Safari on your iPhone.
3. Tap Share.
4. Tap "Add to Home Screen".
5. Keep "Open as Web App" enabled if iOS shows that option.
6. Tap Add.

Your workout data is stored locally in the browser. Use the app's Export
function periodically to make a backup.

The easiest free hosting options are GitHub Pages or Netlify. The folder's
`index.html` is the app entry point.
