# Hotel Review Sentiment Analysis

This project performs sentiment analysis on hotel reviews using two different approaches:

- **VADER (Lexicon-based model)**
- **RoBERTa (Transformer-based deep learning model)**

The goal is to compare traditional rule-based sentiment analysis with a modern transformer model and evaluate their performance.

---

## 📌 Project Overview

Hotel review ratings were converted into sentiment labels:

- Rating ≥ 4 → Positive  
- Rating = 3 → Neutral  
- Rating < 3 → Negative  

These labels were used as ground truth to evaluate model predictions.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK (VADER)
- HuggingFace Transformers
- PyTorch

---

## 🤖 Models Used

### 1️⃣ VADER
- Lexicon-based sentiment analysis model
- Fast and lightweight
- Rule-based approach

### 2️⃣ RoBERTa
- `cardiffnlp/twitter-roberta-base-sentiment`
- Transformer-based deep learning model
- Context-aware and more accurate

---

## 📊 Results

| Model   | Accuracy |
|---------|----------|
| VADER   | 72.6%    |
| RoBERTa | 79.2%    |

RoBERTa outperformed VADER across:
- Accuracy
- Precision
- Recall
- F1-score

Transformer-based models showed stronger performance, especially in detecting negative and neutral sentiments.

---

## 📈 Visualizations

The project includes:
- True sentiment distribution
- Model prediction distributions
- Accuracy comparison bar chart
- Confusion matrices

These visualizations help analyze model behavior and classification performance.

---

## 📂 Project Structure
