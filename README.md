# NEURAL FLOW — Interactive 3D Particle Experience

[![CI Pipeline](https://github.com/jatinrajvanshi94/Neural-Flow/actions/workflows/ci.yml/badge.svg)](https://github.com/jatinrajvanshi94/Neural-Flow/actions/workflows/ci.yml)
[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](https://neural-flow-ten.vercel.app/)

**Neural Flow** is an interactive, immersive 3D particle morphing sandbox driven by real-time webcam input, MediaPipe hand gesture tracking, and coordinates. It features generative Web Audio API synthesis and responsive controls designed for all devices.

## 🚀 Live Production URL
Experience it here: **[https://neural-flow-ten.vercel.app/](https://neural-flow-ten.vercel.app/)**

---

## ✨ Features

- **Interactive 3D Particle Canvas**: Render and morph 3,000+ particles between mathematical structures (Sphere, Cube, Torus, Helix, Galaxy, Heart, Tornado, Infinity).
- **Hand Gesture Tracking**: Powered by MediaPipe Hands, allowing users to rotate, scale, charge, and explode particles with physical hand movements.
- **Generative Audio Synthesis**: Interactive synthesizers driven by particle acceleration, charge cycles, and coordinate manipulation.
- **Responsive HUD Dashboard**: A slide-out hamburger drawer panel on mobile/tablet screens that organizes settings, controls, and instructions into a clean overlay.
- **D-Pad TV Integration**: Large scale parameters and explicit focus indicators optimized for smart TV browsers using TV remote controls.

---

## 🛠️ Getting Started

### Prerequisites
To run validation scripts, ensure you have **Node.js** installed on your system.

### Running Locally
Since this is a static client-side web application, you can run it without any compilation:
1. Clone the repository:
   ```bash
   git clone https://github.com/jatinrajvanshi94/Neural-Flow.git
   ```
2. Open `index.html` directly in any web browser, or launch a local web server:
   ```bash
   npx serve .
   ```

### Code Quality & Validation
Run HTML syntax validation checks:
1. Install dependencies:
   ```bash
   npm install
   ```
2. Run HTML linter:
   ```bash
   npm run lint
   ```

---

## 🛰️ CI/CD Workflow
This repository includes a GitHub Actions workflow (`.github/workflows/ci.yml`) that triggers on every push or pull request to the `main` branch. It executes:
- Node.js installation
- Package dependency restore
- Code validation and syntax checks using `htmlhint`
