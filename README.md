# spam-news-project
A Machine Learning Project that classsifies news as spam or Legitimate using python
# Spam News Detection using Machine Learning

This project classifies news articles as **Spam** or **Legitimate** using Machine Learning.  
Built in **Python** using **Google Colab**.

## Overview
- Preprocesses text (cleaning, stopwords removal)
- Converts text to vectors using **TF-IDF**
- Trained using **Logistic Regression**
- Evaluates using accuracy, confusion matrix, and classification report

## Dataset
File: `news.csv`  
Columns:
- text → news content  
- label → 0 (Legit), 1 (Spam)

## How to Run
1. Open `Spamnews_project.ipynb` in Google Colab  
2. Upload `news.csv`  
3. Run all cells  
4. Test with:
```python
model.predict(vectorizer.transform(["your text here"]))
Technologies Used

Python, Pandas, NumPy, Scikit-learn, NLTK, TF-IDF, Google Colab

Files

Spamnews_project.ipynb – main notebook

README.md – project summary

LICENSE – MIT License
Author

Jayasimha Vardhan

