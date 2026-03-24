# 🧠 Disaster Tweet Classification using ML & Transformers

This project builds a **text classification system** to identify whether a tweet is related to a real disaster or not.

It compares:
- Traditional Machine Learning models (TF-IDF + Logistic Regression)
- Transformer-based Deep Learning models (DistilBERT, BERT)

---

## 🚀 Project Overview

Social media platforms like Twitter are often used during emergencies. This project aims to automatically classify tweets into:

- **Disaster (1)** → Real emergency-related tweet  
- **Non-Disaster (0)** → Normal or irrelevant tweet  

The project demonstrates a full NLP pipeline from preprocessing to advanced transformer models.

---

## 🛠️ Tech Stack

- **Python**
- **Pandas, NumPy**
- **Scikit-learn**
- **Matplotlib, Seaborn**
- **HuggingFace Transformers**
- **PyTorch**

---

## 📊 Dataset

- Training data: `train.csv`
- Test data: `test.csv`

Typical dataset features:
- `text` → Tweet content  
- `target` → Label (0 or 1)

---

## 🧹 Data Preprocessing

- Lowercasing text
- Removing:
  - URLs
  - Mentions (@user)
  - Hashtags
  - Special characters
  - Extra spaces

Example:
