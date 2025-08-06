# 🤟 Sign Language Detection using Deep Learning & OpenCV

This project detects **sign language gestures** using a live webcam feed and classifies them into predefined actions using a custom-trained deep learning model.

---

## 📌 Overview

The system uses **MediaPipe**, **OpenCV**, and a deep learning model (trained with Keras) to:
- 📹 Capture real-time video input
- 🖐 Track hand and body landmarks
- 🧠 Classify sequences into specific sign language gestures

---

## 🧰 Tech Stack

- Python
- OpenCV
- MediaPipe
- NumPy
- TensorFlow / Keras

---

## 🧠 Model Info

- Trained using `.npy` files generated from real-time MediaPipe landmark tracking
- Model saved as `action.h5`
- Supports classification of multiple sign actions like: `hello`, `thanks`, `iloveyou`, etc.

---

## 📁 Project Structure

signLanguageDetection/
├── Sign Language Detection.ipynb     # Jupyter notebook with training + prediction
├── action.h5                         # Trained gesture recognition model
├── MP_Data/                          # Raw MediaPipe data samples for training
├── Logs/
│   └── train/                        # TensorBoard training logs
├── 0.npy                             # Example gesture training array (NumPy)
├── .ipynb_checkpoints/               # Jupyter autosaved checkpoints

