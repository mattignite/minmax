# Bloom · Lift & Nourish

A separate workout app for your partner, with a fresh log and a lower-body priority.

## Start

1. Extract the ZIP on a computer.
2. Open `index.html` in a browser to review the app locally.
3. The beginner program is already loaded. No backup import is necessary. Start with workout A.
4. Use the menu (⋯) for the program guide, check-ins, workout editing, exercise management and backups.

The included `bloom-starter-backup.json` is an optional empty reset template for Bloom. It contains no history or weigh-ins. Importing it later replaces Bloom's current records after an in-app confirmation, with a recovery copy retained.

## Use on her phone

Use the same static hosting method as Min-Max, but deploy Bloom to its own folder or URL. Upload only:

- `index.html`
- `sw.js`
- `manifest.webmanifest`
- `icon.svg`
- `icon-192.png`
- `icon-512.png`
- `apple-touch-icon.png`

Once the app has an HTTPS address, open it in Safari on iPhone and use Share → Add to Home Screen. On Android, open it in Chrome and use Install app or Add to Home Screen. Installation labels vary with the browser. Load the app once online before relying on offline use.

A ZIP file is the app's source package, not a phone installer. Local HTML files can be reviewed on a computer; home-screen installation and reliable offline behavior require HTTPS or localhost. This package has not been published or installed on her phone.

Keep the workout/food guide and any exported personal backups off public hosting. They do not need to be deployed with the app.

## Separate records

Bloom has its own browser storage keys, backup format and cache namespace. It starts without your Min-Max records and rejects Min-Max backups. Its records stay only in the browser or installed app on the device being used; they do not sync between phones or browsers.

Export backups regularly, and before moving devices or clearing browser data. Import the Bloom backup on the new device to continue. If the browser blocks storage, Bloom displays a notice to export before closing.

## Editing the plan

Tap the menu → Edit workouts to adjust exercises, rep ranges, sets and rest. Tap an exercise name during a session to choose an alternative. Each exercise keeps its own recorded history. New saved sessions retain their workout template so later edits do not rewrite their context.

The beginner phase uses two sets per exercise for eight substantial sessions. It can be extended through Program & guide. Partial workouts are kept, but do not count toward the phase unless at least three quarters of planned working sets have complete entries.

## Validation

JavaScript syntax checks and 22 automated behavior checks passed, including fresh data, isolation from Min-Max, workout sequencing, phase progression, drafts, weight averages, food check-ins, backup round trips, invalid import rejection and rollback after a storage failure. Live browser validation status is recorded in Validation.md.
