🌿 Plant Disease Detection using Deep Learning

📃 Project Overview

This project aims to detect plant diseases using deep learning. A Convolutional Neural Network (CNN) is trained on a dataset of plant leaf images to classify diseases and help in early detection for better crop management.

🚀 Features

Image Classification: Identifies plant diseases from leaf images.

Deep Learning Model: Uses CNN for accurate disease detection.

Data Augmentation: Enhances dataset variability for better training.

Google Colab Integration: Uses Kaggle API for dataset download and training on cloud GPUs.

User-friendly Interface: Can be extended with Flask/Streamlit for easy access.

💪 Tech Stack

Python (TensorFlow, Keras, NumPy, Matplotlib, PIL)

Machine Learning: CNN (Convolutional Neural Networks)

Dataset: PlantVillage dataset from Kaggle

Google Colab & Kaggle API for cloud-based training

📊 Dataset

Source: PlantVillage Dataset

Contains labeled images of healthy and diseased plants.

Supports multiple plant species and disease categories.

🔄 Model Training Steps

Download Dataset: Uses Kaggle API to fetch data.

Data Preprocessing: Image augmentation and resizing.

Build CNN Model: Using TensorFlow/Keras.

Train & Evaluate: Train the model on augmented data.

Deploy (Optional): Use Flask/Streamlit for user input and predictions.

🔧 Installation & Setup

1. Install Dependencies

pip install tensorflow numpy matplotlib kaggle

2. Setup Kaggle API

Upload kaggle.json and authenticate.

import json
import os
from zipfile import ZipFile

deep = json.load(open("kaggle.json"))

3. Train Model

Run the plant_disease_detection.ipynb notebook in Google Colab.

🎨 Future Enhancements

Deploy as a mobile/web app.

Extend to real-time disease detection using a webcam.

Improve accuracy with transfer learning (ResNet, MobileNet, etc.).

👨‍👩‍👦 Contributors

Feel free to contribute! Fork and submit a pull request. 🚀

📚 License

This project is licensed under the MIT License.

