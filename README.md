# SMS Spam Detection System using Machine Learning

## Project Overview

SMS spam messages have become a common issue, often containing advertisements, phishing links, or fraudulent content. This project develops an intelligent SMS Spam Detection System using Machine Learning and Natural Language Processing (NLP) techniques to classify SMS messages as either spam or ham (non-spam).

The system converts textual data into numerical representations and applies classification techniques to accurately detect unwanted messages. Different feature extraction methods were analyzed to identify the best-performing approach.

---

## Problem Statement

Spam SMS messages can negatively affect user experience and may contain malicious content. Manual filtering becomes inefficient as message volume increases. This project aims to automate spam detection by building a machine learning model capable of accurately classifying incoming SMS messages.

---

## Dataset Information

**Dataset Used:** SMS Spam Dataset

### Target Categories

| Label | Description |
|---------|-------------|
| Ham | Legitimate SMS messages |
| Spam | Unwanted or promotional messages |

### Dataset Distribution

| Category | Percentage |
|-----------|------------|
| Ham | 86.6% |
| Spam | 13.4% |

Observation:

The dataset shows class imbalance because legitimate messages significantly outnumber spam messages.

---

## Key Highlights

### Text Processing

- Applied Natural Language Processing techniques for SMS analysis
- Converted text data into machine-readable representations
- Prepared raw text for classification tasks

### Feature Extraction

Implemented two text vectorization methods:

- CountVectorizer
- TF-IDF Vectorizer

### Model Development

- Implemented K-Nearest Neighbors (KNN)
- Trained multiple configurations
- Compared model performance across feature extraction methods

### Performance Insights

- Achieved high prediction accuracy
- Compared vectorization approaches
- Identified the best-performing model

---

## Technologies Used

| Category | Tools |
|-----------|-------|
| Programming Language | Python |
| Development Environment | Jupyter Notebook |
| Libraries | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-Learn |
| NLP | CountVectorizer, TF-IDF |

---

## Project Workflow

### Step 1: Data Collection

- Imported SMS spam dataset

### Step 2: Data Preparation

- Separated features and labels
- Performed class distribution analysis

### Step 3: Train-Test Split

Dataset division:

- Training Data → 80%
- Testing Data → 20%
- Random State → 42

Purpose:

- Training data used for model learning
- Testing data used for performance evaluation

### Step 4: Feature Engineering

Applied:

**CountVectorizer**
- Converts text into word-frequency vectors

**TF-IDF Vectorizer**
- Assigns weighted importance to words

### Step 5: Model Training

Implemented:

**K-Nearest Neighbors (KNN)**

Two configurations:

1. CountVectorizer + KNN
2. TF-IDF + KNN

### Step 6: Model Evaluation

Compared model performance using:

- Training Accuracy
- Testing Accuracy
- Prediction analysis

---

## Performance Results

### Model Comparison

| Model Configuration | Training Accuracy | Testing Accuracy |
|---------------------|------------------|------------------|
| CountVectorizer + KNN | 97.3% | 96.8% |
| TF-IDF + KNN | 92.0% | 91.6% |

---

## Best Performing Model

CountVectorizer with K-Nearest Neighbors achieved the highest testing accuracy of:

# 96.8%

This model demonstrated superior capability in identifying spam messages.

---

## Future Improvements

- Hyperparameter tuning
- Deep learning-based text classification
- Advanced NLP preprocessing techniques
- Real-time SMS spam detection system
- Web application deployment using Flask or Streamlit

---

## Author

**Vinnakota Nitish Raj**

LinkedIn: Your LinkedIn Profile URL
