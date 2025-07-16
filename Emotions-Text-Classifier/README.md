# 🔍 Emotion Text Classifier

Welcome to a **Natural Language Processing (NLP)** project that dives deep into the realm of **text emotion classification**. This project leverages the power of **Python**, **machine learning**, and **NLP techniques** to analyze and classify emotions embedded in textual data.

Using a semicolon-separated dataset (`Dataset/train.txt`), we unravel the emotional undertones of human language and build intelligent models capable of understanding sentiment at scale. From data preprocessing to model evaluation, this project showcases a complete pipeline for emotion detection in text.

---

## 🧰 Technologies & Libraries

- Python
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

---

## 📊 Results

- The model achieves high accuracy on the validation set.
- It performs well in predicting emotions across various input types.
- The solution is ready for deployment in:
  - NLP pipelines  
  - Emotion-aware chatbots  
  - User sentiment dashboards 
