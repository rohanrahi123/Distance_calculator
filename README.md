# 📏 Real-Time Distance Measurement Between Two Objects using OpenCV

## 📌 Project Overview
This project calculates the **real-time distance between two objects** using **Computer Vision**.  
It uses **OpenCV** to detect objects from a live camera feed and dynamically measures the distance between them.

The system identifies two target objects, marks their center points, and displays the measured distance instantly on screen.

---

## 🎯 Objectives
- Detect two objects in real-time using webcam feed  
- Calculate distance between detected objects  
- Display measurement visually on screen  
- Provide a simple computer vision-based measuring tool  

---

## 🛠 Technologies Used
- **Python**
- **OpenCV**
- **NumPy**
- **Math Module**

---

## ⚙️ How It Works
1. Accesses the webcam feed in real time  
2. Detects selected colored objects (Yellow objects in this project)  
3. Finds contours of the objects  
4. Calculates center coordinates of both objects  
5. Measures pixel distance between centers  
6. Converts pixel distance into real-world distance (cm) using scaling factor  
7. Displays output live on screen  

---
