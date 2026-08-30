# 4K Visual Design

A high-resolution WebGL generative art experience that renders an animated 40 million-cell procedural pattern in real time.

## Overview

This project displays a fullscreen, continuously evolving visual generated entirely on the GPU using WebGL shaders.  
The animation blends value noise, fractal Brownian motion (fBM), and domain warping to create smooth organic motion with a non-repeating flow.

## Features

- Real-time WebGL rendering pipeline
- High-resolution simulation grid (`8000 x 5000`)
- Procedural shader-based animation (no image assets)
- Adaptive animation speed for `prefers-reduced-motion`
- Graceful fallback message when WebGL is unavailable

## Tech Stack

- HTML5
- JavaScript (vanilla)
- WebGL (GLSL shaders)

## Getting Started

No build step is required.

1. Clone the repository.
2. Open `index.html` in a modern browser with WebGL support.

For best results, run through a local static server:

```bash
python -m http.server 8080
```

Then visit `http://localhost:8080`.

## Project Structure

- `index.html` — complete application including styles, WebGL setup, shaders, and animation loop.

## Browser Requirements

- A modern browser with WebGL enabled
- GPU acceleration for smooth rendering

## License

This project is available under the MIT License. Add a `LICENSE` file if you want to formalize distribution terms.
