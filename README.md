# METRO-9: Infiltration Protocol

![METRO-9 Preview](/manus-storage/metro9-present-preview_95b03f15.png)

**METRO-9: Infiltration Protocol** is a third-person 3D infiltration web game set in a living city across multiple timeline environments. Powered by WebGL 3D rendering (Babylon.js / React), this application features interactive stealth mechanics, dynamic detection meters, HUD overlays, and temporal environment switches.

---

## 🚀 Live Demo

- **Production URL**: [https://metro9infil.vercel.app](https://metro9infil.vercel.app)

---

## ✨ Features

- **Interactive 3D Environments**: Explore distinct time periods (Present, Ancient, Future).
- **Stealth & Infiltration Mechanics**: Disguise system, vision cones, detection panels, and dynamic state tracking.
- **Rich Audio & Visual FX**: Shader-based vertex color mixing, fog effects, and responsive WebGL rendering.
- **PWA & Mobile Ready**: Responsive layout optimized for desktop and touch devices.
- **Fast Static Hosting**: Pre-built static bundles ready for immediate deployment on Vercel or GitHub Pages.

---

## 📁 Project Structure

```text
metro9infil/
├── index.html            # Main HTML entry point & WebGL root container
├── assets/               # JavaScript bundles, CSS stylesheets & shader chunks
│   ├── index-BKsFqddo.js # Primary application & 3D engine bundle
│   ├── index-Bdc3wfIR.css # Game UI & HUD styling
│   └── ...               # Modular GLSL shader fragments & helpers
├── manus-storage/        # High-resolution textures & timeline environment previews
├── vercel.json           # Vercel deployment & static routing configuration
├── package.json          # Node scripts & dependencies metadata
└── README.md             # Project documentation
