# 🌌 Neon Air Draw — AI Spatial Interface

Neon Air Draw is a real-time, AI-powered web app that lets you draw in mid-air using just your hands. Inspired by futuristic interfaces like *Minority Report*, it turns your gestures into a seamless spatial drawing experience.

Use one hand to draw and the other to control, transform, and interact with your creations—no mouse, no touch, just motion.

---

## ✨ What Makes It Special

**✋ Two-Hand Control, Like Magic**

* **Right Hand**: Draw, erase, or clear the canvas with precision
* **Left Hand**: Move, scale, and rotate your drawings in real time

**📐 Smart, Non-Destructive Editing**
Your strokes never lose their original form. All transformations happen dynamically using matrix calculations, so everything stays flexible and editable.

**🕶️ Clean Glass UI**
A sleek, modern glassmorphism interface with subtle neon accents and real-time visual feedback.

**⚡ Smooth Performance**
Powered by WebGL for fast, fluid interactions—targeting a buttery 60FPS experience.

**🌀 Natural Motion Feel**
Includes inertia while moving objects and snap-to-angle rotation (45°) for better control.

**📖 Built-In Guide**
An interactive gesture manual helps you learn everything quickly.

---

## 🛠️ Tech Stack

* **Frontend**: React + Vite
* **Hand Tracking**: MediaPipe Hands
* **Animations**: Framer Motion
* **Icons**: Lucide React (+ custom SVGs)
* **Styling**: Modern CSS (Glassmorphism + Neon UI)

---

## 🎮 How to Use

### ✍️ Drawing Hand (Right Hand)

| Gesture            | What It Does      |
| ------------------ | ----------------- |
| ☝️ Index Finger Up | Start drawing     |
| 🤏 Pinch           | Erase selectively |
| ✊ Fist             | Clear the canvas  |

### 🖐️ Control Hand (Left Hand)

| Gesture           | Action              | Visual Hint          |
| ----------------- | ------------------- | -------------------- |
| ✌️ Two Fingers    | Move nearest stroke | Blue crosshair       |
| 🤏 Pinch & Spread | Scale object        | Rings + % indicator  |
| 🤚 Open Palm      | Rotate object       | Orange arc with snap |

---

## 🚀 Getting Started

1. Install dependencies

```bash
npm install
```

2. Start the dev server

```bash
npm run dev
```

3. Open the app, allow camera access, and start drawing in the air.

---

## 👨‍💻 Developer

**Sayan Mondal**
📸 LinkedIn: [https://www.linkedin.com/in/sayan-kolkata/](https://www.linkedin.com/in/sayan-kolkata/)
🐙 GitHub: [https://github.com/Sayan2713](https://github.com/Sayan2713)

---

*Built with a passion for AI, creativity, and the future of spatial computing.*
