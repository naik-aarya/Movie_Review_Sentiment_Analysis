# Movie Review Sentiment Analysis Using RNN, LSTM and GRU

## 1. Project Overview

This project focuses on performing sentiment analysis on movie reviews using Natural Language Processing (NLP) and Deep Learning techniques.

Three different Recurrent Neural Network architectures — Simple RNN, Long Short-Term Memory (LSTM), and Gated Recurrent Unit (GRU) — are implemented to classify movie reviews into two sentiment categories: Positive and Negative.

NLTK is used for text preprocessing, while TensorFlow and Keras are used to build, train, and evaluate the deep learning models.

The primary objective is to compare the performance of these architectures in understanding textual data and predicting sentiment.

## 2. Problem Statement

Movie reviews contain valuable information about audience opinions, experiences, and preferences. Manually analyzing large volumes of reviews is time-consuming and inefficient.

This project aims to develop an automated sentiment classification system that processes textual movie reviews and predicts whether the expressed sentiment is positive or negative using deep learning models.

## 3. Project Objectives

- Perform Exploratory Data Analysis (EDA) on movie review data.
- Clean and preprocess textual data using NLTK.
- Convert text into numerical sequences.
- Apply tokenization and padding techniques.
- Build Simple RNN, LSTM, and GRU architectures.
- Train and evaluate multiple deep learning models.
- Compare model performance using evaluation metrics.
- Predict sentiment for new movie reviews.

## 4. Dataset Description

The project uses a movie review dataset containing textual reviews and their corresponding sentiment labels.

**Target Classes:**

- Positive: Reviews expressing favourable opinions.
- Negative: Reviews expressing unfavourable opinions.

The dataset is used to train and evaluate binary sentiment classification models.

## 5. Technologies and Libraries Used

- **Programming Language:** Python
- **Data Manipulation:** NumPy, Pandas
- **Data Visualization:** Matplotlib, Seaborn
- **Natural Language Processing:** NLTK
- **Deep Learning:** TensorFlow, Keras
- **Machine Learning Utilities:** Scikit-learn

## 6. Natural Language Processing (NLP)

NLTK (Natural Language Toolkit) is used to perform text preprocessing and prepare movie reviews for deep learning models.

**Text Preprocessing Techniques:**

- Text Cleaning
- Lowercase Conversion
- Tokenization
- Stopword Removal
- Punctuation Removal
- Stemming / Lemmatization (if applied)
- Text-to-Sequence Conversion
- Padding

These preprocessing steps help transform raw textual reviews into structured numerical input suitable for neural networks.

## 7. Deep Learning Models

Three recurrent neural network architectures are implemented for sentiment classification.

### 7.1 Simple Recurrent Neural Network (RNN)

RNN is a neural network architecture designed to process sequential data. It maintains information from previous time steps to learn patterns and relationships within text sequences.

### 7.2 Long Short-Term Memory (LSTM)

LSTM is an advanced RNN architecture designed to capture long-term dependencies in sequential data.

It uses three main gates:

- Forget Gate
- Input Gate
- Output Gate

These gates control the flow of information and help address the vanishing gradient problem associated with traditional RNNs.

### 7.3 Gated Recurrent Unit (GRU)

GRU is a recurrent neural network architecture designed to capture sequential dependencies efficiently.

It uses two main gates:

- Update Gate
- Reset Gate

GRU has a simpler architecture than LSTM and can offer computational efficiency while maintaining strong performance on sequential tasks.

## 8. Project Workflow

1. Dataset Collection
2. Data Loading
3. Exploratory Data Analysis (EDA)
4. Text Cleaning and Preprocessing
5. Tokenization using NLTK
6. Stopword and Punctuation Removal
7. Text Sequence Conversion
8. Padding
9. Word Embedding
10. Simple RNN Model Development
11. LSTM Model Development
12. GRU Model Development
13. Model Compilation and Training
14. Model Evaluation
15. Performance Comparison
16. Sentiment Prediction

## 9. Model Evaluation

The models are evaluated using the following performance metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Training and Validation Loss

These metrics help assess classification performance and compare the effectiveness of RNN, LSTM, and GRU architectures.

## 10. Real-World Applications

- Movie Review Sentiment Analysis
- Customer Feedback Analysis
- Product Review Classification
- Social Media Sentiment Analysis
- Brand Reputation Monitoring
- Opinion Mining

## 11. Project Structure

```text
Movie-Review-Sentiment-Analysis/
│
├── README.md
├── requirements.txt
├── main.py
│
├── models/
│   ├── rnn_model.keras
│   ├── lstm_model.keras
│   └── gru_model.keras
│
└── images/
    ├── sentiment_distribution.png
    ├── model_accuracy_comparison.png
    └── model_loss_comparison.png
```

*Note: Include model and image files only if they are actually available in your repository.*

## 12. Installation and Execution

### Step 1: Clone the Repository

```bash
git clone https://github.com/naik-aarya/Movie-Review-Sentiment-Analysis.git
```

### Step 2: Navigate to the Project Directory

```bash
cd Movie-Review-Sentiment-Analysis
```

### Step 3: Install Required Libraries

```bash
pip install -r requirements.txt
```

### Step 4: Download Required NLTK Resources

Download the NLTK resources required by your preprocessing code.

```python
import nltk

nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
```

*Download only the resources required by your implementation. Depending on your NLTK version, additional tokenizer resources may be needed.*

### Step 5: Run the Python File

```bash
python main.py
```

## 13. Conclusion

This project demonstrates the application of Natural Language Processing and Deep Learning for automated movie review sentiment classification.

By implementing Simple RNN, LSTM, and GRU architectures, the project explores different approaches to learning sequential patterns and contextual information from textual data.

The comparison of these models provides practical insights into recurrent neural network architectures and their applications in real-world NLP problems.

---

**Author:** Aarya Naik

**GitHub:** https://github.com/naik-aarya
