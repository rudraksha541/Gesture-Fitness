# Gesture Fitness🏋️

##  AI-Based Rep Counter & Posture Correction System

An **AI-powered fitness assistant** that uses computer vision to **automatically count exercise repetitions** and **analyze posture in real time** using a webcam.  
The system helps users perform workouts with **correct form**, reducing injury risk and improving workout efficiency.

---

## 📌 Project Overview

This project leverages **MediaPipe Pose Estimation** and **OpenCV** to detect human body landmarks and track joint movements during exercises.  
Based on joint angles and movement thresholds, the system:

- Counts repetitions accurately
- Detects incorrect posture
- Provides real-time visual feedback

Supported exercises include:
- Push-ups
- Squats
- Bicep Curls

Each exercise is implemented as a **separate Python module** for modularity and scalability.

---

## 🎯 Key Features

- 📷 **Real-time webcam-based detection**
- 🧠 **Pose landmark extraction using AI**
- 🔢 **Automatic repetition counting**
- 🦴 **Joint angle calculation**
- ⚠️ **Posture correction feedback**
- 📊 **Live on-screen metrics**
- 🧩 **Modular exercise-wise scripts**

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---------|--------|
| **Python** | Core programming language |
| **OpenCV** | Video capture & image processing |
| **MediaPipe** | Pose estimation & body landmark detection |
| **NumPy** | Mathematical calculations |
| **Webcam** | Live video input |

---

## 🧠 How It Works (Technical Flow)

1. Webcam captures live video frames  
2. MediaPipe Pose detects **33 body landmarks**
3. Relevant joints are selected based on exercise
4. Angles between joints are calculated using vector math
5. Movement phases are detected (up/down)
6. Rep counter updates when a valid cycle completes
7. Incorrect posture triggers visual warnings

---

## 📁 Project Structure

