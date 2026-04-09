# 📰 Fake News Detection System

##  Overview

This project is an intelligent **Fake News Detection System** that classifies news articles as **Real** or **Fake** using Machine Learning and Natural Language Processing (NLP) techniques.

The system also integrates **real-time news fetching** and provides **model explainability** using LIME, making predictions transparent and interpretable.

---

##  Objectives

* Detect fake news using machine learning
* Improve classification accuracy using preprocessing techniques
* Provide explainability for predictions
* Fetch and analyze real-time news articles


##  Tech Stack

###  Programming Language

* Python

###  Libraries & Tools

* Scikit-learn (ML models)
* Pandas & NumPy (Data processing)
* TextBlob (Sentiment analysis)
* TF-IDF Vectorizer (Feature extraction)
* SMOTE (Class balancing)
* LIME (Explainable AI)
* NewsAPI (Real-time news fetching)

---

##  Methodology

### 1. Data Preprocessing

* Text cleaning (removing punctuation, stopwords)
* Lowercasing and normalization
* Tokenization

### 2. Feature Extraction

* TF-IDF Vectorization to convert text into numerical features

### 3. Handling Imbalanced Data

* SMOTE (Synthetic Minority Oversampling Technique)

### 4. Model Training

* Logistic Regression classifier

### 5. Model Evaluation

* Accuracy, Precision, Recall, F1-score

### 6. Explainability

* LIME used to interpret predictions

### 7. Real-Time Integration

* Fetch news articles using NewsAPI
* Classify them as Fake or Real

---

## Features

*  Detect fake vs real news
*  Real-time news classification
*  Explainable predictions using LIME
*  Handles imbalanced datasets
*  Scalable and modular pipeline

---

##  Project Structure

```
fake-news-detection/
│── notebook.ipynb
│── README.md
│── requirements.txt
│── data/
```

---

## How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/fake-news-detection.git
cd fake-news-detection
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Notebook

* Open `notebook.ipynb` in Jupyter or Colab
* Execute all cells

Results

* Achieved high accuracy using Logistic Regression
* Improved performance with SMOTE
* LIME provides clear explanations for predictions

--- Example Use Case

1. Input a news article or headline
2. System processes and vectorizes the text
3. Model predicts whether it's **Fake** or **Real**
4. LIME explains which words influenced the prediction

 Future Enhancements

* Add Deep Learning models (LSTM, BERT)
* Deploy as a web application
* Integrate speech-to-text for live news detection
* Improve real-time streaming capabilities



 Author

**Abhiram Aravind**

-
