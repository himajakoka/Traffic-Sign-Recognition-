# 🚦 Traffic Sign Recognition

A deep learning-based web application that recognizes and classifies traffic signs from uploaded images.

The project uses a trained Convolutional Neural Network (CNN) model with TensorFlow/Keras and provides a simple Flask web interface for image-based traffic sign recognition.

---

## 📌 About the Project

Traffic signs play an important role in maintaining road safety and guiding drivers.

This project aims to automatically identify traffic signs from images using a trained deep learning model. The application allows users to upload an image of a traffic sign, processes the image, and predicts the corresponding traffic sign class.

---

## 🎯 Objective

The main objectives of this project are:

- Detect and recognize traffic signs from images.
- Use deep learning for image classification.
- Provide a simple web interface for users.
- Display the predicted traffic sign class.
- Demonstrate the practical use of CNNs in computer vision.

---

## ✨ Features

- 📷 Upload a traffic sign image.
- 🧠 CNN-based image classification.
- 🚦 Traffic sign prediction.
- 🌐 Flask-based web interface.
- ⚡ Fast image processing using OpenCV.
- 📊 Uses a trained Keras/TensorFlow model.
- 🏷️ Traffic sign labels are managed using `labels.csv`.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Core programming language |
| TensorFlow | Deep learning framework |
| Keras | Neural network model |
| OpenCV | Image processing |
| Flask | Web application framework |
| NumPy | Numerical operations |
| Pandas | Data handling |
| Pillow | Image processing |
| HTML/CSS | Web interface |

---

## 📂 Project Structure

```text
Traffic-Sign-Recognition/
│
├── static/
│   └── CSS and static files
│
├── templates/
│   └── HTML templates
│
├── uploads/
│   └── Uploaded images
│
├── app.py
│   └── Flask web application
│
├── main.py
│   └── Main project/model code
│
├── model.h5
│   └── Trained deep learning model
│
├── labels.csv
│   └── Traffic sign class labels
│
├── test.py
│   └── Testing code
│
├── requirements.txt
│   └── Required Python packages
│
└── README.md
    └── Project documentation
