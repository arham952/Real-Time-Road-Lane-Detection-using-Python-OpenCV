Real-Time Road Lane Detection using Python & OpenCV 🚗
Project Overview
This project implements real-time lane detection for autonomous vehicles using computer vision techniques. The system processes live video feed or pre-recorded footage to detect lane markings on the road. It uses edge detection, color thresholding, and Hough Transform to identify lane lines and overlay them on the original video.

⚙️ Features
✅ Real-time lane detection from a webcam or video file
✅ Edge detection using Canny Edge Detector
✅ Region of interest (ROI) masking for filtering road lanes
✅ Hough Line Transform for detecting lane lines
✅ Polynomial fitting for smoother lane visualization
✅ Works on highways and urban roads with clear lane markings

🛠️ Technologies Used
🔹 Python – Core programming language
🔹 OpenCV – Image processing & computer vision
🔹 NumPy – Efficient numerical computations
🔹 Matplotlib – Visualization of detected lanes

🚀 How to Run the Project
1️⃣ Clone the Repository

git clone https://github.com/arham952/Real-Time-Road-Lane-Detection-using-Python-OpenCV.git
cd Real-Time-Road-Lane-Detection-using-Python-OpenCV

2️⃣ Install Dependencies
Make sure you have Python installed. Then, install the required libraries:

pip install opencv-python numpy matplotlib

3️⃣ Run the Lane Detection Script
For real-time detection from the webcam, run:

python lane_detection.py

For video file input, modify the script to load your video:
cap = cv2.VideoCapture('your_video.mp4')

Sample Output

🛠️ Future Improvements
🔹 Implement Deep Learning models (CNNs) for advanced lane detection
🔹 Improve performance in poor lighting & weather conditions
🔹 Add curve detection & lane departure warning system

📜 License
This project is open-source under the MIT License.
