# ✊🖐✌ Rock Paper Scissors — Finger Edition

A real-time **hand gesture-controlled Rock Paper Scissors game** built with **Python, OpenCV, and MediaPipe**. Play without touching your keyboard or mouse — your hand is the controller.

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue?logo=python">
  <img src="https://img.shields.io/badge/OpenCV-4.x-green?logo=opencv">
  <img src="https://img.shields.io/badge/MediaPipe-Hand%20Tracking-orange">
  <img src="https://img.shields.io/badge/License-MIT-lightgrey">
</p>

---

## 🎮 Demo

<p align="center">
  <img src="assets/demo.gif" width="700">
</p>

> Point your index finger to navigate menus and use gestures to play against the CPU.

---

## ✨ Features

### 🖐 Gesture-Based Controls

* No mouse or keyboard required
* Hover your fingertip over buttons to select
* One-second hold confirmation system

### 👋 Real-Time Hand Tracking

* Powered by MediaPipe landmarks
* Live hand skeleton visualization
* Smooth fingertip cursor tracking

### ✊✋✌ Sign Detection

Recognizes:

| Gesture | Sign     |
| ------- | -------- |
| ✊       | Rock     |
| 🖐      | Paper    |
| ✌       | Scissors |

### 🎯 Gameplay Features

* Choose target score: **3, 5, 7, or 10**
* Automatic round progression
* Round counter and score HUD
* Animated countdown before reveal
* CPU opponent with random moves

### 🎨 Visual Effects

* Neon fingertip cursor trail
* Particle effects on win/loss/tie
* Animated player and CPU signs
* Progress bars and smooth transitions

### 🔄 Match System

* Rematch option
* Return to menu without restarting
* Fully self-contained script

---

## 🧠 How It Works

1. Start the webcam.
2. Select the match score using your fingertip.
3. Show Rock, Paper, or Scissors.
4. Hold your gesture until it's locked.
5. Countdown begins.
6. Winner is announced.
7. Next round starts automatically.

---

## 📂 Project Structure

```text
rps-finger-edition/
│
├── rps.py             # Main game script
├── README.md
├── requirements.txt
├── LICENSE
└── assets/
    ├── gameplay.png
    └── demo.gif
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/rps-finger-edition.git
cd rps-finger-edition
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the game:

```bash
python rps.py
```

Press **Q** to quit anytime.

---

## 📦 Requirements

* Python 3.8+
* Webcam

### Dependencies

```txt
opencv-python
mediapipe
numpy
```

Install:

```bash
pip install opencv-python mediapipe numpy
```

---

## 🖼 Gesture Reference

| Gesture | Sign     | Description                      |
| ------- | -------- | -------------------------------- |
| ✊       | Rock     | Closed fist                      |
| 🖐      | Paper    | Open hand                        |
| ✌       | Scissors | Index and middle finger extended |

---

## 🔄 Game Flow

```text
SELECT
   ↓
WAIT
   ↓
COUNTDOWN
   ↓
RESULT
   ↓
NEXT ROUND
   ↓
GAME OVER
   ↓
REMATCH / MENU
```

---

## 🚀 Future Improvements

* [ ] Sound effects
* [ ] Two-player mode
* [ ] Difficulty levels
* [ ] Match history tracking
* [ ] Leaderboard system
* [ ] Custom themes

---

## 🛠 Built With

* Python
* OpenCV
* MediaPipe
* NumPy

---

## 📜 License

This project is licensed under the MIT License.

---

## ⭐ Support

If you found this project interesting, please consider giving it a **star ⭐**.

---

<p align="center">
Built with ❤️ using Python and Computer Vision
</p>
