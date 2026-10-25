# Min-Max: balanced four-day update

This is a revised copy of your app. Your original project folder and uploaded backup have not been edited.

## Review and use

1. Extract the ZIP to its own folder.
2. Open `index.html` in your usual browser for a local review.
3. Open the menu (⋯), choose **Import backup**, and select the included `minmax-balanced-backup.json`.
4. Confirm the import in the app. You should see **31 sessions** in Workout log and the new A–D workout templates on the home screen.
5. Start with A. The first eight saved sessions use the easier return phase. The next workout follows the sequence across missed calendar days.

The included revised backup preserves every saved session, original set entry, exercise alias and substitution from your October 25 export. It changes the active workout templates and archives the previous templates so old sessions remain readable. Use this backup with the revised app; the older app does not understand all version 3 fields.

You can instead import your original backup to review your existing setup first, then choose **Program & guide → Use this four-day plan**. Importing or switching saves a recovery copy, available from the menu. Export a separate backup before moving between devices or replacing an installation.

## What changed

- Four workouts with short leg blocks and six exercises per session.
- An eight-session return phase, with a manual extension or finish option.
- A next-workout recommendation that continues through missed weeks.
- Session templates saved with new logs, preserving historical workout context.
- Clear rep progression prompts and optional last-set effort tracking.
- Completed weekly working sets by estimated muscle group. Blank sets do not count.
- Actual lift records instead of estimated-max percentages from high-rep sets.
- A rest timer and optional protein, sleep and body-weight check-ins.
- More complete backups, import validation and a recovery copy.

Muscle-group totals use exercise-name estimates and exclude indirect work. Custom exercises may appear as Other. Attendance is based on recorded work, so it cannot distinguish an unlogged workout from one that was missed. New rep entries above 60 are flagged for review; older records are preserved.

## Your existing installed app

This package has not replaced or published your current installation. To update that installation, use the same hosting/deployment process as the original static app, retaining the file names in this folder. Keep the backup JSON as a personal file; it is not needed in the publicly hosted app. Do not upload the supplied backup or this personal guide to public hosting.

`index.html`, `sw.js`, `manifest.webmanifest` and the three icon images are the app files to deploy. The app has no build dependencies. Offline installation requires HTTPS (or localhost); opening a local HTML file is a review option rather than an installed offline app.

The app saves to browser storage, without cloud sync. If a browser blocks storage, a notice appears. Export before closing in that situation. Import into the revised app on your intended device before continuing your logs there.

## Validation

JavaScript syntax checks passed. Nineteen automated checks passed, including preservation of all 31 sessions, old-session rendering, workout sequencing, return-phase sets, weekly set counts, backup round trips, active draft preservation, malformed import rejection and rollback after an import storage failure.

Live browser preview was blocked in this environment. Visual layout, real-device storage and offline installation still need a device check. No hosted deployment was performed.
