# 🔧 Graphic Stress Test (WebGL)

This project is a **WebGL-based 3D fractal renderer and stress test** designed to push the limits of your GPU in a browser environment. It renders complex ray-marched volumetric shapes using shader code with dynamic lighting and surface calculations.

## 🌀 Demo

The rendering is entirely GPU-accelerated using **GLSL shaders** for both vertex and fragment processing. You can interact with the 3D scene using your mouse or touch gestures to rotate, pan, and zoom.

> 🧪 Try it out by opening `index.html` in any modern browser that supports WebGL.

---

## ✨ Features

- Real-time volumetric rendering via ray marching
- Dynamically animated fractal transformations
- High precision shading and surface normals
- Intuitive interaction: mouse & multi-touch supported
- Pure HTML/CSS/JavaScript + WebGL — no dependencies

---

## 🖱️ Controls

### Mouse / Trackpad
- **Left-click + drag** – Rotate view
- **Right-click + drag** – Pan view
- **Scroll wheel** – Zoom in/out

### Touch
- **1-finger drag** – Rotate view
- **2-finger drag** – Pan view
- **Pinch gesture** – Zoom in/out

---

## 📁 Project Structure


---

## 🧠 How It Works

The main magic happens inside **GLSL fragment shaders** using a ray marching technique to evaluate a custom-defined implicit surface. The kernel function iteratively transforms and evaluates 3D space to generate pseudo-fractal geometry.

Some key techniques used:
- Distance estimation fields
- Normals via central differencing
- Reflection and lighting computations
- Colorization based on depth and reflection vectors

---

## 🖥️ Requirements

- A browser with **WebGL 1.0 support**
  - Chrome, Firefox, Edge, Safari, etc.
- A **GPU with shader support** (most modern devices qualify)

---

## 🚀 Getting Started

Clone or download this repository, then simply open `index.html` in a browser.

```bash
git clone https://github.com/yourusername/graphic-stress-test.git
cd graphic-stress-test
open index.html  # Or use your preferred browser
