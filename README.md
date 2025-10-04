# TOTO Calendar - Desktop App (Electron scaffold)

This package wraps the provided `index.html` (the uploaded `F1.html`) into a minimal Electron app.

## How to run (Windows / macOS / Linux)

1. Install Node.js (v16+ recommended) from https://nodejs.org/.
2. Open a terminal in this folder.
3. Install Electron (one-time):  
   ```
   npm install --save-dev electron
   ```
   or to save as a runtime dependency:
   ```
   npm install electron
   ```
4. Start the app:
   ```
   npm start
   ```

This will open a desktop window running the calendar app.  
If you'd like a packaged executable (.exe / .dmg / AppImage), use tools like `electron-builder` or `electron-forge` — I can help scaffold that if you want.

## Notes
- The original file `F1.html` was copied into `index.html` and left unchanged.
- Data (calendar entries) is stored in the browser's IndexedDB / localStorage for persistence per user profile.
