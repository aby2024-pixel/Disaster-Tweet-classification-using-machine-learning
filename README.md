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


---

## 🧠 Models Implemented

### 1️⃣ Baseline Model
- **TF-IDF Vectorization**
- **Logistic Regression**


---

### 2️⃣ Transformer Models

#### 🔹 DistilBERT
- Pretrained: `distilbert-base-uncased`
- Tokenization with max length = 128
- Multiple experiments with:
  - Learning rates
  - Batch sizes
  - Epochs

#### 🔹 BERT
- Pretrained: `bert-base-uncased`
- Fine-tuned on dataset
- Uses HuggingFace Trainer API

---

## ⚙️ Training Details

- Train/Validation split: **80/20**
- Stratified sampling used
- Evaluation per epoch

---

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC (baseline)

*(Replace with your actual results from notebooks)*

---

## 🧪 Experiments

- Compared traditional ML vs transformer models
- Tuned hyperparameters:
  - Learning rate
  - Batch size
  - Epochs
- Observed performance improvements using transformers

---

## 📂 Project Structure

├── project-update-1.ipynb # Initial experiments
├── ProjectUpdate2.ipynb # Advanced models (BERT, DistilBERT)
├── train.csv # Training dataset
├── test.csv # Test dataset
├── README.md


---

## ▶️ How to Run

### 1. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn transformers torch
