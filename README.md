# Movie Genre Classification 

##  Project Overview
This project was developed during my Machine Learning Internship at CodSoft. It is a Natural Language Processing (NLP) text classification model designed to automatically predict a movie's genre based entirely on its plot summary.

Working with text data presents unique challenges compared to standard numerical datasets. This repository demonstrates my ability to clean and preprocess unstructured text, extract meaningful numerical features using text vectorization, and train a multi-class machine learning model.

##  Key Highlights
* **Text Preprocessing:** Built a robust pipeline to clean raw movie plots by removing stopwords, special characters, and applying text normalization techniques to prepare the data for the model.
* **Feature Engineering:** Utilized **TF-IDF** (Term Frequency-Inverse Document Frequency) to transform the unstructured text data into meaningful numerical vectors, highlighting the most important words for genre prediction.
* **Model Training:** Trained and evaluated a **Logistic Regression** model capable of multi-class classification, successfully categorizing movies into their respective genres based on the weighted text features.

##  Tech Stack
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Natural Language Processing:** NLTK / SpaCy, Regular Expressions (Regex)
* **Machine Learning & Vectorization:** Scikit-Learn (TF-IDF Vectorizer)
