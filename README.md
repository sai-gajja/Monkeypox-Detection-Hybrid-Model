# 🦠 Monkeypox Detection using Deep Learning  

This project focuses on building a deep learning model to detect **monkeypox and related diseases** from skin lesion images.  
The model combines **CNN, EfficientNetB3, Graph Neural Networks (GNN), and Channel Attention** for robust feature extraction and classification.  

---

## 📂 Dataset  

The dataset consists of skin lesion images across four categories:  

- 🐔 **Chickenpox** – 107 images  
- 🔴 **Measles** – 91 images  
- 🐵 **Monkeypox** – 279 images  
- ✅ **Normal** – 293 images  

Data augmentation techniques such as **rotation** and **zooming** were applied to balance and expand the dataset.  

---

## 🧠 Model Architecture  

The detection pipeline integrates multiple deep learning techniques:  

- **CNN** – for low-level feature extraction  
- **EfficientNetB3** – for powerful image classification backbone  
- **Channel Attention** – to focus on important features  
- **Graph Neural Network (GNN)** – to capture relational information across features  
- **Hybrid Fusion Layer** – combines CNN, EfficientNet, and GNN representations  
- **Explainability** – powered by **LIME** for interpretable predictions  

---

## ⚡ Training & Evaluation  

The model was trained with advanced callbacks including **LIME explanations**, **learning rate scheduling**, and **early stopping**.  

Evaluation metrics include:  

- 📉 **PR-AUC (Precision-Recall Area Under Curve)**  
- 📊 **Confusion Matrix**  
- 📑 **Classification Report** (Precision, Recall, F1-score)  

✅ Achieved **90% accuracy** on test data.  

---

## 🚀 Features  

- Multi-class classification of **skin lesion diseases**  
- Hybrid deep learning model with **explainability**  
- Training visualization & evaluation metrics  
- Dataset augmentation support for better generalization  

---

## 📦 Key Libraries  

- TensorFlow / Keras  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- Scikit-learn  
- LIME  

