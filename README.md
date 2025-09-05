# KNN-Classifier-Implementation

This repository contains the implementation and report for **Machine Learning (IC272) Assignment 1** at IIT Mandi.  
The project focuses on **preprocessing and classifying Indian districts into literacy categories (Low, Medium, High) using the K-Nearest Neighbors (KNN) algorithm**.

## Dataset
- Indian Districts Population dataset (610 records).  
- Features include: District, State, Population, Growth, Sex Ratio, Literacy.  
- Target variable: Literacy category (Low <65%, Medium 65–85%, High >85%).  

## Preprocessing
- Cleaned and transformed numeric data (removed commas, percentage signs, anomalies).  
- Standardized features to zero mean and unit variance.  
- One-hot encoded states, label-encoded target variable.  
- Dataset split: **70% train, 15% validation, 15% test**.  

## KNN Implementation
- Distance metric: **Euclidean distance**.  
- Tested with k = 3, 5, 7.  
- Best performance at **k = 3**.  

### Validation Accuracies
- k = 3 → **79.12%**  
- k = 5 → 75.82%  
- k = 7 → 73.62%  

### Final Test Accuracy
- **69.56%** on held-out test set.  

## Evaluation Metrics
- Precision, Recall, and F1-score computed per class.  
- Confusion matrices and distribution plots used for analysis.  
- Observed class imbalance (High literacy class had low recall).  

## 📌 Conclusion
The KNN classifier (k=3) achieved moderate accuracy on the dataset.  
Data preprocessing and cross-validation were critical for improving stability.  
Performance highlighted challenges with imbalanced classes, particularly in high-literacy districts.

---

### Author
- **Aayan Garg**  
- Microelectronics & VLSI, SCEE, IIT Mandi  


