# SMART-PNEUMONIA-DIAGNOSTIC-MODEL-USING-AN-ENSEMBLE-TRANSFER-LEARNING-MODEL

Pneumonia is a major infectious disease that affects the lungs, causing inflammation among **children** and **elderly people**.  
This creates a need to optimize medical diagnosis, as traditional approaches (such as manual image inspection, clinical evaluation, and examination) are not proactive or efficient enough for **early detection**.

Recent research has shown that **Artificial Intelligence (AI)** and **Deep Learning (DL)** algorithms are more robust in tackling this challenge, particularly by leveraging **Convolutional Neural Networks (CNNs)** and **Transfer Learning** models for medical diagnosis with high precision and accuracy.

---

## 🔹 Proposed Framework
This study proposes an **ensemble learning framework** that integrates the predictive power of pretrained models such as **VGG16** and **DenseNet121** for detecting **Pneumonia from Chest X-ray images** using a **weight-based strategy**.

---

## 🔹 Dataset
- **Public dataset** of **5,856 Chest X-ray images**  
  - Pneumonia: **3,883**  
  - Normal: **1,349**  

### Preprocessing Techniques:
- Image scaling  
- Data augmentation  
- Class weight allocation (to handle class imbalance)  

---

## 🔹 Methodology
- Base learners: **VGG16** and **DenseNet121**  
- Training and evaluation metrics:  
  - Accuracy  
  - Precision  
  - Recall  
  - F1-score  
  - Area Under the Curve (AUC)  

---

## 🔹 Results
- **VGG16**: Accuracy **94.55%**  
- **DenseNet121**: Accuracy **93.75%**  

Using a **weighted ensemble strategy** (based on a hyperbolic tangent function), the ensemble model achieved:  
- Accuracy: **95.19%**  
- Precision: **96.15%**  
- Recall: **96.15%**  
- F1-score: **96.15%**  
- AUC: **98.58%**  

---

## 🔹 Conclusion
The ensemble learning model **outperforms the individual base learners**, showing **higher precision, recall, and overall accuracy**.  
It also demonstrated **minimal misclassification error**, confirming the model’s capability in providing reliable and efficient **pneumonia diagnosis from Chest X-ray images**.
