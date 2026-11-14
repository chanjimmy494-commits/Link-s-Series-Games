# Link's Adventure — Ancient Outpost: deployment and mobile layout

## Required gameplay build
The illustrated Ancient Outpost gameplay build consists of index.html, stage_backdrop.jpg, floor.jpg, and the complete sprites/ directory (the supplied dual-orientation ZIP). These files must be uploaded together into the same GitHub Pages game directory. Do not substitute the legacy procedural prototype or borrow any Link's Melee artwork.

## Mobile orientations
- Portrait: show the complete 16:9 game canvas near the top of the screen; place the directional pad and action buttons **below** the canvas, without covering the gameplay. Do not show a rotation blocker.
- Landscape: show the 16:9 game canvas fitted to the available screen; overlay the directional pad in the bottom-left and three action buttons in the bottom-right.
- Preserve safe-area insets and disable text selection, browser long-press menus, and accidental gesture zoom over the controls.
- D-pad: up = interact, down = crouch, left/right = move. Sliding thumb changes direction.
- Action buttons left to right: attack (tap normal, hold heavy), shield block, jump. Action buttons have approximately 1.5x standard height and sufficient horizontal spacing.
- Both orientations are supported; landscape is **optional**, never mandatory.

## Asset requirements
- Swordsman: original blue-tunic, dirty-blond-haired artwork and supplied animation frames.
- Enemies: distinct reptilian melee warrior, armored brute, goblin archer, each with separate animated frames.
- Stage: dedicated illustrated Ancient Outpost environment.
- Never reuse Link's Melee characters or backdrop.

## Release verification
Verify asset requests return 200, animations advance, shield blocking is visually distinct, touchscreen controls work simultaneously, and both orientations remain playable before declaring a GitHub Pages release complete.
