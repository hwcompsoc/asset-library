# HW CompSoc asset library

Starter library - 29 October 2026.

## Choose an asset

- Blue: light backgrounds. White: dark backgrounds. Both retain a cyan detail.
- Black and white-mono: single-colour applications.
- Logos: complete HW CompSoc lockup. Icons: cursor extracted from the supplied artwork.
- SVG: scalable vector paths, with outlined lettering and no external fonts.
- PNG: transparent exports except the explicitly named background versions; the number in each filename is its width in pixels.
- logos/background/: full square compositions with solid backgrounds, in SVG and PNG.
- palette/: HEX/RGB JSON, CSS variables and a swatch sheet.
- guide/: one-page PDF usage guide.

The transparent assets are cropped around the artwork with a small edge allowance. Add the clear space described in the guide when placing them.

## Brand decisions

The primary and accent colours are sampled from the supplied artwork. The dark background is standardised to primary blue #004066 at the user's request. All colour variants use the same accent cyan #00A1CC. All new variants share the light-logo vector geometry for consistency. The original font has not been identified; use the outlined artwork without retyping the logo. Clear-space and minimum-size rules are starter guidance, not pre-existing official rules. CMYK values are not supplied because accurate print conversion depends on the printer's colour profile.

Open index.html for a visual catalogue.

## Original background colours

The supplied dark PNG has a slightly textured background; its median and most common background RGB is (1, 68, 115), or #014473. The new full-background dark SVG and PNGs instead use #004066 to match the light logo lettering, as requested. The palette, previews and guide use this standardised background colour. The light source has a white background.

## Additional formats

- PDF: vector copies of every logo and cursor variant, with outlined shapes and no embedded raster images. White artwork has no background and is intended for placement on dark surfaces. The full-background PDFs include their solid background. Colours remain RGB; use a printer-specific conversion if CMYK is required.
- JPEG: full-background logos at 1024 and 2048 pixels wide, saved at high quality. JPEG does not support transparency.
- ICO: square, transparent cursor icons containing 16, 24, 32, 48, 64, 128 and 256 pixel sizes. favicon.ico uses the blue cursor; white variants are intended for dark surfaces. Check the smallest sizes in your browser.

## Pointer cursor

The pointing-hand cursor uses the original arrow cursor as its design base, retaining the stepped outline and cyan detail. Find it alongside the arrow assets as `pointer-{colour}`.

- Colours: blue and white with cyan accents; black and white-mono in a single colour.
- SVG: transparent vector artwork at the original 160 x 207 proportions.
- PNG: transparent exports at 64, 128, 256 and 512 pixels wide, preserving the artwork proportions.
- PDF: transparent vector copies in RGB, with no embedded raster artwork.
- ICO: square transparent icons containing 16, 24, 32, 48, 64, 128 and 256 pixel sizes, with the hand centred and its proportions preserved.

The catalogue includes previews and links to every pointer variant and PNG size.
