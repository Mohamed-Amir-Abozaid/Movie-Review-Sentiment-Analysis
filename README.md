# Movie Review Sentiment Analysis

Binary sentiment classification on IMDB movie reviews using Machine Learning.

---

## Project Overview

This project aims to classify movie reviews as **positive** or **negative** based on their textual content.
It follows a clean, production-style machine learning pipeline with proper project structure.

---

## Dataset

- **Source:** IMDB Movie Reviews Dataset  
- **Size:** 50,000 reviews  
- **Classes:** Positive / Negative (balanced)

Dataset is located in:
/data


---

## Project Structure

Sentiment_Classifier/
│
├── data/
│   └── IMDB_Dataset.csv
│
├── notebooks/
│   ├── 01_eda_and_cleaning.ipynb
│   ├── 02_feature_engineering_and_training.ipynb
│   └── 03_model_evaluation.ipynb
│
├── models/
│   ├── Sentiment_Classifier_v1/
│   └── Sentiment_Classifier_v2/
│
├── experiments/
│   └── test_models.ipynb
│
├── utils/
│   └── preprocessing.py
│
│
├── README.md



---

## Methodology

### 1. Exploratory Data Analysis
- Sentiment distribution
- Review length analysis

### 2. Text Preprocessing
- HTML tag removal
- Lowercasing
- Punctuation & number removal
- Stopword removal
- Lemmatization

### 3. Feature Engineering
- TF-IDF Vectorization

### 4. Model Training
- Logistic Regression (baseline)
- Support Vector Machine (experiments)

### 5. Evaluation
- Precision, Recall, F1-score
- Confusion Matrix

---

## Results

- The dataset is perfectly balanced (50% positive / 50% negative)
- Baseline Logistic Regression achieved strong F1-score performance
- Detailed evaluation is available in `03_model_evaluation.ipynb`

---





