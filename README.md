# 🖐️ 3D Particle System - Hand Gesture Control

An interactive 3D particle visualization system that responds to real-time hand gestures using your webcam. Control thousands of animated particles with simple hand movements and gestures.

![Project Demo](https://img.shields.io/badge/Three.js-3D-blue)
![MediaPipe](https://img.shields.io/badge/MediaPipe-Hand%20Tracking-green)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)


## ✨ Features

### 🎨 9 Beautiful Particle Templates
- 🌐 **Sphere** - Classic 3D sphere
- ❤️ **Heart** - Romantic heart shape
- 🌸 **Flower** - Elegant flower pattern
- 🪐 **Saturn** - Planet with rings
- 🎆 **Fireworks** - Explosive burst effect
- 🌀 **Spiral** - Hypnotic spiral
- 🌊 **Wave** - Flowing wave pattern
- 🧬 **DNA** - Double helix structure
- 🌌 **Galaxy** - Spiral galaxy

### 🎨 6 Color Palettes
- Rainbow | Fire | Ocean | Forest | Sunset | Neon

### ✋ Gesture Controls
| Gesture | Action |
|---------|--------|
| 👌 **Pinch** | Scale particles (pinch to zoom in/out) |
| ✊ **Fist** | Cycle through color palettes |
| ✌️ **Peace** | Switch particle templates |
| 🖐️ **Open Hand** | Attract particles to your palm |
| 👍 **Thumbs Up** | Trigger explosion effect |

### ⚙️ Adjustable Settings
- **Particle Count** (500 - 10,000)
- **Particle Size** (1 - 10)
- **Animation Speed** (0.1x - 3x)
- **Hand Influence** (0% - 100%)

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **Three.js** | 3D rendering and particle system |
| **MediaPipe Hands** | Real-time hand tracking and gesture detection |
| **HTML5/CSS3** | UI layout and styling |
| **JavaScript (ES6)** | Core logic and interactivity |

## 📁 Project Structure

├── index.html # Main application file
├── README.md # Project documentation
└── Data Analytics Certificate.png # Certificate (if applicable)

## 🚀 How to Run

### Option 1: Direct Open
1. Download `index.html`
2. Open in a modern browser (Chrome, Edge, Firefox)
3. Allow camera access when prompted
4. Start gesturing!

### Option 2: Local Server
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Then open http://localhost:8000
