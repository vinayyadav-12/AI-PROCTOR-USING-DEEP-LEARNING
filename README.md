# 📘 AI Proctor Using Deep Learning

An AI-powered proctoring system built using deep learning and computer vision techniques to monitor students during online examinations.  
The system detects suspicious activities such as:

- Presence of multiple persons  
- User absence  
- Mobile phone detection  
- Eye gaze deviation  
- Head pose anomalies  

---

## 🚀 Features

- **Face Detection** – Detects whether the user is present  
- **Multiple Person Detection** – Flags if more than one person appears  
- **Eye Gaze Tracking** – Detects if user is looking away  
- **Mobile Phone Detection** – Identifies phones in the frame  
- **Head Pose Estimation** – Detects suspicious head movements  
- **Real-time Monitoring** – Uses webcam input  
- **Deep Learning Models** – Highly accurate trained models  

---

## 🧠 Tech Stack & Libraries

- Python  
- OpenCV  
- TensorFlow / Keras  
- Mediapipe  
- dlib  
- NumPy  
- Matplotlib  
- deepface 

---

## 📁 Project Structure

<pre>
AI-Proctor-using-Deep-Learning/
├── models/                   # Pretrained models
├── utils/                    # Helper functions
├── images/                   # Media assets (screenshots)
├── proctor.py                # Main program
├── phone_detection.py        # Phone detection module
├── eye_tracking.py           # Eye tracking module
├── face_detection.py         # Face + multiple person detection
├── head_pose.py              # Head pose estimation
├── requirements.txt          # Required python libraries
└── README.md                 # Documentation
</pre>

## ⚙️ How It Works

1. Webcam feed is captured in real-time  
2. Each frame is processed through multiple models:
   - Face detector  
   - Object detector (phones/persons)  
   - Eye-gaze estimator  
   - Head-pose estimator  
3. System raises flags on suspicious behaviour  
4. Alerts + bounding boxes are shown on the live video  

---

## 🚀 Future Improvements

- Voice activity & background noise detection  
- Cheating score + reporting dashboard  
- Face recognition for identity verification  
- Cloud-based monitoring panel  
- Integration with LMS/exam portals  
