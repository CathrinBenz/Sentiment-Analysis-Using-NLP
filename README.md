# Sentiment-Analysis-Using-NLP
Sentiment Analysis using Natural Language Processing (NLP) and Machine Learning. Built with Python, NLTK, TF-IDF, and Multinomial Naive Bayes for classifying text sentiment.

##  Overview

This project implements a Sentiment Analysis system using Natural Language Processing (NLP) and Machine Learning to classify text into different sentiment categories. The workflow includes text preprocessing, feature extraction using TF-IDF, model training with Multinomial Naive Bayes, and evaluation of prediction performance.

---

##  Features

- Text preprocessing and cleaning
- Stopword removal
- Tokenization
- Lemmatization using NLTK
- TF-IDF feature extraction
- Sentiment classification using Multinomial Naive Bayes
- Model evaluation with accuracy and classification report

---

## Project Architecture

```
Input Text
      │
      ▼
Text Cleaning
(Remove URLs, Punctuation, etc.)
      │
      ▼
Tokenization
      │
      ▼
Stopword Removal
      │
      ▼
Lemmatization
      │
      ▼
TF-IDF Vectorization
      │
      ▼
Multinomial Naive Bayes
      │
      ▼
Predicted Sentiment
```

---

##  Technologies Used

- Python
- Pandas
- NLTK
- Scikit-learn
- TF-IDF Vectorizer
- Multinomial Naive Bayes

---

##  Installation

```bash

cd Sentiment-Analysis-Using-NLP

pip install -r requirements.txt
```

---

##  Usage

1. Load the dataset.
2. Preprocess the text.
3. Perform tokenization and lemmatization.
4. Convert text into TF-IDF features.
5. Train the Multinomial Naive Bayes model.
6. Predict sentiment for new text samples.

---

##  Project Structure

```
Sentiment-Analysis-Using-NLP/

│── SENTIMENTAL ANALYSIS PROJECT.ipynb
│── README.md
│── requirements.txt
│── dataset/
│── images/
```

---

##  Results

- Cleaned and preprocessed text data.
- Extracted features using TF-IDF.
- Classified text sentiment using Multinomial Naive Bayes.
- Evaluated model performance using accuracy and classification metrics.

---

## Future Enhancements

- Deep Learning with LSTM/Bi-LSTM
- BERT-based sentiment analysis
- Real-time Twitter sentiment analysis
- Web application using Streamlit
- Multi-class sentiment classification

