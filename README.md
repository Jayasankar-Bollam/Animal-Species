# 🐾 Animal Species Detection Using YOLOv8

## 📌 Project Overview

Animal Species Detection Using YOLOv8 is a Computer Vision and Deep Learning-based web application developed using Python and Django. The system automatically detects and classifies animal species from uploaded images using a custom-trained YOLOv8 object detection model.

The model has been trained on approximately 2300 annotated animal images and is capable of identifying multiple animal species within a single image. The application provides a simple web interface where users can upload an image and instantly receive detection results with bounding boxes and species labels.

---

## 🎯 Project Objective

The primary objective of this project is to develop an intelligent wildlife recognition system that can automatically detect and classify animal species from images.

This project demonstrates the practical integration of:

* Deep Learning
* Object Detection
* Computer Vision
* Web Application Development
* AI Model Deployment

---

## 💡 Project Idea

Wildlife monitoring and species identification often require manual inspection and expert knowledge. This project automates that process using YOLOv8, a state-of-the-art object detection algorithm.

The system analyzes uploaded images, detects animals present in the image, draws bounding boxes around detected animals, and predicts their species names with confidence-based filtering.

---

## 🚀 Features

* YOLOv8-based animal species detection
* Multi-object detection support
* Bounding box visualization
* Species name labeling
* Model performance visualization
* Training graph visualization
* User authentication module
* Django web interface
* Image upload and processing

---

## 🧠 Animal Species Supported

The model is trained to detect species including:

* Antelope
* Badger
* Bat
* Bear
* Beaver
* Beetle
* Bison
* Black Bear
* Boar
* Bobcat
* Buffalo
* Butterfly
* Crow
* Fish
* Honeybee
* Koala
* Pig
* Polar Bear
* Zebra

---

## 🛠 Technology Stack

### Frontend

* HTML
* CSS
* JavaScript

### Backend

* Python
* Django

### Deep Learning & Computer Vision

* YOLOv8
* OpenCV
* NumPy
* Pandas
* Matplotlib

### Database

* SQLite

### Version Control

* Git
* GitHub

---

## 📂 Project Modules

### 1. User Login

Provides authentication functionality for system access.

Default Credentials:

Username: admin

Password: admin

### 2. Train YOLOv8 Algorithm

Displays model training performance including precision and recall metrics.

### 3. Training Graph

Visualizes YOLOv8 training statistics including:

* Training Loss
* Validation Loss
* Precision
* Recall
* mAP Metrics

### 4. Animal Species Detection

Allows users to upload images and detect animal species using the trained YOLOv8 model.

---

## 🔄 System Workflow

1. User logs into the application.
2. User uploads an animal image.
3. Image is preprocessed using OpenCV.
4. YOLOv8 extracts visual features.
5. Animals are detected and classified.
6. Bounding boxes are drawn around detected animals.
7. Species names are displayed on the image.
8. Detection results are presented through the web interface.

---

## 📊 Dataset Information

Dataset Source:

Roboflow Animal Species Detection Dataset

Dataset Link:

https://universe.roboflow.com/ecowatchai/animal-species-detection

Dataset Size:

Approximately 2300 annotated images.

---

## 📥 Project Resources

### Complete Project Folder

https://drive.google.com/drive/folders/1OJxqvStKGD0d1NvlymsX_la44EOfh7Hm?usp=drive_link

### Dataset

https://drive.google.com/drive/folders/1hf27kfaNOfO1lD91Veim7ILlrjShXfEL

### Trained Model

https://drive.google.com/drive/folders/1yg0ST6shCmi7fxdg0a19jlhkQnoIIQgk

### Test Images

https://drive.google.com/drive/folders/1efePz4gi9_TgTojsDwssGrRpor7X08SG

### SQLite Database

https://drive.google.com/file/d/1pNdU4pEojM6ju1cm3wOw0p-gOlpSPt_S/view?usp=drivesdk

---

## ⚙️ Installation

### Clone Repository

git clone https://github.com/Jayasankar-Bollam/AnimalSpecies.git

### Install Dependencies

pip install -r requirements.txt

### Run Application

python manage.py runserver

### Open Browser

http://127.0.0.1:8000/index.html

---

## 🌍 Applications

* Wildlife Monitoring
* Biodiversity Research
* Animal Population Tracking
* Educational Platforms
* Environmental Conservation
* AI-Powered Image Analysis
* Ecological Research

---

## 🔮 Future Enhancements

* Real-time video-based animal detection
* Mobile application integration
* Cloud deployment
* Species confidence score display
* Multi-class analytics dashboard
* Automatic report generation

---

## 👨‍💻 Author

Jayasankar Bollam

B.Tech – Computer Science and Engineering

Full Stack Developer | AI & Machine Learning Enthusiast

GitHub:
https://github.com/Jayasankar-Bollam

---

## 📜 License

This project is developed for educational, academic, and research purposes.

