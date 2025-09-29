**🎥 Screen Recorder using PyAutoGUI & OpenCV**

This project is a Python-based Screen Recorder that captures the screen in real-time and saves it as a video file. It uses PyAutoGUI to take screenshots and OpenCV (cv2) to process and save them as a video.

**🚀 Features**

✅ Records screen at a specified resolution (default: 1920x1080)
✅ Uses the XVID codec for video compression
✅ Allows you to preview live recording in a resizable window
✅ Saves output as .avi file format
✅ Recording can be stopped anytime by pressing 'q'
✅ Debug mode available for PyAutoGUI

**🛠️ Tech Stack**

Python

PyAutoGUI → for capturing screenshots

OpenCV (cv2) → for video writing & live window display

NumPy → for handling image arrays

**📂 How It Works**

Import required libraries: PyAutoGUI, OpenCV, NumPy

Set resolution → Example: (1920, 1080)

Specify codec → Using XVID

Create VideoWriter → Handles writing frames to a .avi file

Open preview window → A resizable "Live" window displays recording in real-time

Capture frames:

PyAutoGUI takes a screenshot

Convert screenshot from BGR → RGB

Write frame to the output file

Stop recording → Press 'q'

**▶️ Usage**
1️⃣ Clone the Repository
git clone https://github.com/your-username/screen-recorder.git
cd screen-recorder

2️⃣ Install Dependencies
pip install pyautogui opencv-python numpy

3️⃣ Run the Program
python main.py

4️⃣ Stop Recording

Press 'q' to stop recording and save the video.

**⚙️ Configuration**

Resolution → Default:1920x1080

Codec → XVID

FPS → Adjustable (default: 20)

Output File → output.avi

You can modify these values in the script to suit your needs.

## 📸 Output  

Here’s an example of the recorded screen:  

[🎬 Watch the Output Video](Recording.avi)


**🙌 Acknowledgements**

PyAutoGUI
 for screen capture

OpenCV
 for video processing
