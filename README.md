# Save the Dodo

*You can't control him. You can only try.*

A run-based survival comedy. Nudge a magnificently stupid dodo around an island, collect shinies for his
nest, and get him home by sunset. Something enormous is hungry. Several somethings are asleep.

**Play:** open the GitHub Pages link on your phone, then add it to your home screen
(iPhone: Share → Add to Home Screen · Android: ⋮ → Install app). It works offline after the first load.

## Controls
- **Phone:** drag anywhere to nudge him · two fingers to spin/zoom the camera · HUSH (hold) · HONK! (tap) · compass = follow camera
- **Keyboard:** WASD nudge · Space hush/hide · Shift honk · drag mouse / Q E spin · scroll zoom · C follow camera · P pause · M mute · T tuning rack

## Files
- `index.html` — the whole game (three.js r128, procedural audio, no external assets)
- `three.min.js` — the 3D library, bundled so it works offline
- `manifest.webmanifest`, `sw.js`, `icon-*.png` — what makes it installable

When you publish a new version, change `VERSION` at the top of `sw.js` (e.g. `dodo-v7`) so phones fetch the update.
