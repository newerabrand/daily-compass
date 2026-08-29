Daily Compass — For Daily Life
PWA package — icon fixed

Files:
- index.html
- manifest.json
- service-worker.js
- icons/icon-192.png
- icons/icon-512.png

Icon fix:
- The supplied Daily Compass artwork is used for both PWA icons.
- Icons are stored in the exact `icons/` folder referenced by the manifest.
- Icon dimensions are exactly 192×192 and 512×512.
- index.html includes explicit favicon and Apple touch icon references.
- Service-worker cache is bumped to v2 so the old cached icon is replaced.

Cloud/Supabase sync and existing app logic in index.html are preserved.
