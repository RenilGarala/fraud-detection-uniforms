# 📞 Fraud Call Detection using Machine Learning

## 📌 Project Overview
This project is built to demonstrate how machine learning can be applied to detect **fraudulent calls**, such as cases where criminals impersonate police officers or law enforcement officials.  

The notebook implements the process using **Google MediaPipe Model Maker** with a structured dataset. It explains the end-to-end workflow from dataset preparation to prediction.

---

## 🔗 Dataset  
You can access the dataset here:  
👉 [Dataset Drive Link](https://drive.google.com/drive/folders/1XV5dJNpaLuMQoz83429dXNOKfi07-r6J?usp=share_link)

---



## 🔧 Block Diagram (Conceptual Flow)

**System Flow:**
1. **Dataset Collection** → Gather fraud and genuine call samples.  
2. **Data Preprocessing** → Clean and prepare data for training.  
3. **Feature Extraction** → Use MediaPipe to generate embeddings.  
4. **Model Training** → Train classifier on fraud vs genuine samples.  
5. **Evaluation** → Validate the trained model.  
6. **Prediction** → Classify new/unseen samples as Fraud or Genuine.  

---

## ⚡ Code Flow Explanation

1. **Import Libraries**  
   - Load all required libraries (TensorFlow, MediaPipe, NumPy, etc.).

2. **Dataset Loading**  
   - Dataset organized into folders:
     ```
     dataset/
       ├── Uniform/
       │   ├── test/
       │   └── train/
     ```

3. **Preprocessing**  
   - Normalization and data preparation.  
   - Train/validation/test splits created.

4. **Model Training**  
   - Model built using MediaPipe Model Maker.  
   - Classification head trained to distinguish between **fraud** and **genuine**.

5. **Prediction**  
   - The trained model is used to make predictions on unseen data.  

---
