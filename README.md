# Smart Motion Detection CCTV

A real-time motion detection system built using Python and OpenCV.  
It acts like a basic CCTV system that detects movement using webcam feed and triggers a beep alert.

---

## Features
- Real-time webcam video capture
- Motion detection using frame difference
- Noise filtering for better accuracy
- Beep alert when motion is detected

---

## Technologies Used
- Python
- OpenCV
- Winsound (for alert sound)

---

## How It Works
1. Captures video from webcam
2. Compares consecutive frames
3. Detects differences (motion)
4. Highlights motion areas using contour detection
5. Triggers sound alert when motion is detected

---

## Installation

Install required library:

```bash
pip install opencv-python
```

---

## Run the Project

```bash
python motion_detection.py
```

Press `ESC` to exit the program.

---

## Future Improvements
- Save video when motion is detected
- Add email/phone alerts
- AI-based person detection
- Combine with face recognition system
- Cloud CCTV system

---

## Author
Shiv
