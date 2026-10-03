<div align="center">

# ⚙️ Project J.A.R.V.I.S

**Just A Rather Very Intelligent System**

*Control your desktop with hand gestures and voice — no mouse, no keyboard.*

> "Sometimes you gotta run before you can walk." — Tony Stark

</div>

---

## What is this?

Project Jarvis is a hands-free desktop control system built as an HCI course project. Using your webcam and MediaPipe hand tracking, you can navigate your computer, open and close applications, scroll, and more — just like Tony Stark, minus the arc reactor.

---

## Features

### Core
- [ ] Hand gesture detection via MediaPipe
- [ ] Open, close, and minimize applications
- [ ] Clap to wake / activate
- [ ] HUD overlay — shows system status, active app, and gesture guide

### Bonus
- [ ] Wake word detection — *"Hey Jarvis"*
- [ ] Voice commands — open app, close app, play/pause, volume control
- [ ] 3D model manipulation via hand tracking (Iron Man hologram style)

---

## Tech Stack

| Layer | Technology |
|---|---|
| Hand tracking | MediaPipe Hands |
| OS control | PyAutoGUI / subprocess |
| Wake word | Porcupine by Picovoice |
| Voice commands | SpeechRecognition + Whisper |
| HUD overlay | OpenCV / Tkinter |
| 3D interaction (bonus) | Three.js + MediaPipe |

---

## Team

5-person team — MSA University / University of Greenwich
Course: Human Computer Interaction

---

## Project Status

🔧 Early development — architecture and gesture detection in progress.

---

## Setup

> Setup instructions will be added here as modules are completed.

---

## HCI Design

This project was developed under 7 usability principles studied in the HCI lab:

- **Navigation** — gesture guide always visible, clear movement commands
- **Familiarity** — HUD mirrors familiar OS layout concepts
- **Consistency** — uniform visual language across all panels
- **Error Prevention** — STOP control and hand-detection confirmation before acting
- **Feedback** — command log confirms every executed action in real time
- **Visual Clarity** — high-contrast minimal HUD, no decorative clutter
- **Flexibility & Efficiency** — supports both beginner (guide-assisted) and expert (direct gesture) use
