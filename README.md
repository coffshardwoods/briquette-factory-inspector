# Briquette Factory Inspector

Mobile-first factory visit checklist: 31 inspection items, notes, photographs, and a post-visit assessment.

**App:** https://coffshardwoods.github.io/briquette-factory-inspector/

## Install on iPhone

1. Open the app URL in Safari while online and wait for the checklist to appear.
2. Tap Share, then **Add to Home Screen**. If offered, turn on **Open as Web App**, then tap **Add**.
3. Open the new Home Screen icon while online so the app files are cached.
4. Before leaving for a factory, turn on Airplane Mode and reopen the Home Screen app. Confirm the checklist and an existing visit still load.

## Records and backups

Visits and photo blobs are stored in the device's IndexedDB. The app makes no upload requests for this data. GitHub Pages only serves the application files. Use **Backup JSON (including photos)** after each visit and save the downloaded file somewhere you control. The backup contains inspection details and photos, so handle it as confidential. **Restore backup** imports visits and photos from that file. Keep a separate backup before restoring another file.

Browser-managed storage can be removed by iOS or by clearing website data. Large photo collections may reach device storage limits. Video files are not stored. The Print button prints the full checklist.

## Publishing

GitHub Pages publishes from `main` at `/ (root)`. Keep `.nojekyll` in the root. After editing cached app files, increment the `CACHE` name in `sw.js`, then verify the new site online and in Airplane Mode.
