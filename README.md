# 👤 Face Recognition GUI App

A desktop GUI application for real-time face detection, recognition, age/gender prediction, and emotion detection using OpenCV, TensorFlow, and deep learning models.

---

## 📸 Features

- Real-time face detection using Haar Cascades
- Face data collection via webcam or video
- Train a face recognition model using LBPH (Local Binary Patterns Histograms)
- Emotion detection using a CNN model
- Age and gender prediction using pre-trained models
- User-friendly GUI built with Tkinter

---

## 🧠 How It Works

1. **Capture Face Data**
   - Users can record their face using the webcam or a video file
   - Up to 300 images per person are captured and stored in a `/data` folder

2. **Train Face Classifier**
   - The app uses OpenCV’s `LBPHFaceRecognizer` to train a classifier for each user

3. **Run Face Recognition**
   - On running, it recognizes the user in real time
   - Predicts **age**, **gender**, and **emotion**

---

## 🛠️ Tech Stack & Libraries

- `Python 3.10`
- `OpenCV` (`opencv-contrib-python==4.5.5.64`)
- `NumPy==1.21.4`
- `TensorFlow` (use version compatible with Python 3.10, e.g. `2.10.1`)
- `Keras` and `keras-preprocessing`
- `Pillow` for image handling
- `imutils` for convenience image operations
- `MTCNN` for face landmark detection
- `Tkinter` for GUI

---

## 🧑‍💻 How to Use

### 1. 📦 Clone the repository

```bash
git clone https://github.com/Harsh-0812/FaceRecognition-GUI-APP.git
cd FaceRecognition-GUI-APP
