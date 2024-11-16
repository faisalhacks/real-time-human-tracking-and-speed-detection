# 🚶‍♂️ Real-Time Human Detection and Speed Estimation Using YOLOv8

Welcome to the **Real-Time Human Detection and Speed Estimation** project! This project uses **YOLOv8** for detecting humans in a live webcam feed and estimates their speed based on their movement. It also features a **Gradio** web app for real-time interaction and analysis. 

---

## 🛠️ **Technologies Used**

This project utilizes several powerful libraries and tools to deliver its functionalities:

- **[YOLOv8](https://github.com/ultralytics/ultralytics)**: For human detection
- **[OpenCV](https://opencv.org/)**: For handling video capture and frame processing
- **[Gradio](https://gradio.app/)**: For creating an interactive web interface
- **[Google Colab](https://colab.research.google.com/)**: For running the project in a cloud environment

### 📦 Libraries and Tools:
![YOLOv8](https://img.shields.io/badge/YOLOv8-FF5C5C?style=flat&logo=github&logoColor=white)  
![OpenCV](https://img.shields.io/badge/OpenCV-5C3F3F?style=flat&logo=opencv&logoColor=white)  
![Gradio](https://img.shields.io/badge/Gradio-37C9FF?style=flat&logo=gradio&logoColor=white)  
![Google Colab](https://img.shields.io/badge/Google_Colab-FF3366?style=flat&logo=googlecolab&logoColor=white)

---

## 🚀 **Use Case**

This project has the following use cases:

- **Real-time Human Detection**: Detects humans in a live webcam stream using YOLOv8.
- **Speed Estimation**: Tracks the detected humans and estimates their movement speed.
- **Interactive Web Interface**: Provides a Gradio-based interface to view the video feed and speed estimates in real time.
- **Webcam Support**: Works with any webcam connected to your system for capturing live video.

---

## 📸 **How It Works**

### 1. **Human Detection**
- YOLOv8 identifies humans in each frame of the video stream.
  
### 2. **Tracking and Speed Estimation**
- The program tracks detected people across frames, calculates the distance they travel, and estimates their speed in meters per second.
  
### 3. **Gradio Web Interface**
- The Gradio app allows users to interact with the webcam feed and see the human detection and speed information in real-time.
  
---

## 🏃‍♂️ **Demo**: Run it on Google Colab!

You can try out this project directly on Google Colab by clicking the button below. It will open the Colab notebook, where you can run the project step-by-step.

[![Open in Colab](https://colab.research.google.com/drive/1fZM7lfnycho0cGA8RnlzEbvnMH650dxR?usp=sharing)

---

## 🛠️ **Installation & Setup**

### **1. Clone the repository**

```bash
git clone https://github.com/your-username/real-time-human-detection-speed-estimation.git
cd real-time-human-detection-speed-estimation
