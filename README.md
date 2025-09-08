# Gesture-Volume-Tracker
A Hand Volume Control Gesture I made with python

# Gesture Volume Tracker

Gesture Volume Tracker lets you control your system volume using hand gestures captured from your webcam. Pinch or separate your thumb and index finger to adjust volume in real-time.

# Features

- Track hand movements using Mediapipe

- Adjust system volume based on distance between thumb and index finger

 -Works on Windows (via Pycaw) and macOS (via AppleScript)

- Real-time volume bar overlay on screen

- Smooth, responsive gesture-to-volume mapping

# Requirements

- Python 3.8+

- OpenCV (pip install opencv-python)

- Mediapipe (pip install mediapipe)

- NumPy (pip install numpy)

- Pycaw (Windows only: pip install pycaw comtypes)

# Usage

Clone the repository:

git clone https://github.com/yourusername/Gesture-Volume-Tracker.git
cd Gesture-Volume-Tracker


# Install dependencies:

pip install -r requirements.txt


# Run the project:

python gesture_volume.py


Use your thumb and index finger to control the volume.

# Notes

On macOS, the script uses AppleScript to set system volume.

On Windows, Pycaw manages system volume.

Recommended camera resolution: 640x480 for smooth performance.

<img width="636" height="494" alt="Screenshot 2025-09-08 at 8 56 40 AM" src="https://github.com/user-attachments/assets/77bc62f3-a8ac-411c-b0e8-719217a5c16f" />



