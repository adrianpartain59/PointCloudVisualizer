# Point Cloud Visualizer

An interactive browser-based point cloud visualizer for generating abstract wave, landscape, and cloth-like point cloud images.

The project is a single static `index.html` file, so it can run locally in a browser or be hosted directly with GitHub Pages.

## Features

- Procedural point cloud wave surface
- Adjustable density, wave shape, brightness, point size, camera, color, seed, and animation settings
- Built-in presets for different looks
- Desktop and mobile portrait crop modes
- PNG export with high-resolution options up to 8x
- Keyboard shortcuts:
  - `H` hides or shows the control panel
  - `S` exports a PNG
  - `Space` toggles animation playback

## Run Locally

Open `index.html` directly in a browser.

You can also serve the folder locally:

```sh
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Exporting Images

Use the **Export PNG** button, or press `S`.

The export resolution defaults to **Ultra Quality (8x, slower)**. If Mobile mode is selected, exports use the same portrait crop shown in the preview.

## GitHub Pages

This project can be deployed as a static GitHub Pages site:

1. Open the repository settings on GitHub.
2. Go to **Pages**.
3. Set **Source** to **Deploy from a branch**.
4. Set **Branch** to `main` and folder to `/ (root)`.
5. Save the settings.

The site will be published at:

```text
https://adrianpartain59.github.io/PointCloudVisualizer/
```
