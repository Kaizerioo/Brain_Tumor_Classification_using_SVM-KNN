# Brain Tumor Classification using SVM & KNN

## 📌 Overview
This project implements and compares two classic machine learning models — **Support Vector Machine (SVM)** and **K-Nearest Neighbors (KNN)** — for classifying brain tumor types from MRI images. The goal is to build and evaluate a pipeline that can distinguish between different tumor categories (e.g., glioma, meningioma, pituitary, none) using image-derived features and traditional classifiers.

This repository includes:
- Data preprocessing and feature extraction
- Model training (SVM & KNN)
- Evaluation with classification metrics
- Visualization of results

## 📁 Dataset
The dataset used in this project consists of labeled MRI brain tumor images commonly found in public repositories. Images are grouped by tumor type and preprocessed before training.
*(Dataset is provided in the `dataset/` folder or linked through the repository.)*

## 🛠️ Methodology

### 1) **Data Preparation**
- Load MRI images and labels
- Preprocess images:
  - Resize to uniform dimensions
  - Normalize pixel intensity
  - Optional feature extraction (e.g., texture or shape)

### 2) **Feature Extraction**
- Extract meaningful features that represent image characteristics usable by SVM/KNN
- Examples include histogram-based features or pixel intensity distributions

### 3) **Model Training**
- Train **Support Vector Machine (SVM)** classifier
- Train **K-Nearest Neighbors (KNN)** classifier
- Perform train-validation split and hyperparameter tuning

### 4) **Evaluation**
- Evaluate both models using metrics such as:
  - **Accuracy**
  - **Confusion matrix**
  - Classification report (precision, recall, F1-score)
- Visualize results and compare performance

## 📊 Expected Results
The SVM and KNN models provide a baseline comparison for machine learning-based brain tumor classification. Many research works have used similar approaches and achieved respectable performance for MRI-based tumor classification using SVM and KNN. :contentReference[oaicite:1]{index=1}

## 🧠 Tools & Libraries
- Python
- scikit-learn
- numpy, pandas
- matplotlib, seaborn

## 📁 Project Structure
```
Brain_Tumor_Classification_using_SVM-KNN/
├── dataset/
│ └── (MRI images and labels)
├── brain-tumor-classification-using-svm-knn.ipynb
├── README.md
└── requirements.txt
```
