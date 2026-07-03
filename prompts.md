## Schwarzschild Black Hole Simulator

Build a real-time, interactive 3D black hole simulator as a single
self-contained HTML file (vanilla JavaScript + WebGL, no libraries, no
build step, no external assets).

Requirements:
- Trace light rays so the starfield background is gravitationally lensed
  and the glowing accretion disk wraps over and under the black hole's
  shadow.
- Click-drag to orbit the camera, scroll to zoom.
- Keep it smooth (~60fps) in a browser; prioritize physical correctness.

Return only the complete HTML file.

## Kerr Black Hole Simulator

Build a real-time, interactive 3D simulator of a SPINNING (Kerr) black
hole as a single self-contained HTML file (vanilla JavaScript + WebGL, no
libraries, no build step, no external assets).

Requirements:
- Trace light rays through curved spacetime so the starfield background is
  gravitationally lensed and the glowing accretion disk wraps over and
  under the black hole's shadow.
- Model black-hole spin with frame-dragging, and expose a control to vary
  the spin from 0 (non-rotating) up to near-maximal. The shadow should
  become asymmetric and the inner disk edge should move as spin changes.
- Include relativistic effects on the disk: Doppler beaming (one side
  noticeably brighter) and gravitational redshift.
- Click-drag to orbit the camera, scroll to zoom.
- Keep it smooth (~60fps) in a browser; prioritize physical correctness.

Return only the complete HTML file.
