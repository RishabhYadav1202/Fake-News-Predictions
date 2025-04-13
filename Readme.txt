# 📰 Fake News Detection using NLP & Machine Learning

In today's digital world, fake news can spread rapidly and cause real damage. This project aims to detect fake news articles using Natural Language Processing and classic ML models.

---

## 📌 Project Highlights
- Cleaned and preprocessed ~20,000 articles
- Applied stemming and stopword removal
- Used TF-IDF for feature extraction
- Trained 3 ML models (Logistic Regression, Naive Bayes, SVM)
- Achieved **99.27% accuracy** with **LinearSVC**
- Visualized model explanations using **SHAP**

---

## 🧪 Models Compared

| Model               | Accuracy | Precision | Recall | F1 Score |
|--------------------|----------|-----------|--------|----------|
| **LinearSVC**       | 99.27%   | 99.51%    | 99.04% | 99.27%   |
| Logistic Regression | 98.97%   | 98.85%    | 99.09% | 98.97%   |
| Multinomial NB      | 95.43%   | 99.27%    | 91.55% | 95.25%   |

---

## 📊 Visuals
- Class Distribution
- WordCloud of Common Words
- Confusion Matrices
- ROC-AUC Curve
- SHAP Summary Plot

<p align="center">
  <img src="images/shap_summary.png" width="600">
</p>

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- NLTK
- SHAP
- Matplotlib, Seaborn

---

## 🚀 Future Work
- Deploy using Streamlit
- Try Deep Learning models (LSTM, BERT)
- Integrate with real-time news API

---

## 🧠 Learnings
- NLP pipeline from scratch
- Model tuning via GridSearchCV
- Explainable AI with SHAP

---

## 📁 Dataset
[News Dataset (Kaggle)](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)

---

## 📌 Author
[Your Name](https://www.linkedin.com/in/your-profile)

---

## 📝 License
MIT License
