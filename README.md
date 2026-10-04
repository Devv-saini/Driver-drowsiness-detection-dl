# 🚗 Driver Drowsiness Detection Using Dlib and OpenCV

A Python project that detects driver drowsiness from video using **facial landmarks**.  
It monitors the driver’s **eyes and mouth** to identify sleepiness based on blinking and yawning patterns.

---

## 🎯 Features
- Detects drowsiness from recorded video (no live camera needed)  
- Calculates **Eye Aspect Ratio (EAR)** and **Mouth Aspect Ratio (MAR)**  
- Logs drowsy events with timestamps in a CSV file  
- Shows live EAR/MAR graphs and saves output video  

---

## 🧠 Tech Stack
- **Python**
- **OpenCV** – for video processing  
- **Dlib** – for facial landmark detection  
- **Pandas** – for CSV logging  
- **Matplotlib** – for graph visualization  

---

## ⚙️ Setup

```bash
# Clone repo
git clone https://github.com/YourUsername/drowsiness-detection-dlib-opencv.git
cd drowsiness-detection-dlib-opencv

# Install requirements
pip install opencv-python dlib-bin imutils numpy pandas matplotlib

# Download and place the Dlib model:
shape_predictor_68_face_landmarks.dat from kaggle
then add your test video (e.g. driver_video.mp4).

#run the program
python drowsy_detector.py
```
Output:
output.mp4 → processed video with alerts
drowsiness_log.csv → timestamps of drowsy events

💡 Example Use
Useful for vehicle safety systems to prevent accidents by warning when the driver becomes drowsy.

📜 License

This project is licensed under the MIT License.

About Me

Name: Dev Saini

Course: B.Tech Artificial Intelligence and Data Science

College: COER University

Year: 1st Year
