# 🖱️ Virtual Mouse – Control Your Computer Using Hand Gestures

A computer-vision powered project that replaces the traditional mouse with real-time hand tracking, gesture recognition, and cursor control using a webcam.

This Virtual Mouse uses **OpenCV** and **MediaPipe** to detect hand landmarks, interpret gestures, and translate them into system-level mouse actions such as movement, clicking, and dragging. It demonstrates how AI-driven human–computer interaction can eliminate physical devices and create intuitive, touch-free interaction.

---

## 🔥 Features

- **Real-time Hand Tracking** using MediaPipe’s high-precision hand landmark model  
- **Smooth Cursor Control** mapped from camera coordinates to screen coordinates  
- **Gesture-Based Actions:**  
  - Index finger up → Move cursor  
  - Index + Thumb pinch → Left click  
  - Custom gestures → Scroll or drag  
- **Touch-Free Interaction** using only a standard webcam  
- **Lightweight & Fast** with minimal latency  

---

## 🧠 Technologies Used

- Python  
- OpenCV – image processing & video capture  
- MediaPipe – hand landmark detection  
- PyAutoGUI – cursor & click automation  
- NumPy – vector and coordinate mapping  

---

## 🚀 How It Works

1. Captures webcam frames using OpenCV  
2. Detects hand landmarks using MediaPipe’s Hand Tracking model  
3. Calculates finger positions & interprets gestures  
4. Maps hand coordinates to actual screen coordinates  
5. Sends cursor and click commands to the operating system  

A blend of **computer vision + gesture AI** results in a fully functional, touchless virtual mouse.

---

## 📦 Installation

> **Note:** MediaPipe supports **Python 3.10 or 3.11**. Use a virtual environment for best compatibility.

Install dependencies:

```bash
pip install opencv-python mediapipe numpy pyautogui
