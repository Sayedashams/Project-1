# ✋🤖 Hand Gesture-Based Home Automation

This is my mini project that uses hand gestures detected through OpenCV to control electrical appliances via an Arduino board and relays.

# 🎯 Project Goals
- Use hand gestures to automate home appliance control
- Create a touch-free system using computer vision and Arduino

# ⚙ Technologies Used
- Python (OpenCV, cvzone)
- Arduino (Firmata or relay control)
- pyfirmata or serial communication

# 🧠 How It Works
- OpenCV detects hand gestures via webcam
- Python sends a signal to Arduino via serial or Firmata
- Arduino switches appliances on/off using relays

# 📁 Files
- hand-gesture.py – Python script for webcam gesture recognition
- firmata.ino – Arduino code to control relays

# 🚀 How to Run

1. Install required Python libraries:
    ```bash
 pip install opencv-python pyfirmata cvzone
2. Upload Arduino code to board
3. Run the python script
