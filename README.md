# iPhone Simulator — iOS 26 style

A mobile-first web simulation inspired by iOS. It is **not** Apple's iOS and does not connect to real phone calls, SMS, Instagram, or Apple services. Instagram, chats, calls, notifications, and system controls are demo interactions.

## Files
- `index.html` — app shell and screen structure.
- `styles.css` — visual design, responsive layout, glass effects, app styles.
- `data.js` — starter content (profile, apps, sample posts, stories, chats, photos).
- `app.js` — interactions, app routing, data editor, local save, backup/restore.

## Publish with GitHub Pages (iPhone-friendly)
1. Sign in to GitHub in Safari and create a **new public repository** named `ios26-simulator` (or another name). Do not use the old project repository.
2. Upload all four files from this folder to the root of that repository. Keep the exact filenames and capitalization.
3. Open repository **Settings → Pages**.
4. Under Build and deployment choose **Deploy from a branch**, select branch `main` and folder `/ (root)`, then Save.
5. Wait for the Pages URL to appear. It normally looks like `https://YOUR-USERNAME.github.io/ios26-simulator/`.
6. Open the URL in Safari on your iPhone. Use Share → Add to Home Screen for an app-like shortcut.

## Editing data
- Change starter content in `data.js` before publishing.
- Once the site is live, use Settings inside the simulator to edit the profile, posts, stories, contacts, photos and backup files.
- Code changes: edit the relevant file in GitHub and commit the change. Pages will redeploy automatically.

## Data and photos
- Edits are stored in `localStorage` on the current browser/device. They do not automatically sync across devices and can be lost if Safari website data is cleared.
- Use Settings → Export backup regularly. Import backup restores a previous JSON export.
- Photos selected from the device are embedded as data URLs in local storage. Very large images may exceed browser storage limits; use smaller images where possible.
- To make a photo appear on every device, upload it to a public image host and use its direct image URL in the editor. Do not use private or sensitive photos in a public repository.

## Notes
- This is a starter project. Some features (real camera capture, real call/audio, authentic iOS system gestures and cloud sync) are intentionally simulated or not implemented.
