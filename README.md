# Pixel Art Maker

A simple pixel art editor developed purely with HTML, CSS, and JavaScript.

## Features

- **Pen tool** — Click and drag to draw pixels in any color
- **Eraser tool** — Erase pixels back to white
- **Fill tool** — Flood fill contiguous regions with a single click
- **Color palette** — 16 preset colors + a custom color picker
- **Grid sizes** — Switch between 16x16, 32x32, and 64x64 grids
- **PNG export** — Download your pixel art as a clean PNG (no grid lines)
- **Hover preview** — Semi-transparent preview of the current color on hover

## How it works

The application consists of three core technologies:

- **HTML** (`index.html`) — Provides the structure: a toolbar for tools/colors/grid size, a canvas for drawing, and an export button.
- **CSS** (`style.css`) — Styles the interface, including the toolbar, buttons, color picker, and canvas container.
- **JavaScript** (`script.js`) — Handles all the logic:
  - Tool selection (pen, eraser, fill)
  - Color selection from the palette or custom picker
  - Grid size changes and canvas resizing
  - Drawing on the canvas with mouse events
  - Implementing the fill algorithm (flood fill)
  - Exporting the canvas as a PNG image

## Getting started

Simply open `index.html` in any modern web browser to start creating pixel art. No build steps or dependencies required.

Feel free to modify the colors in the palette, adjust the grid size options, or extend the tools by editing the respective files.
Enjoy creating your pixel art!