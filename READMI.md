# 🎮 Voxel Architect

**Voxel Architect** is a real-time, gesture-controlled 3D voxel modeling web application.  
It allows users to create, edit, and manipulate 3D voxel structures using **hand gestures** captured through a webcam.

The system uses **MediaPipe Hands** for hand tracking and **Three.js** for rendering interactive 3D graphics.

---

## 🚀 Features

- ✋ Real-time hand gesture detection using webcam
- 🧱 Build 3D voxels using pinch gesture
- 🎨 Change voxel colors using hand signs
- 🌈 Disco / Rainbow lighting mode
- 🌍 Gravity burst & restore effect
- 🔄 Grab, move, rotate the entire structure
- ♻️ Reset system using dual-hand gesture
- 🖥️ Cyber-style HUD with live system state

---

## 🛠️ Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript**
- **Three.js** (3D Rendering)
- **MediaPipe Hands** (Hand Gesture Detection)
- **WebGL**
- **Web Camera API**

---

## 🧠 How It Works

1. The webcam captures live video input.
2. MediaPipe Hands detects hand landmarks in real time.
3. Gestures are recognized based on finger positions.
4. Recognized gestures trigger actions like:
   - Building voxels
   - Erasing voxels
   - Applying gravity
   - Changing colors
5. Three.js renders the voxel world dynamically.

---

## ✋ Supported Gestures

### Left Hand

 ✌️ Peace Sign → Change voxel color
 👍 Thumb Up → Restore structure
 👎 Thumb Down → Activate gravity
 ✊ Fist → Grab and move structure

### Right Hand

 🤏 Pinch → Build voxels
 ✌️ Peace Sign → Disco / Rainbow mode
 ✋ Open Palm → Stop action

### Both Hands

 ✊✊ Two Fists (Hold) → Reset system
 ✋✋ Two Palms (Hold) → Rotate structure

---

## ▶️ How to Run the Project

> ⚠️ Camera access requires HTTP server (do not open file directly)

### Method 1: Using VS Code

1. Open the project folder in VS Code
2. Install **Live Server** extension
3. Right-click `index.html`
4. Select **Open with Live Server**
5. Allow camera access in browser

### Method 2: Using Python

---
bash
python -m http.server 8000

---

Open:

---
 http://localhost8000

---

---

## 📂 Project Structure

---
Voxel-Architect/
│
├── index.html
└── README.md

---

---

## 🎓 Academic Use

This project is suitable for:

 Mini Project
 Final Year Project (with extensions)
 Computer Vision Demonstration
 Human–Computer Interaction (HCI)

---

## 🧪 Future Enhancements

 Undo / Redo support
 Save & Load voxel structures
 Multi-layer (Z-axis) building
 Voice commands
 VR / AR integration

---

## 👨‍💻 Author

Developed by **[NASRIN]**
MASTER OF COMPUTER APPLICATION

---

## 📜 License

This project is for educational purposes only.
