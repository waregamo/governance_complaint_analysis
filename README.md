# 🧠 Governance Complaint Sentiment Analyzer

A machine learning project that applies **Natural Language Processing (NLP)** and **Supervised Learning** techniques to analyze and classify citizen complaints related to governance issues.

## 🌍 SDG Alignment: SDG 16 — Peace, Justice and Strong Institutions

The project contributes to **SDG 16** by enabling faster, data-driven insights from citizen feedback. It empowers institutions to identify and act on emerging public concerns, fostering transparency and justice.

---

## 🎯 Objective

Use **sentiment analysis** and **machine learning classification** to:

- Detect **positive** vs **negative** sentiments in governance related complaints.
- Provide a tool to inform policymakers and institutions about areas of concern.
- Demonstrate how AI can assist in institutional feedback systems.

---

## 🧪 ML Approach Used

- **Natural Language Processing (NLP)** with `TextBlob` for sentiment scoring.
- **TF-IDF vectorization** for text features.
- **Logistic Regression Classifier** for supervised binary sentiment classification.

---

## 📊 Dataset

- A CSV file of real-world governance complaints (complaints_processed.csv).
- Text fields preprocessed for punctuation, stop words, and lowercasing.

---

## ⚙️ Tools & Libraries

- Python
- Pandas
- TextBlob
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 🔁 Workflow

1. **Data Cleaning**: Removed punctuation, converted to lowercase, removed stopwords.
2. **Sentiment Analysis**: Used TextBlob to assign polarity scores.
3. **Labeling**: Polarity > 0 → Positive (1), else Negative (0).
4. **Vectorization**: TF-IDF applied to cleaned text.
5. **Training**: Logistic Regression model trained to classify sentiments.
6. **Evaluation**: Model evaluated using accuracy score and confusion matrix.

---

## 📌 Results

- Achieved good accuracy in predicting sentiments.
- Most complaints showed negative polarity, suggesting dissatisfaction with services.
- Potential for real-world use by governments to understand citizen sentiment trends.

---

## 🧠 Ethical & Social Reflection

- **Bias**: Model relies on TextBlob, which may have bias in handling local languages or context-specific expressions.
- **Sustainability**: Automating analysis reduces manual review overhead and improves institutional responsiveness.

---

## Project Screenshots

### 📉 Sample Output


--

## Team Members
1. warega moses  waregamoses20@gmail.com
2. Sheila Wambui muriukisheila33@gmail.com
3. Bopaki Shaku  bopakishaku@gmail.com
4. Mathew Siya   mattewsiyabonga@gmail.com
5. Dancan Jeff   danjeff254@gmail.com
6. Kazeem Bello  kazeembello5088@gmail.com