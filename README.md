# Save the Dodo

*You can't control him. You can only try.*

A run-based survival comedy. The last two dodos on Earth: a magnificently stupid dodo and Doda, sitting on the last egg.
Keep her on the egg with shinies, feed them both, stay out of the T-rex's sight, and get both of them into the nest by sunset.
Survive three days and the egg hatches.

**Play:** open the GitHub Pages link on your phone, then add it to your home screen
(iPhone: Share → Add to Home Screen · Android: ⋮ → Install app). It works offline after the first load.

## Controls
- **Phone:** drag anywhere to steer him · two fingers to spin/zoom the camera · HUSH (hold) · HONK! (tap) · JUMP (tap) · compass = re-center & follow · ❚❚ (top-right) = pause menu with settings
- **Keyboard:** WASD / arrows steer · Space hush/hide · Shift honk · F jump · drag mouse / Q E spin · scroll zoom · C follow camera · Esc or P pause menu · M mute · T tuning rack
- **Settings** (main menu or pause menu): master / music / sound effects / ambience volume, follow camera, tips on/off

## Files
- `index.html` — the whole game (three.js r128, procedural audio, no external assets)
- `three.min.js` — the 3D library, bundled so it works offline
- `manifest.webmanifest`, `sw.js`, `icon-*.png` — what makes it installable

When you publish a new version, change `VERSION` at the top of `sw.js` (e.g. `dodo-v7`) so phones fetch the update.
