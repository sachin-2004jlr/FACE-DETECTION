# FACE-DETECTION
A Python-based face detection project using OpenCV and Haar Cascade Classifiers, designed to process images and detect human faces in real time.
# Real-Time Face Detection with OpenCV

This project demonstrates real-time face detection using Python and OpenCV's Haar Cascade Classifiers. It captures video from the webcam or processes image files to detect and mark human faces in real-time.

## 🔍 Features

- Real-time webcam-based face detection
- Image-based face detection
- Uses Haar Cascades from OpenCV
- Simple and beginner-friendly implementation

## 📁 Project Structure
Create Virtual Environment :
python -m venv ml_face
source ml_face/bin/activate  # On Windows: ml_face\Scripts\activate

Install Required Libraries :
pip install numpy pandas matplotlib seaborn opencv-python

🚀 How to Run :
jupyter notebook "Face det PRJ.ipynb"

Follow the cells in sequence to:

Load your environment
Import libraries
Load the image/video stream
Detect faces using Haar cascades

📷 Sample Output
Detected faces highlighted with rectangles
Console outputs showing number of faces detected

🧠 Algorithm Used
Haar Cascade Classifier from OpenCV

Optional image preprocessing (grayscale conversion)

📌 Requirements
Python 3.7+
OpenCV (opencv-python)
Jupyter Notebook (for running .ipynb)
