Elevor360D Moving Box Tracker V5 — FREE ADVERTISING EDITION

This is a separate copy of V4. Existing box storage keys and backup/restore remain unchanged. No licensing has been added.

TEST
1. Extract ZIP and upload all contents to a NEW GitHub Pages repository (do not overwrite your paid V4).
2. Open its GitHub Pages HTTPS URL. A sample Elevor360D advert appears below the header.
3. Try adding a box, refreshing, finding it, and using backup/restore.
4. On your phone, install from the browser if the install prompt is available.

PUBLISH ADS FROM UNIVERSAL ADVERTISING MANAGER V1
1. In manager, choose Export & Publish > Download adverts.json.
2. Download stored images from the manager.
3. Upload adverts.json to advertising/adverts.json in THIS new app repository.
4. Upload the image files to advertising/images/ with exactly the filenames exported by the manager.
5. In manager, choose target 'Business / utility apps' or 'All', or target 'Specific apps' with app ID moving-box-tracker.
6. Refresh the app while online; it checks the feed on opening and approximately every 30 minutes.

CENTRAL FEED OPTION
Edit ad-config.json feedUrl to a FULL HTTPS URL pointing at the shared advertising/adverts.json file on your own GitHub Pages site. The image paths in the feed are relative to that feed URL. Make sure your hosting allows cross-origin fetch (GitHub Pages normally does). This lets multiple apps share the same advert feed.

OFFLINE
The last successfully downloaded advert metadata is cached locally; sample advert image is precached by the service worker. Remote images previously viewed may depend on browser cache; for reliable offline external images, use same-origin hosted assets and a service-worker caching enhancement in a later release. All box-tracking features remain offline-first.

NOTE
The ad banner is deliberately non-interruptive. The link opens in a new tab. The banner does not collect tracking data or process advertiser payments. Manager exports must be published manually.
