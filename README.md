# 🤖 J.A.R.V.I.S — Neural Interface System

J.A.R.V.I.S (Just A Rather Very Intelligent System) is a futuristic, browser-based neural interface simulation inspired by sci-fi HUDs and intelligent assistant systems.  
It runs entirely in the browser and combines 3D visuals, gesture control, instrument clusters, audio feedback, and autonomous behavior.

Live Website:
https://Anish-Kushwaha.github.io/JARVIS

---

## ✨ Features

### 🧠 Core Interface
- Futuristic HUD (Heads-Up Display)
- Boot-up animation with system initialization
- Animated creator name display
- Scanlines, grid floor, radar, reticle, and live data stream
- Responsive and mobile-friendly layout

### 🌌 3D Visualization
- Real-time 3D particle system using Three.js
- Smooth motion physics and interpolation
- Multiple system modes:
  - ATTRACT – particles follow gesture focus
  - SHOCKWAVE – explosive particle repulsion
  - IDLE – ambient autonomous motion

### 🖐️ Gesture Control
- Hand tracking powered by MediaPipe Hands
- Index finger tracking mapped into 3D space
- Reticle follows real-world hand movement
- Camera initializes only after user interaction (browser-safe)

### 📊 Instrument Clusters (HUD / Avionics)
- Energy core rings
- Reactor load meters
- Oscilloscope / signal waveform
- Compass and heading indicator
- Telemetry (ALT, SPD, TEMP, PWR)
- System load histogram
- Threat / mode indicator
- Mode-reactive colors and animations

### 🔊 Audio & Voice System
- Boot startup tone
- Button click and mode switch beeps
- Ambient futuristic hum
- Shockwave / combat pulse sounds
- Threat alert siren
- Text-to-speech system voice:
  - Mode announcements
  - Status updates
  - Threat warnings
- Implemented using Web Audio API and Web Speech API

### 🤖 Autonomous Behavior
- Periodic system voice messages
- Idle monitoring announcements
- Dynamic HUD glow and pulse effects
- Mode-dependent animation speed and color changes

### ⚠️ Threat Detection
- Detects excessive tapping or suspicious interaction
- Activates alert state with:
  - Visual warning overlay
  - Siren sound
  - Voice alert
- Fully browser-safe (no back-button exploits)

---

## 🛠️ Tech Stack

- HTML5
- CSS3 (HUD styling, animations, responsive design)
- JavaScript (ES6)
- Three.js – 3D rendering
- MediaPipe Hands – gesture tracking
- Web Audio API – sound synthesis
- Web Speech API – voice output

---

## 🚀 Usage

### Online
Open directly in a browser:
https://Anish-Kushwaha.github.io/JARVIS

### Local
1. Clone the repository:
   git clone https://github.com/Anish-Kushwaha/JARVIS.git

2. Open index.html in a modern browser (Chrome recommended)

3. Click INITIALIZE once to enable audio and camera

Note: Browsers require user interaction before allowing sound and camera access.

---

## 🎮 Controls

- INITIALIZE
  Enables camera, audio, and gesture tracking

- Mode Selector
  ATTRACT
  SHOCKWAVE
  IDLE

- Hand Movement
  Index finger controls particle focus

- Tap / Click
  Excessive tapping triggers threat detection

---

## 📱 Mobile Support

- Auto-scaling HUD
- Intelligent hiding of non-essential panels
- Touch-friendly controls
- Optimized performance for mobile browsers

---

## ⚖️ License

This project is licensed under the GNU General Public License v3.0 (GPL-3.0).

You are free to:
- Use
- Study
- Modify
- Share

Under the following conditions:
- Derivative works must also use GPL-3.0
- Source code must be disclosed
- Proper credit must be given

Full license text:
https://www.gnu.org/licenses/gpl-3.0.en.html

---

## © Copyright & Legal Restriction

Copyright © 2025 Anish Kushwaha

Legal Notice:
- This project, including its source code, UI design, visual systems, and logic, is the intellectual property of Anish Kushwaha.
- Commercial use, rebranding, or redistribution without attribution is strictly prohibited.
- Any forks or derivative works must:
  1. Credit the original author
  2. Retain the GPL-3.0 license
  3. Clearly document all modifications

Violation of these terms may result in legal action under applicable intellectual property laws.

---

## 👨‍💻 Creator

Anish Kushwaha  
Engineer • Student  
Interests: AI, Cybersecurity, Creative Coding, Futuristic Interfaces  

GitHub:
https://github.com/Anish-Kushwaha

---

Just A Rather Very Intelligent System  
— J.A.R.V.I.S
