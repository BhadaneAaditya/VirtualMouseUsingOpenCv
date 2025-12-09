🖱️ Virtual Mouse – Control Your Computer Using Hand Gestures

A computer-vision powered project that replaces the traditional mouse with real-time hand tracking, gesture recognition, and cursor control using a webcam.

This Virtual Mouse uses OpenCV and MediaPipe to detect hand landmarks, interpret gestures, and translate them into system-level mouse actions such as movement, clicking, and dragging. It demonstrates how AI-driven human-computer interaction can eliminate physical devices and create intuitive, touch-free interaction.

🔥 Features

Real-time Hand Tracking using MediaPipe’s high-precision hand landmark model.

Smooth Cursor Control mapped from hand coordinates to screen coordinates.

Gesture-Based Actions

Index finger up → Move cursor

Index + Thumb pinch → Left click

Custom gestures → Scroll or drag

Touch-Free Interaction using only your webcam.

Lightweight & Fast with minimal latency.

🧠 Technologies Used

Python

OpenCV for image processing

MediaPipe for hand landmark detection

PyAutoGUI for cursor & click control

NumPy for coordinate mapping

🚀 How It Works

Captures webcam frames with OpenCV.

Detects hand landmarks using MediaPipe’s Hand Tracking model.

Calculates finger positions & gestures.

Converts hand coordinates to screen coordinates.

Sends cursor and click commands to the OS.

A blend of computer vision + gesture AI = A fully functional virtual mouse.

📦 Installation

Note: MediaPipe currently supports Python 3.10 or 3.11.
Use a virtual environment for best results.

pip install opencv-python mediapipe numpy pyautogui

🎯 Use Cases

Contactless computer control

Accessibility applications

Gesture-controlled games

Interactive AI/ML projects

Human-computer interaction (HCI) research

📝 Future Enhancements

Right-click and scroll gestures

Multi-hand support

Custom gesture training

Enhanced smoothing algorithms

UI overlay for gesture feedback

🤝 Contributions

Contributions, issues, and feature requests are welcome!
Feel free to fork the repo and submit a pull request.

⭐ Support

If you like this project, consider giving it a star ⭐ on GitHub!
