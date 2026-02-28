# 🎨 Etch-a-Sketch+

An upgraded, responsive Etch-a-Sketch built with **HTML, CSS Grid, and vanilla JavaScript**.

## ✨ What's New

- Interactive top control panel (desktop + touch friendly)
- Adjustable grid size slider (8–100)
- Multiple drawing modes:
  - Grayscale darkening
  - Solid color (with color picker)
  - Rainbow random colors
  - Eraser
- Brush size control (1–4)
- Clear board action
- Grid line visibility toggle
- Export current drawing as a PNG image
- Live board stats (`filled` / `total` cells)
- Dark mode-friendly UI using `prefers-color-scheme`

## 🚀 Run Locally

Open `index.html` directly in your browser, or serve with a simple server:

```bash
python3 -m http.server 8000
```

Then visit: `http://localhost:8000`

## 🛠️ Stack

- HTML5
- CSS3 (Grid + modern UI styling)
- JavaScript (DOM APIs + Pointer Events)

## 📌 Next Ideas

- Undo/redo history
- Symmetry/mirror drawing mode
- Fill bucket tool
- Save/load from localStorage
