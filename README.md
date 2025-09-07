# Elder Monitoring and SOS Alert System

## 📌 Project Overview
The Elder Monitoring and SOS Alert System is an AI-based safety solution that uses **computer vision, deep learning, and IoT** to detect falls, gestures, and suspicious activities for elderly individuals living alone. The system triggers **real-time SOS alerts** and improves emergency response time, ensuring better safety and independent living for the elderly.

---

## 🚀 Features
- **Fall Detection** – Vision-based fall recognition using pose estimation and motion analysis.  
- **Gesture-based SOS** – Emergency recognition through simple hand gestures.  
- **Night Vision Monitoring** – Low-light monitoring for nighttime safety.  
- **Suspicious Activity Detection** – Detects abnormal activities in the environment.  
- **Database Integration** – Stores alerts, events, and history for analysis.  
- **Real-Time Alerts** – Sends warnings via screen, sound, or potential notification integration.  

---

## 🛠️ Technology Stack
- **Programming Language**: Python  
- **Libraries**: OpenCV, Mediapipe, NumPy, Scikit-learn, TensorFlow/PyTorch (optional)  
- **Database**: SQLite (via `db.py`)  
- **Modules**:
  - `fall_detection.py` – Detects falls
  - `gesture_sos.py` – Recognizes SOS gestures
  - `sos_alert.py` – Triggers alerts
  - `monitor_motion.py` – Tracks abnormal movement
  - `night_vision.py` – Enhances visibility in low light
  - `suspicious.py` – Detects suspicious behavior

---

## 📂 Project Structure
elder_monitoring_system/
│── db.py
│── fall_detection.py
│── gesture_sos.py
│── sos_alert.py
│── monitor_motion.py
│── night_vision.py
│── suspicious.py
│── utils/config.py
│── requirements.txt

yaml
Copy code

---

## ⚙️ Installation & Setup
1. Clone the repository  
   ```bash
   git clone <repo_url>
   cd elder_monitoring_system
Install dependencies

bash
Copy code
pip install -r requirements.txt
Run the main program

bash
Copy code
python main.py
🎯Outcomes
Real-time monitoring of elderly people.

Fall detection and SOS alerts with high accuracy.

Gesture recognition for emergency help.

Night vision and suspicious activity monitoring.
