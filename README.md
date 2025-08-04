# 🎭 PCA + ANN Face Recognition System

This project implements a face recognition system using **Principal Component Analysis (PCA)** for dimensionality reduction and an **Artificial Neural Network (ANN)** for classification.

---

## 📁 Dataset

- 450 grayscale images of known individuals (organized in subfolders).
- Images resized to **92x112** (10304 features).
- Additional "imposter" images used to evaluate unknown face detection.

---

## 🚀 Project Steps

1. **Image Preprocessing**  
   - Grayscale conversion, resizing, flattening.

2. **Label Encoding & Data Split**  
   - Labels encoded and split into 60% training / 40% test sets.

3. **PCA (Dimensionality Reduction)**  
   - Reduced from 10304 → 50 principal components.

4. **ANN Training**  
   - Trained 3-layer Keras ANN on PCA-transformed features.

5. **Evaluation**  
   - Tested model accuracy on known faces.
   - Also evaluated on unseen imposter images.

6. **Imposter Handling**  
   - Used confidence thresholding to reject unknown faces.
   - Successfully labeled unknowns as "Unknown".

7. **Model Saving**  
   - Saved trained model (`.keras`) and PCA data (`.npy`, `.pkl`).

---

## 📊 Results

- **Training Accuracy:** ~96%
- **Test Accuracy:** ~38.89%
- **Imposter Evaluation:** Unknown faces correctly rejected using threshold (≥ 0.9)

---

## 🧰 Tools Used

- Python, OpenCV, NumPy, scikit-learn, TensorFlow/Keras  
- Jupyter Notebook for development

---

## 📂 Folder Structure

