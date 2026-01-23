# 🎬 Movie Genre Prediction using NLP

This project predicts the **genre of a movie** based on its **plot description** using Natural Language Processing (NLP) and Machine Learning techniques.

---

## 🚀 Overview
The project demonstrates an end-to-end NLP pipeline including text preprocessing, feature extraction using TF-IDF, and genre classification using a Naive Bayes model.

---

## 📂 Dataset
- **Source:** Kaggle
- **Format:** CSV
- **Columns:**
  - `Description` – Movie plot summary
  - `Genre` – Movie genre label

The dataset contains short, genre-indicative descriptions, making it suitable for text classification tasks.

---

## 🛠 Tech Stack
- Python
- Pandas
- NLTK
- Scikit-learn
- Jupyter Notebook / Google Colab

---

## 🧹 Text Preprocessing
- Converted text to lowercase  
- Removed punctuation and numbers  
- Removed stopwords  
- Applied lemmatization  
- Used simple tokenization  

---

## 🔢 Feature Extraction
- **TF-IDF Vectorizer**
  - Unigrams and bigrams
  - Converts text data into numerical features

---

## 🤖 Model
- **Multinomial Naive Bayes**
  - Well-suited for text classification
  - Efficient for high-dimensional sparse data

---

## 📊 Model Evaluation
The model achieved **high accuracy** due to strong genre-specific cues present in the dataset descriptions.  
A label-shuffle test confirmed that there was **no data leakage**, validating the correctness of the pipeline.

---

## 🧪 Sample Prediction
