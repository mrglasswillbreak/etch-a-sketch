# Etch-a-Sketch+

A modern, responsive **Etch-a-Sketch web app** built with plain HTML, CSS, and JavaScript.
It supports desktop and touch drawing with multiple brush modes, quick controls, and PNG export.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Screenshots](#screenshots)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Usage Guide](#usage-guide)
- [Project Structure](#project-structure)
- [Roadmap](#roadmap)

## Overview
Etch-a-Sketch+ renders a dynamic grid canvas and lets users draw by dragging the pointer across cells.
The app includes creative drawing modes, brush sizing, and utility actions (clear, toggle grid lines, export PNG).

## Features

### Drawing
- **Grayscale mode** with progressive darkening
- **Solid color mode** with color picker
- **Rainbow mode** for random colors per stroke
- **Eraser mode** for quick cleanup
- **Brush size control** (1–4)

### Canvas Controls
- **Grid size slider** (8–100) + Apply action
- **Clear board** in one click
- **Show/Hide grid lines**
- **Live stats** (`filled / total` cells)
- **Save PNG** export of the current artwork

### UX
- Touch-friendly pointer interactions
- Responsive layout with compact top control bar
- Dark-mode aware UI via `prefers-color-scheme`

## Screenshots

> Note: The screenshots below were captured from the running app in this environment.

### Default Interface
![Etch-a-Sketch default interface](browser:/tmp/codex_browser_invocations/ba858c2b3dc32759/artifacts/shots/default-ui.png)

### Customized Controls State
![Etch-a-Sketch customized controls](browser:/tmp/codex_browser_invocations/19feca4cb762b78e/artifacts/shots/custom-ui.png)

## Tech Stack
- **HTML5**
- **CSS3** (Grid, custom properties, responsive layout)
- **Vanilla JavaScript** (DOM APIs, Pointer Events)

## Getting Started

### Option 1: Open directly
Open `index.html` in your browser.

### Option 2: Run a local server (recommended)
```bash
python3 -m http.server 8000
```
Then open: `http://localhost:8000`

## Usage Guide
1. Adjust **Grid** size and click **Apply**.
2. Choose a drawing **Mode**.
3. (Optional) Pick a color in **Color** mode.
4. Set **Brush** size.
5. Draw on the board using mouse or touch.
6. Use **Clear**, **Hide/Show Grid Lines**, or **Save PNG** as needed.

## Project Structure
```text
.
├── index.html
└── README.md
```

## Roadmap
- Undo / redo history
- Mirror and symmetry drawing
- Fill bucket tool
- Persist sketches with localStorage
