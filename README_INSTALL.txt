OUR PLACES LIBRARY V3 — GITHUB UPDATE

This version adds:
- an index of current and future journeys
- new journey creation
- direct camera/photo-library uploads
- local photo galleries
- captions and place labels
- JSON export and import backups
- iPhone-to-iPad transfer through the backup file
- the original Santo Stefano itinerary as Volume I

UPLOAD TO YOUR EXISTING GITHUB REPOSITORY
1. Extract this ZIP on the Windows PC.
2. Open the existing GitHub repository.
3. Upload all files from this package at the repository root.
4. Allow GitHub to replace index.html, manifest.webmanifest, service-worker.js and the icons.
5. Commit the changes.
6. GitHub Pages normally republishes automatically within 1-3 minutes.
7. Open the app once in Safari and once from the Home Screen icon while online.

IF THE OLD VERSION REMAINS
- Close the app completely and reopen it.
- In Safari, revisit the GitHub Pages address and refresh.
- If necessary, delete the Home Screen icon, revisit the address in Safari and add it again.
The service worker cache name has changed to our-places-library-v3, which normally forces the update.

PHOTO STORAGE
The app saves resized JPEG copies locally in IndexedDB. Originals remain in Apple Photos.
Browser storage is not a permanent archive. Use Export Backup regularly.
The JSON backup contains trip records and the saved photo copies, so it may become large.

IPHONE AND IPAD
Data does not automatically sync:
1. Export backup on the device containing the latest collection.
2. Save it in Files or transfer it with AirDrop.
3. Import the backup on the other device.

PRIVACY
The GitHub Pages site itself contains only the app code and the built-in itinerary.
Your added photographs and personal journey data remain in local browser storage unless you export or deliberately share the backup.
