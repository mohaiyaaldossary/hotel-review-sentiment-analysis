# Hotel Review Sentiment Analysis

This project performs sentiment analysis on hotel reviews using two different approaches:

- **VADER (Lexicon-based model)**
- **RoBERTa (Transformer-based deep learning model)**

The goal of this project is to compare a traditional rule-based sentiment analysis method with a modern transformer-based model and evaluate their performance.

---

## 📌 Project Overview

Hotel review ratings were converted into sentiment labels:

- Rating ≥ 4 → Positive  
- Rating = 3 → Neutral  
- Rating < 3 → Negative  

These labels were used as ground truth to evaluate model predictions.

---

## 📂 Dataset

**Datafiniti Hotel Reviews Dataset**

Source: Kaggle  
https://www.kaggle.com/datasets/datafiniti/hotel-reviews

The dataset contains hotel review texts along with numerical ratings.  
Ratings were transformed into sentiment categories (positive, neutral, negative) for evaluation purposes.

Note: The dataset is not included in this repository due to size limitations. Please download it directly from Kaggle.

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

### VADER
- Lexicon-based sentiment analysis model  
- Fast and lightweight  
- Rule-based approach  

### RoBERTa
- `cardiffnlp/twitter-roberta-base-sentiment`  
- Transformer-based deep learning model  
- Context-aware and more accurate  

---

## 📊 Results

| Model   | Accuracy |
|---------|----------|
| VADER   | 72.6%    |
| RoBERTa | 79.2%    |

RoBERTa outperformed VADER across accuracy, precision, recall, and F1-score.  
The transformer-based model showed stronger performance, especially in detecting negative and neutral sentiments.

---

## 📈 Visual Analysis

The project includes:

- True sentiment distribution  
- Model prediction distributions  
- Accuracy comparison visualization  
- Confusion matrices  

These visualizations provide insights into model behavior and classification performance.

---

## 📌 Conclusion

This project demonstrates:

- Data preprocessing and cleaning  
- Sentiment label engineering  
- Comparison between lexicon-based and transformer-based models  
- Model evaluation using classification metrics  
- Data visualization for performance analysis  

The results highlight the advantage of transformer-based NLP models in understanding contextual sentiment compared to rule-based approaches.
