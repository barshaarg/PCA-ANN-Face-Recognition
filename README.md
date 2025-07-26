# Face Recognition using PCA + ANN

This project implements a basic face recognition system using Principal Component Analysis (PCA) and an Artificial Neural Network (ANN).

## 📁 Dataset
- 450 grayscale images of 9 individuals.
- Each image is resized to **15x30** (450 pixels).
- Dataset was preloaded locally and not uploaded to GitHub.

## 🔍 Steps Performed
1. Load and preprocess images (convert to grayscale and resize).
2. Flatten each image and construct the data matrix.
3. Apply PCA for dimensionality reduction.
4. Train a simple ANN on PCA-transformed data.
5. Test with a new “imposter” image.

## 📈 Accuracy
- **Test Accuracy:** 45.56% on unseen data.

## 🤖 Imposter Result
- A random image was predicted as: **Ajay**

## 🚀 Tools Used
- Python, OpenCV, NumPy, scikit-learn, Keras

## 📌 Notes
- The dataset folder is large, so it’s excluded from this repo.
- Trained using `model_training.ipynb` notebook.

---
> Submitted for project: LYST7052  
> Author: Barsha Rani Gogoi
