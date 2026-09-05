# Mirror Doodle

A tiny browser toy for drawing kaleidoscopic, symmetric doodles on an HTML canvas.
Every stroke is mirrored around the center, so a single drag becomes a mandala.

## Run it

No build step, no dependencies. Just open `index.html` in a browser:

```bash
# macOS
open index.html
# Windows
start index.html
# Linux
xdg-open index.html
```

## Controls

| Control | What it does |
| --- | --- |
| **Symmetry** | Number of rotational copies of each stroke (2–24) |
| **Brush** | Stroke width in pixels (1–40) |
| **Hue speed** | How quickly the stroke color cycles as you draw (0 = fixed hue) |
| **Fade** | Slowly fades the canvas over time for a "living" look (0 = off) |
| **Reflect** | Also mirror each stroke, doubling the symmetry |
| **Clear** | Wipe the canvas |
| **Save PNG** | Download the current canvas as a PNG |

Drag anywhere on the canvas to draw. Touch is supported.
