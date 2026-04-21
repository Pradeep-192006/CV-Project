🪄 Invisibility System using OpenCV & MediaPipe

📌 Description
This project creates a real-time invisibility effect using a webcam.
When you raise your hand ✋, the system hides your body by replacing it with the background.
When your hand is down 👇, you appear normally.

🚀 Features
Hand gesture control (Up = Invisible, Down = Visible)
Real-time video processing
AI-based human segmentation
Smooth switching using stability logic
FPS display

🛠️ Technologies Used
Python
OpenCV
MediaPipe
NumPy

📦 Requirements
Install required libraries:
Bash
pip install opencv-python mediapipe numpy

⚙️ How It Works
Background Capture
Captures background at the start (without the person).

Hand Detection
Detects hand using MediaPipe.
If index finger is above wrist → Invisible mode.

Stability Check
Uses a frame counter to avoid sudden flickering.

Segmentation
Separates the person from the background using AI.

Invisibility Effect
Replaces the person area with the saved background.

🖥️ Usage
Run the program:

Bash
python invisibility.py

Controls:
✋ Hand Up → Invisible
👇 Hand Down → Visible
Press ESC → Exit

Output Video
🎥 Download video here: https://github.com/Pradeep-192006/CV-Project/raw/main/visible%20and%20invisible/output%20(4).mp4

⚠️ Notes
Ensure good lighting
Stay still during background capture
Works best with simple background

💡 Future Scope
More gesture controls
Better segmentation accuracy
Custom background support
