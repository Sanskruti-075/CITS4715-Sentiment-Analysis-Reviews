# 💬 Sentiment Analysis of Reviews

## Intern Details
| Field | Details |
|---|---|
| **Intern ID** | CITS4715 |
| **Full Name** | Sanskruti Vijay Gulghane |
| **Organization** | Codtech IT Solutions Pvt. Ltd. |
| **Domain** | Artificial Intelligence |
| **No. of Weeks** | 4 Weeks |
| **Internship Period** | 14 June 2026 – 12 July 2026 |

---

## 📌 Project Name
**Sentiment Analysis of Reviews**

## 📋 Project Scope
Analyze customer product reviews and classify their sentiment as **Positive**, **Negative**, or **Neutral** using NLP techniques — specifically TF-IDF vectorization and **Logistic Regression**. Useful for businesses to understand customer feedback at scale.

---

## 🛠️ Technologies Used
- Python 3.x
- NumPy & Pandas
- Matplotlib & Seaborn
- Scikit-learn (TF-IDF + Logistic Regression)

---

## 📂 Project Structure
```
sentiment/
├── sentiment_analysis.py          # Main Python script
├── sentiment_distribution.png     # EDA output
├── sentiment_confusion_matrix.png # Evaluation output
└── README.md
```

---

## ▶️ How to Run
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
python sentiment_analysis.py
```

---

## 📊 Output
- Sentiment distribution bar chart (Positive / Neutral / Negative)
- Model accuracy and full classification report
- Confusion matrix heatmap
- Live predictions on 5 custom reviews with emoji labels

---

## 🔍 Algorithm
**Logistic Regression** with **TF-IDF Vectorizer** for multi-class text classification. Stratified train-test split (80/20) used to preserve class balance.
