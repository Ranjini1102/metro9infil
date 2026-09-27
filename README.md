<div align="center">
  <img src="/manus-storage/metro9-present-preview_95b03f15.png" alt="METRO-9 Preview" width="100%" />

  <h1>METRO-9: Infiltration Protocol</h1>
  
  <p>
    <strong>A next-generation third-person 3D infiltration web game across temporal dimensions.</strong>
  </p>

  <p>
    <a href="https://metro9infil.vercel.app"><b>🎮 Play the Live Demo</b></a>
  </p>

  <p>
    <img src="https://img.shields.io/badge/Status-Live-success.svg" alt="Status" />
    <img src="https://img.shields.io/badge/Engine-Babylon.js-EF5B25.svg?logo=babylon.js&logoColor=white" alt="Babylon.js" />
    <img src="https://img.shields.io/badge/Platform-WebGL-990000.svg?logo=webgl&logoColor=white" alt="WebGL" />
    <img src="https://img.shields.io/badge/Deployment-Vercel-000000.svg?logo=vercel&logoColor=white" alt="Vercel" />
    <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License" />
  </p>
</div>

---

## 📖 Table of Contents
- [Overview](#-overview)
- [Key Features](#-key-features)
- [Technical Architecture](#-technical-architecture)
- [Gameplay Mechanics](#-gameplay-mechanics)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Deployment](#-deployment)
- [Contributing](#-contributing)
- [License](#-license)

## 🌌 Overview

**METRO-9: Infiltration Protocol** is an advanced 3D stealth and infiltration game built directly for the browser. Set within a dynamic, living city, players navigate through intricate environments across multiple timelines—Present, Ancient, and Future. Powered by a robust WebGL 3D rendering engine, METRO-9 delivers an immersive, low-latency gaming experience featuring interactive stealth mechanics, intelligent detection systems, and seamless temporal environment switching.

## ✨ Key Features

- **Temporal Dimensional Shifts:** Instantly transition between distinct eras (Present, Ancient, Future) with unique environmental aesthetics and challenges.
- **Advanced Stealth Systems:** Navigate complex vision cones, utilize the disguise system, and monitor dynamic detection meters via the intuitive HUD.
- **High-Fidelity WebGL Rendering:** Leverages state-of-the-art shader techniques including vertex color mixing, realistic fog effects, and optimized 3D asset pipelines.
- **Responsive & Accessible (PWA):** Fully optimized for both desktop and mobile touch devices, featuring a Progressive Web App implementation for native-like performance.
- **Zero-Friction Access:** Delivered as a static bundle requiring no installation—just click and play.

## 🏗 Technical Architecture

The project is engineered for maximum performance and portability:

- **Core Engine:** Babylon.js (WebGL 3D Rendering)
- **UI & HUD Framework:** WebGL/Canvas integrated UI layer
- **Shaders:** Custom GLSL (Fragment/Vertex shaders for environmental effects)
- **Asset Pipeline:** Pre-compiled JS bundles with DDS texture loading & optimized spheremap polynomials.
- **Hosting:** Vercel (Edge network delivery with static routing)

## 🎮 Gameplay Mechanics

- **Infiltration:** Sneak past patrolling entities. Utilize the environment to break line of sight.
- **Detection HUD:** Real-time feedback overlay that tracks your visibility. Once the meter fills, the infiltration protocol fails.
- **Temporal Anomalies:** Certain obstacles can only be bypassed by shifting the timeline, requiring strategic thinking.

## 📁 Project Structure

```text
metro9infil/
├── index.html            # Main HTML entry point & WebGL root container
├── assets/               # Pre-compiled game logic, CSS, and GLSL shaders
│   ├── index-BKsFqddo.js # Primary application & 3D engine bundle
│   ├── index-Bdc3wfIR.css# Game UI & HUD styling
│   └── *.js              # Modular shader fragments & rendering helpers
├── manus-storage/        # High-resolution textures & timeline preview imagery
├── __manus/              # PWA manifest & service worker configurations
├── vercel.json           # Edge deployment & static routing configuration
├── package.json          # Node scripts & dependencies metadata
└── README.md             # Project documentation (You are here)
```

## 🚀 Getting Started

To run the project locally for development or testing, follow these simple steps.

### Prerequisites

- [Node.js](https://nodejs.org/) (v16.x or later recommended)
- `npm` or `yarn` package manager

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Ranjini1102/metro9infil.git
   cd metro9infil
   ```

2. **Launch the local server:**
   ```bash
   npm run start
   ```
   *(This uses `npx serve .` to serve the static files on a local port.)*

3. **Play:**
   Open your browser and navigate to the local server URL (usually `http://localhost:3000`).

## ☁️ Deployment

METRO-9 is pre-configured for seamless deployment on Vercel. 

The inclusion of `vercel.json` ensures that routing and caching headers are properly managed for static assets and the PWA manifest.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FRanjini1102%2Fmetro9infil)

## 🤝 Contributing

We welcome contributions from developers, 3D artists, and game designers! 
1. Fork the repository
2. Create a Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 👨‍💻 Creator

**Ranjini**
- GitHub: [@Ranjini1102](https://github.com/Ranjini1102)

## 📄 License

This project is licensed under the MIT License.

<div align="center">
  <p><i>Developed with passion for WebGL gaming.</i></p>
</div>
