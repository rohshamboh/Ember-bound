EMBERBOUND CHRONICLE — PHONE-FIRST PWA

Files:
- index.html: game and interface
- manifest.json: installable app metadata
- sw.js: offline cache
- icon.svg: app icon

Features in this first prototype:
- Original epic-fantasy setting
- Four character paths
- Turn-based combat, spellcasting, guarding and fleeing
- XP, leveling and attribute points
- Equipment, potions, rations, merchant
- Quests, discoveries and event chronicle
- Local browser save via localStorage
- Service worker for offline loading after first visit

IMPORTANT:
A Progressive Web App must be served from HTTPS (or localhost) for installation and service-worker offline caching. Opening index.html directly from the Files app may allow the game to run, but install/offline features may not work. Host the folder using a static HTTPS host, then open its URL in Chrome and use menu > Add to Home screen / Install app.

No accounts, analytics, external libraries, ads, paid APIs or subscriptions are used by the game code. Save data is local to the browser/device profile. Clear browser data and saves may be lost, so use the in-game save plus browser/device backups where available.
