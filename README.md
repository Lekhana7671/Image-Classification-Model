# Image-Classification-Model

*Company*: Codtech IT Solutions Private Limited

*Name*: Yarnakula Lekhana

*Intern ID*: CTIS1133

*Domain*: Machine Learning

*Duration*: 12 Weeks

*Mentor*: Neela Santosh

# 🌟 Image Classification Using Convolutional Neural Networks (CNN)

## 📌 Overview
This project demonstrates **image classification** using **Convolutional Neural Networks (CNNs)** implemented with **TensorFlow/Keras**. The goal is to build a functional CNN that can classify images into multiple categories and evaluate its performance on a test dataset.  

For simplicity and reproducibility, the project uses the **CIFAR-10 dataset**, a well-known dataset containing 60,000 32x32 RGB images across 10 classes.

---

## 🎯 Objectives
- Build a CNN to classify images from the CIFAR-10 dataset.  
- Preprocess and normalize image data for optimal learning.  
- Train and validate the model using training and validation sets.  
- Evaluate performance using test data and accuracy metrics.  
- Present results in a clean, reproducible Jupyter Notebook.

---

## 📊 Dataset Description
The **CIFAR-10 dataset** contains:

| Feature | Description |
|---------|-------------|
| Images | 32x32 color images (RGB) |
| Classes | 10 categories: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck |
| Size | 60,000 images (50,000 train, 10,000 test) |

- The dataset is **built into TensorFlow/Keras**, so no external download is required.  
- Images are normalized to improve CNN training efficiency.

---

## 🛠️ Tools & Technologies Used
- Python 3.x  
- TensorFlow/Keras  
- Matplotlib (for visualization)  
- Google Colab or Jupyter Notebook  

---

## 🧪 Methodology

### 1. Data Preprocessing
- Normalize pixel values to range [0,1]  
- One-hot encode class labels for multi-class classification  

### 2. Build CNN Model
- Use **Conv2D + MaxPooling2D** layers to extract spatial features  
- Flatten features and connect to **Dense layers** for classification  
- Use **Dropout layers** to reduce overfitting  
- Use **Softmax activation** in output layer for multi-class prediction  

### 3. Compile Model
- Optimizer: `Adam`  
- Loss function: `categorical_crossentropy`  
- Metric: `accuracy`  

### 4. Train Model
- Use training dataset with validation split  
- Train for multiple epochs (e.g., 10) with batch size of 64  

### 5. Evaluate Model
- Test model on unseen test data  
- Print **test accuracy** and optionally **loss**  
- Optional: plot training and validation accuracy over epochs  

---

## 📈 Results & Analysis
- CNN achieves high accuracy on CIFAR-10, demonstrating its ability to extract spatial features from images.  
- Model evaluation metrics (accuracy) indicate strong performance on the test dataset.  
- Visualization of training history helps identify potential overfitting or underfitting.  
- This workflow demonstrates a **complete end-to-end CNN image classification pipeline**.

---

## ✅ Deliverables
- `CNN_Image_Classification.ipynb` – Jupyter Notebook containing:
  - Data preprocessing  
  - CNN model architecture  
  - Training and validation process  
  - Test evaluation metrics  
  - Analysis and observations  

---

## 🚀 How to Run
1. Open the notebook in **Google Colab** or **Jupyter Notebook**  
2. Run all cells sequentially (Shift + Enter)  
3. Explore model summary, accuracy metrics, and predictions  

---

## 🙌 Acknowledgments
This project is completed as part of an internship task at **CODTECH** to demonstrate knowledge of **Convolutional Neural Networks** and **image classification** workflows.  

# Output

<img width="1910" height="865" alt="Image" src="https://github.com/user-attachments/assets/0df14718-40f8-4b4e-8686-7d91655a0653" />
