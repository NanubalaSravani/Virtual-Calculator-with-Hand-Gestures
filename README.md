# Virtual Hand Gesture Calculator

This project is a **Virtual Calculator** controlled using **hand gestures** detected by a webcam.  
It uses **OpenCV**, **cvzone**, and **MediaPipe** to track hand landmarks and trigger calculator button inputs on the screen.

---

## ✨ Features
- Control calculator using **hand movements** (no keyboard needed!)
- Detects finger pinch gesture for button clicks
- Supports arithmetic operations:
  - `+`, `-`, `*`, `/`
- Includes:
  - **C** : Clear screen
  - **del** : Delete last character
  - **(** and **)**
  - **=** : Evaluate expression
- Real-time webcam display

---

## 🛠️ Technologies Used
| Library / Tool | Purpose |
|----------------|---------|
| Python | Programming Language |
| OpenCV | Webcam & UI Display |
| cvzone | Hand Tracking Helper Tools |
| MediaPipe | Hand Landmark Detection |
| pyttsx3 | Voice Output (optional) |

---

## 📦 Install Dependencies

Run the following commands:

```bash
pip install opencv-python
pip install cvzone
pip install mediapipe
pip install pyttsx3

```bash
