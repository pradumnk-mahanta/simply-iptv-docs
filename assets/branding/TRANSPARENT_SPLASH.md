# Transparent splash/setup logo

Created with the built-in image-generation tool. Source: app/src/main/res/drawable-nodpi/splash_logo.png from the approved logo. Only the surrounding background is removed; the badge interior remains opaque for text contrast. The source master preserves alpha; Export-BrandAssets.ps1 resizes it to 1024x1024 RGBA.

## Background removal

```
Use case: background-extraction.
Edit target: the attached Simply IPTV splash logo PNG.
Make only one change: remove the entire outside background beyond the cyan rounded rectangle, leaving genuine transparent alpha there. Remove every part of the surrounding square navy canvas, vignette and exterior glow so the rounded badge is a clean cutout that can sit on either an off-white or a black page.
Preserve exactly the original logo: the cyan rounded rectangle outline, the navy fill INSIDE that rounded rectangle, the white Simply lettering, the bold white IP and cyan TV, letter shapes, alignment, proportions and colors. Do not retype, redesign, recolor, move, enlarge, crop, or add anything.
IMPORTANT: keep the inside navy panel fully opaque; only the outside of the badge becomes transparent. The white letters must remain white. Use a crisp antialiased cutout edge following the outside edge of the cyan border, with no dark rectangular matte, no checkerboard painted into the image, no white halo, and no outer shadow.
Maintain the square canvas and the logo's same centered position and size with transparent padding, preferably 1024x1024. Output PNG with true alpha transparency.
```

## Edge cleanup

```
Edit this transparent Simply IPTV badge. Change ONLY the rough cutout boundary: remove the scattered cyan/blue/purple specks and ragged fringe outside the rounded rectangle. The outer contour must be a perfectly smooth antialiased rounded rectangle ending exactly at the bright cyan border, with clean transparent pixels immediately outside it. NO glow, NO shadow, NO halo, NO stray colored pixels. Keep genuine alpha transparency outside. Keep the navy interior opaque.
Preserve the existing wordmark pixels, lettering, colors, size, center position, cyan border thickness and rounded corner geometry. Do not change the letters or redraw the logo. Preserve the existing square transparent canvas. This is an edge-cleanup pass for a production splash/setup logo displayed on an off-white page.
```

