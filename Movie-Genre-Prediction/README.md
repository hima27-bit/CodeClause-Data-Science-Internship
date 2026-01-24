🎬 Movie Genre Prediction using NLP
📌 Project Overview

This project aims to predict the genre of a movie based on its plot description using Natural Language Processing (NLP) techniques and machine learning. By analyzing textual patterns in movie descriptions, the model classifies movies into appropriate genres.

🎯 Aim

To build a machine learning model that predicts the genre of a movie using its plot summary.

📝 Description

The project uses NLP techniques to preprocess movie plot descriptions and converts them into numerical features using TF-IDF vectorization. A Naive Bayes classifier is trained on these features to predict the genre of a movie. The model is evaluated using accuracy and classification metrics, and it also supports custom user input for genre prediction.

🛠 Technologies Used

Python

Google Colab

NLTK

Scikit-learn

Pandas, NumPy

📂 Dataset

File name: movie_genre.csv

Columns used:

Description – Movie plot summary

Genre – Movie genre label

⚙️ Methodology

Loaded and explored the dataset

Cleaned and preprocessed text data (lowercasing, punctuation removal, stopword removal)

Converted text into numerical features using TF-IDF

Split data into training and testing sets

Trained a Naive Bayes classification model

Evaluated model performance

Tested the model using custom movie descriptions

📊 Results

The model achieved high accuracy on the test dataset.

Successfully predicted genres for unseen movie plot descriptions.

📚 Learning Outcomes

Understanding of text preprocessing techniques

Feature extraction using TF-IDF

Implementation of text classification models

Practical experience with NLP pipelines

✅ Conclusion

This project demonstrates how NLP and machine learning can be effectively used for text classification tasks such as movie genre prediction. The model performed well due to clear textual patterns in the dataset and appropriate feature extraction techniques.
