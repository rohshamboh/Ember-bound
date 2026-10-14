EMBERBOUND CHRONICLE — PHONE-FIRST PWA

Files:
- index.html: game and interface
- manifest.json: installable app metadata
- sw.js: offline cache
- icon.svg: app icon

Features in this upgraded prototype:
- Original epic-fantasy setting
- Six character paths (Vanguard, Arcanist, Ranger, Warden, Duelist, Runeknight) and five original races
- Turn-based combat, spellcasting, guarding and fleeing
- XP, leveling, attribute points, skill points, race traits, signature class abilities and class skill trees
- Equipment, potions, rations, merchant
- Quests, discoveries and event chronicle
- Local browser save via localStorage
- Service worker for offline loading after first visit

IMPORTANT:
A Progressive Web App must be served from HTTPS (or localhost) for installation and service-worker offline caching. Opening index.html directly from the Files app may allow the game to run, but install/offline features may not work. Host the folder using a static HTTPS host, then open its URL in Chrome and use menu > Add to Home screen / Install app.

No accounts, analytics, external libraries, ads, paid APIs or subscriptions are used by the game code. Save data is local to the browser/device profile. Clear browser data and saves may be lost, so use the in-game save plus browser/device backups where available.

UPDATE EXISTING GITHUB PAGES SITE
1. Open your existing GitHub repository on your phone.
2. Upload/replace index.html and sw.js from this package at the repository root.
3. Commit the changes to the main branch. Keep the same repository and URL.
4. Open the game in Chrome, refresh it; if the old version remains, close the game tab and reopen it after a minute. The service worker cache is versioned to refresh the app shell.

SAVE COMPATIBILITY
This update migrates the existing emberbound-save record in place. It does not intentionally clear character, inventory, quest or campaign data. As with any update, use the in-game Save now option before updating.
