# 🎶 No Strings Attached

**A Real-Time Hand-Tracked Music Synthesizer Powered by Computer Vision and Web Audio.**

---

## 🧠 Project Overview

**No Strings Attached** explores the intersection of music and computer vision by turning your hands into live musical instruments — no strings, buttons, or controllers required. Leveraging MediaPipe for real-time hand tracking and Tone.js for sound synthesis, users can generate arpeggios, play drums, and manipulate audio purely through hand gestures.

---

## 🎯 Problem Statement

What if you could jam without touching an instrument? Traditional instruments require space, hardware, and physical dexterity. No Strings Attached transforms any webcam into an interactive musical surface, allowing users to control audio with gestures alone.

---

## 👥 Stakeholders

| Type              | Who                                 | How They Benefit                          |
|-------------------|--------------------------------------|--------------------------------------------|
| 🎧 End Users      | Musicians, creators, hobbyists       | Perform or experiment with music via gestures |
| 🧑‍🏫 Educators     | Music + STEM teachers                 | Use gesture-based music for engagement     |
| 🧪 Researchers     | CV + HCI community                   | Prototype for gesture-controlled interfaces|
| 🧑‍💻 Developers     | CV/Audio tool builders               | Modular system to extend or remix         |

---

## 🧱 What This Builds (Computer Vision Task)

- **Gesture Recognition** via hand landmark tracking (MediaPipe Hands)
- **Real-Time Input Mapping** to trigger:
  - 🎹 Synth arpeggios
  - 🥁 Drum samples
- **Optional Add-Ons**:
  - Object segmentation for effect control
  - Pose or depth-based dynamics

---

## 🎯 SMART Goals

| Goal | Metric |
|------|--------|
| ⏱️ < 100ms latency from gesture to audio output | Live performance capable |
| ✋ 90%+ gesture detection accuracy in ideal lighting | Robust control |
| 🎶 At least 3 distinct synth sounds & 2 drum kits | Expressive range |
| 🧩 Modular architecture for easy extension | Developer-friendly |
| 🌐 Web-based (no install required) | Public accessibility |


Goal	Description
Specific	Build a real-time web-based app that generates music based on hand gestures via webcam
Measurable	Must detect at least 4 finger positions and trigger 3+ distinct audio outputs
Achievable	Uses existing libraries (MediaPipe, Tone.js) and adapts open-source gesture-music tools
Relevant	Makes music creation more inclusive, fun, and accessible
Time-Bound	Phase 1 done by July 16, working prototype by July 23, final presentation by July 30

---

## 📦 Tech Stack

| Layer | Tools |
|-------|-------|
| 👁️ CV | MediaPipe Hands (JS) |
| 🔊 Audio | Tone.js |
| 🧠 Logic | Modular JS Managers (`MusicManager.js`, `CVManager.js`, `Game.js`) |
| 🧑‍🎨 UI | HTML, CSS, Canvas |
| 🛠️ Build/Test | VSCode, Live Server, Localhost |

---
Planner Board: https://planner.cloud.microsoft/webui/plan/00tmWQEKW0qG1-LoE2rEFGQAAzq_/view/board?tid=b0626806-ceff-4393-821e-f9a3e666893b
