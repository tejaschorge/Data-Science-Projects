# 🧠 Emotion Text Classifier

This project classifies text into human emotions (joy, sadness, fear, anger, surprise, love) using machine learning and NLP techniques. It demonstrates a full pipeline from preprocessing to model training and prediction.

---

## 📌 Project Overview

- **Goal:** Predict emotions from raw input text using deep learning.
- **Dataset:** Provided in `dataset/train.txt` with text and emotion labels.
- **Problem Type:** Multiclass classification (6 emotions).
- **Tools Used:** Python, TensorFlow/Keras, Scikit-learn, Pandas, NumPy.

---

## 🧰 Technologies & Libraries

- Python 3.11
- TensorFlow / Keras
- Scikit-learn
- Pandas, NumPy
- Jupyter Notebook

---

## 🔄 Workflow

1. **Data Loading:** Read `train.txt`, separate text and emotion labels.
2. **Preprocessing:**
   - Tokenization and padding of text
   - Label encoding and one-hot encoding
3. **Model Building:**
   - Embedding layer
   - Dense + Flatten layers
4. **Training:** Model trained for 10 epochs with validation.
5. **Prediction:** Predicts emotion from new user input text.
