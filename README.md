# CIRLXIII // SPLASH (ASCII Edition)

A standalone, offline, monochrome, ASCII-art falling-block puzzle with cross-shaped water-bomb explosions and chain reactions.

## Play

Open `index.html` in a modern desktop browser (Safari, Chrome, Firefox, or Edge). Mobile browsers are supported through the touch controls below the game board. You can also publish `index.html` at the repository root using GitHub Pages (`Settings > Pages > Deploy from a branch > main > /(root)`).

No internet connection, external assets, installation, or JavaScript build tools are required after downloading.

## Rules

- 12 x 20 board; two block types, light `[]` and dark `##`.
- All 63 nonempty 2 x 3 shapes are dealt once per 63-piece cycle, starting with the larger shapes. Each falling shape is one gray shade.
- Match a solid 3 x 3 area of one shade to clear it and generate a short cross-shaped splash.
- Every third piece carries a water bomb, depicted as `()` or `{}`. Its fuse expires after two subsequent pieces lock. Bombs splash three cells in all four directions; hitting another bomb triggers it immediately.
- Gravity applies after a wave. Any new 3 x 3 areas can trigger further waves and raise the chain multiplier.
- Hold a piece to set up combinations. You can hold only once per falling piece.

## Controls

| Key | Action |
| --- | --- |
| Left / A | Move left |
| Right / D | Move right |
| Down / S | Soft drop |
| Enter / Up | Rotate clockwise |
| Space | Drop instantly |
| H / C | Hold / swap piece |
| P | Pause or resume |
| R | Restart |
| M | Toggle sound |

On phones, tap the six buttons under the board or gesture on the board (tap to rotate, sideways swipes to move, long down-swipe to drop, upward swipe to hold). Holding the left, right, or down buttons repeats the action.

## Developer checks

Visit `index.html?test=1` to execute 12 deterministic checks, including 2,000 randomized board scenarios, in the browser. A `PASS` message should appear at the bottom of the page.

## Source rights

No third-party images, music, or fonts are included. No license file has been added; select and add an appropriate license before publishing the code as open source.
