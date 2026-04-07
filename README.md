# Design My Tee 

A fully interactive single-file HTML t-shirt customizer. Upload logos, change colors, position graphics, rotate 3D preview, and export PNGs.


##  Features

-  **12 preset colors + custom HEX picker**
-  **Drag-drop logo upload** (PNG/JPG/SVG)
-  **4 positions**: Chest, Center, Left Chest, Back
-  **5 sizes**: XS-XL
-  **3D rotatable preview** (drag/rotate, front/back flip)
-  **Mobile/touch support**
-  **PNG export** (high-res)
-  **Fully responsive**
-  **No build** - single HTML file

##  Quick Start

1. Open `design-my-tee.html` in any browser
2. Pick a **color** from swatches or use custom picker
3. **Drag-drop** a logo onto the shirt or preview
4. Adjust **position** and **size** in tabs
5. **Rotate** preview with mouse/touch
6. **Download PNG** when ready

```bash
# Windows
start design-my-tee.html

```

##  How It Works

- **SVG rendering**: Dynamic shirt + logo with gradients/shadows
- **Canvas export**: SVG → PNG conversion
- **Vanilla JS/CSS**: No frameworks, ~800 LOC
- **Responsive**: Grid/flexbox layout
