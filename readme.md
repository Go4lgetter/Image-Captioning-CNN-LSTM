# Image Captioning using CNN-LSTM

This project implements an Image Captioning system using a Convolutional Neural Network (CNN) as an encoder and a Long Short-Term Memory (LSTM) network as a decoder.

## 📌 Project Overview
The model extracts visual features from images using a pre-trained CNN (VGG16) and generates descriptive captions using an LSTM-based sequence model.

## 🛠 Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- tqdm

## 🧠 Model Architecture
- CNN (VGG16) for feature extraction
- LSTM for caption generation
- Encoder–Decoder framework

## 📊 Output
The system generates meaningful and grammatically coherent captions for unseen images.

## 🚀 Future Improvements
- Add attention mechanism
- Use Transformer-based models
- Extend to video captioning

## 📂 Dataset

This project uses the Flickr8k dataset.

You can download it from:
https://www.kaggle.com/datasets/adityajn105/flickr8k

After downloading, place the Images folder and captions file inside the project directory.