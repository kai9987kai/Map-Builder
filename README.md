# Map-Builder (Advanced Creative Canvas)

**Map-Builder** is a lightweight, single-file, browser-first **2D map/canvas editor** concept. The repository currently contains one file (`index.html`) that defines the intended tool surface for drawing, layout, layering, and exporting—aimed at quickly sketching maps/levels/diagrams on a canvas. :contentReference[oaicite:0]{index=0}

---

## Repository contents

- `index.html` — the “Advanced Creative Canvas” UI/spec scaffold. :contentReference[oaicite:1]{index=1}

> At the moment, the repo is effectively a **single-page prototype/spec** (tool list + workflow surface), suitable as a foundation to wire into a real canvas engine. :contentReference[oaicite:2]{index=2}

---

## Feature surface (as specified)

### Drawing / editing tools
The UI surface includes the following tools: :contentReference[oaicite:3]{index=3}

- ✏️ **Free Draw**
- 🗺️ **Contour Maker**
- ▭ **Rectangle**
- ⚪ **Circle**
- ➖ **Line**
- 📏 **Ruler**
- 🛣️ **Road Pen**
- ⬛ **Corner Pen**
- ✋ **Move**
- 🔲 **Select**
- ↕️ **Resize**
- 🔄 **Rotate**
- 🧽 **Eraser**
- 🔤 **Text**

### Align tools
- ⬅️ Align Left
- ➡️ Align Center
- ⬆️ Align Right
- Align Top / Middle / Bottom :contentReference[oaicite:4]{index=4}

### Styling controls
- **Stroke color**
- **Fill color**
- **Background color**
- **Stroke width** :contentReference[oaicite:5]{index=5}

### Labels
- Add label + label color, with an “➕ Add Label” action. :contentReference[oaicite:6]{index=6}

### Canvas utilities
- Toggle grid
- Undo / Redo
- Clear canvas
- Export as PNG
- Save canvas
- Load canvas :contentReference[oaicite:7]{index=7}

### Layers
- A layers section is present, implying multi-layer editing/stacking. :contentReference[oaicite:8]{index=8}

### “What’s New” notes (in the file)
The file also advertises:
- Save/load via **local storage**
- Improved draggable handles for rotate/resize
- A **“What’s New” popup** feature :contentReference[oaicite:9]{index=9}

---

## Quick start

### Option A — open directly
1. Clone:
   ```bash
   git clone https://github.com/kai9987kai/Map-Builder.git
   cd Map-Builder
