# 🎬 Sentiment Analysis on IMDB Movie Reviews

## 📌 Project Overview
This project performs **Sentiment Analysis** on movie reviews using **Natural Language Processing (NLP)** techniques.  
The model classifies a given movie review as **Positive** or **Negative** based on learned patterns from the IMDB dataset.

---

## 📂 Dataset
**IMDB Dataset of 50K Movie Reviews**

- Total reviews: 50,000
- Columns:
  - `review` → Movie review text
  - `sentiment` → positive / negative

Dataset Source: Kaggle

---

## 🧠 Technologies Used
- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorizer
- Naive Bayes Classifier

---

## ⚙️ How It Works
1. Load IMDB movie reviews dataset
2. Convert text data into numerical form using **TF-IDF**
3. Split data into training and testing sets
4. Train a **Naive Bayes** classifier
5. Predict sentiment for user-entered reviews

---

## ▶️ How to Run the Project

### 1️⃣ Install dependencies
```bash
pip install -r requirements.txt
