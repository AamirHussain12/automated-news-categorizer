# 📰 Automated News Categorizer (NLP)

This project builds a **News Categorization system** using classical NLP techniques to automatically classify news articles into predefined categories. It also explores **topic modeling** to uncover hidden themes in the data.

---

## 🚀 Project Overview

The goal of this project is to:

- Classify news articles into categories (multi-class classification)
- Extract meaningful patterns from text data
- Explore both **supervised learning** and **unsupervised topic modeling**

---

## 🧠 Techniques Used

### 🔹 Supervised Learning (Classification)
- Text preprocessing (cleaning, tokenization, normalization)
- Feature extraction using **TF-IDF**
- Models:
  - Logistic Regression
  - Naive Bayes

---

### 🔹 Unsupervised Learning (Topic Modeling)
- **Latent Dirichlet Allocation (LDA)**
  - Discovers hidden topics in news articles
  - Helps understand underlying structure of text data

---

## 📂 Dataset

- News articles dataset with labeled categories
- Each sample contains:
  - `Text` → News content  
  - `Category` → Target label  

---

## 🧹 Data Preprocessing

- Lowercasing text  
- Removing punctuation  
- Removing stopwords  
- Tokenization  
- Text normalization  

---

## 🔤 Feature Engineering

- **TF-IDF (Term Frequency–Inverse Document Frequency)**  
  Converts text into numerical features for model training

---

## 🤖 Models Used

- Logistic Regression  
- Naive Bayes  

---

## 📊 Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1-score  

---

## 📈 Results

- Achieved strong baseline performance using TF-IDF + simple models  
- Model performance varied across categories due to data imbalance  
- LDA provided useful insights into hidden topics within the dataset  

---

## 🧠 Key Learnings

- Data preprocessing has a major impact on performance  
- TF-IDF is a powerful baseline for text classification  
- Simpler models can perform well with good features  
- Difference between:
  - **Text Classification** (predict labels)
  - **Topic Modeling** (discover hidden themes)

---

## 🛠️ Tech Stack

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- NLTK  
- Gensim (for LDA)  

---

## ▶️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/AamirHussain12/automated-news-categorizer.git
cd automated-news-categorizer
