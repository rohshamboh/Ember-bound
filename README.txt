EMBERBOUND CHRONICLE — CHARACTER VISUAL UPDATE

Upload the contents of this folder to the ROOT of your existing GitHub repository for Emberbound Chronicle, replacing index.html and sw.js and adding the art folder. Keep manifest.json and icon.svg if they already exist.

Files:
- index.html: updated character screen with race/class portraits and a dynamic selected-character showcase
- sw.js: cache version updated to refresh the art assets
- art/: original cropped character portraits used by the screen

SAVE COMPATIBILITY: This update keeps the existing localStorage save key (emberbound-save) and adds no destructive reset. Back up your save if possible before updating.

After committing to main, wait for GitHub Pages to publish. Reopen the same site URL. If an old version appears, close the app/tab and reopen after a short wait so the new service worker can install.
