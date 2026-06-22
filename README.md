# ✊🖐✌ Rock Paper Scissors — Finger Edition

A real-time **hand gesture-controlled Rock Paper Scissors game** built with **Python, OpenCV, and MediaPipe**. No mouse, no keyboard — your hand is the controller.

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue?logo=python">
  <img src="https://img.shields.io/badge/OpenCV-4.x-green?logo=opencv">
  <img src="https://img.shields.io/badge/MediaPipe-Hand%20Tracking-orange">
  <img src="https://img.shields.io/badge/License-MIT-lightgrey">
</p>

---

## 🎮 Demo

<p align="center">
  <img src="assets/demo.gif" width="750">
</p>

> Point your index finger to navigate menus and use hand gestures to play against the CPU.

---

## ✨ Features

### 🖐 Gesture-Based Controls

* No mouse or keyboard required
* Hover your fingertip over buttons to select
* Hold for ~1 second to confirm actions

### 👋 Real-Time Hand Tracking

* Powered by MediaPipe landmarks
* Live hand skeleton visualization
* Smooth fingertip cursor tracking

### ✊✋✌ Sign Recognition

Automatically detects:

| Gesture | Sign     |
| ------- | -------- |
| ✊       | Rock     |
| 🖐      | Paper    |
| ✌       | Scissors |

### 🎯 Gameplay Features

* Select target score: **3, 5, 7, or 10**
* Automatic round progression
* Round counter and score bars
* CPU opponent
* Countdown timer before reveal

### 🎨 Visual Effects

* Neon fingertip cursor trail
* Particle effects on win, loss and tie
* Animated sign drawings
* Smooth transitions and HUD

### 🔄 Match System

* Rematch option
* Return to menu without restarting
* Single script, no external assets required

---

## 🧠 How It Works

1. Start the webcam.
2. Select the target score.
3. Show Rock, Paper or Scissors.
4. Hold the gesture until it is locked.
5. Countdown begins.
6. Round result is displayed.
7. Next round starts automatically.
8. Play until one side reaches the target score.

---

## 📂 Project Structure

```text
rps-finger-edition/
│
├── rps.py
├── README.md
├── requirements.txt
├── LICENSE
└── assets/
    ├── demo.gif
    ├── menu.png
    ├── gameplay.png
    ├── result.png
    └── gameover.png
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

Press **Q** at any time to quit.

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

Install manually:

```bash
pip install opencv-python mediapipe numpy
```

---

## 🖼 Gesture Reference

| Gesture | Sign     | Description                       |
| ------- | -------- | --------------------------------- |
| ✊       | Rock     | Closed fist                       |
| 🖐      | Paper    | Open hand                         |
| ✌       | Scissors | Index and middle fingers extended |

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

## 📸 Screenshots

### Main Menu

<p align="center">
  <img src="assets/menu.png" width="750">
</p>

### Gameplay

<p align="center">
  <img src="assets/gameplay.png" width="750">
</p>

### Round Result Screen

<p align="center">
  <img src="assets/result.png" width="750">
</p>

### Match Over Screen

<p align="center">
  <img src="assets/gameover.png" width="750">
</p>

---

## 🚀 Future Improvements

* [ ] Sound effects
* [ ] Two-player mode
* [ ] Difficulty levels
* [ ] Match history
* [ ] Leaderboard
* [ ] Custom themes

---

## 🛠 Built With

* Python
* OpenCV
* MediaPipe
* NumPy

---

## 👨‍💻 Author

<p align="center">

### **Kanak Tiwari**

Final Year B.Tech Student • Python Developer • Computer Vision Enthusiast

<a href="https://github.com/YOUR_USERNAME">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github">
</a>

<a href="https://linkedin.com/in/YOUR_LINKEDIN_USERNAME">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin">
</a>

<a href="mailto:your-email@example.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail">
</a>

</p>

---

## 📜 License

This project is licensed under the MIT License.

---

## ⭐ Support

If you found this project useful, consider giving it a **star ⭐** on GitHub.

---

<p align="center">
Made with ❤️ by <b>Kanak Tiwari</b>
</p>
