# 🤟 Sign Language to Text and Speech Translation System

A real-time AI-powered system that recognizes sign language hand gestures using Computer Vision and Deep Learning, then converts them into text and speech. This project aims to bridge the communication gap between hearing-impaired individuals and others by providing an intelligent gesture recognition system.

---

## 📖 Overview

This project uses a **Convolutional Neural Network (CNN)** trained on sign language gesture images to recognize hand signs captured from a webcam. The recognized gesture is displayed as text and converted into speech using a Text-to-Speech (TTS) engine.

---

## 🚀 Features

- Real-time hand gesture recognition using webcam
- Converts sign language into text
- Converts recognized text into speech
- CNN-based gesture classification
- Image preprocessing using OpenCV
- User-friendly interface
- Fast and accurate predictions

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- pyttsx3
- CNN (Convolutional Neural Network)

---

## 🏗️ Project Workflow

```
Webcam
   │
   ▼
Capture Video Frames
   │
   ▼
Image Preprocessing
   │
   ▼
CNN Model Prediction
   │
   ▼
Recognized Gesture
   │
   ├────────► Display Text
   │
   └────────► Convert Text to Speech
```

---

## 📂 Project Structure

```
Sign-Language-To-Text-And-Speech-Translation-System/
│
├── app.py
├── train.py
├── collect-data.py
├── preprocessing.py
├── image_processing.py
├── requirements_pip.txt
├── requirements_conda.txt
├── README.md
└── signs.png
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/mitkari2612/Sign-Language-To-Text-And-Speech-Translation-System.git
```

### Navigate to the Project

```bash
cd Sign-Language-To-Text-And-Speech-Translation-System
```

### Install Dependencies

Using pip:

```bash
pip install -r requirements_pip.txt
```

or using Conda:

```bash
conda create --name sign-language python=3.10
conda activate sign-language
pip install -r requirements_pip.txt
```

---

## ▶️ Run the Project

```bash
python app.py
```

---

## 🧠 Model Pipeline

```
Dataset
   │
   ▼
Image Collection
   │
   ▼
Image Preprocessing
   │
   ▼
CNN Model Training
   │
   ▼
Model Evaluation
   │
   ▼
Real-Time Gesture Prediction
   │
   ▼
Text Output
   │
   ▼
Speech Output
```

---



## 📌 Applications

- Assistive technology for deaf and mute individuals
- Human-computer interaction
- Educational learning platform
- Smart communication systems
- AI-based accessibility solutions

---

## ✅ Advantages

- Real-time prediction
- Lightweight implementation
- Easy to use
- Accurate gesture recognition
- Improves accessibility
- Low-cost communication solution

---

## ⚠️ Limitations

- Sensitive to lighting conditions
- Performance depends on webcam quality
- Supports only trained gestures
- Background noise may affect accuracy

---

## 🔮 Future Enhancements

- Support complete words and sentences
- Dynamic gesture recognition using LSTM/Transformer
- MediaPipe hand landmark detection
- Mobile application deployment
- Multi-language text and speech support
- Improved model accuracy using larger datasets

---

## 💡 Skills Demonstrated

- Python Programming
- Deep Learning
- TensorFlow
- CNN
- Computer Vision
- OpenCV
- Image Processing
- Model Training
- Real-Time Inference
- Text-to-Speech Integration

---

## 👨‍💻 Author

**Ajay Mitkari**

- 🎓 B.Tech in Electronics & Telecommunication Engineering
- 🎓 PG-Diploma in Big Data Analytics (CDAC)
- 💼 Interested in AI, Machine Learning, Deep Learning, Computer Vision, and Generative AI

---


## 📜 License

This project is developed for educational and learning purposes.
