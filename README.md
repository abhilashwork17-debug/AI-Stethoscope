# AI-Stethoscope# 🩺 AI Stethoscope — Smart Heart Sound Analysis

## Overview

The AI Stethoscope is an IoT-enabled healthcare system designed to detect heart abnormalities using audio signal analysis. It records heart sounds via a digital microphone, processes them using a machine learning model, and provides real-time predictions through a web interface.
---
##  Features

* 🎧 Real-time heart sound recording
* 🤖 AI-based classification (Normal / Abnormal)
* 🌐 Web dashboard for live results
* 📡 IoT integration with Raspberry Pi
* 📊 Visual feedback for analysis
---
##  Tech Stack

* **Hardware:** Raspberry Pi Zero 2 W, Microphone
* **Backend:** Python, Flask
* **Machine Learning:** YAMNet
* **Dataset:** PhysioNet Challenge 2016
* **Frontend:** HTML, CSS, JavaScript
---
##  How It Works

1. Heart sound is captured using a microphone connected to Raspberry Pi
2. Audio is sent to the Flask server
3. The ML model processes the sound and extracts features
4. The system predicts whether the sound is normal or abnormal
5. Results are displayed on a web dashboard in real time
---
##  Project Structure

```
ai-stethoscope/
│
├── backend/          # Flask server & ML model
├── frontend/         # Web dashboard
├── models/           # Trained model files
├── assets/           # Screenshots / images
├── docs/             # Reports / documentation
└── README.md
```
---
##  How to Run

1. Clone the repository

```
git clone https://github.com/your-username/ai-stethoscope.git
cd ai-stethoscope
```

2. Install dependencies

```
pip install -r requirements.txt
```

3. Run the server

```
python app.py
```
---
##  Results

* Successfully classifies heart sounds into normal and abnormal categories
* Demonstrates real-time prediction with IoT integration
* Provides a scalable approach for smart healthcare monitoring
---
## 🔮 Future Improvements

* Improve model accuracy with larger datasets
* Add mobile app integration
* Deploy on cloud for remote monitoring
---
##  Author

**Abhilash Mishra**
B.Tech CSE | AI & Full-Stack Developer
