Bintaro 60K — iPhone / PWA version

IMPORTANT: iOS will not install a PWA correctly from a downloaded local HTML file. It must be served from an HTTPS website.

Recommended free setup: GitHub Pages
1. Create a new private or public GitHub repository. (GitHub Pages availability for private repositories depends on your GitHub plan.)
2. Upload everything in this folder to the repository root.
3. In GitHub: Settings > Pages > Build and deployment > Deploy from a branch.
4. Select the main branch and / (root), then Save.
5. Open the resulting HTTPS address in Safari on the iPhone.
6. Tap Share > Add to Home Screen > Add.
7. Launch Bintaro 60K from the Home Screen.

Daily use
- The Today screen uses the iPhone's current local date automatically.
- You do not export/import every day.
- Run logs and Easy Midpoint edits are saved in local browser storage on that iPhone.
- The app refreshes after a date change, when returning to the app, or while it remains open.
- After the first successful online load, the service worker caches the app for offline use.

Backup
Use Setup > Export training data occasionally. Import is only needed when restoring or moving to another browser/device.

Data note
This is a personal static app. There is no cloud database or account sync. Removing the app/site data can remove locally stored logs, so occasional JSON backups are recommended.
