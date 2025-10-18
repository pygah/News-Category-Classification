# News-Category-Classification
This project focuses on automatically classifying news articles into categories such as Business, Sports, Technology, and Politics using Natural Language Processing (NLP) and Machine Learning.The model is trained on the AG News dataset, which contains thousands of labeled news articles.
# 📰 AG News Text Classification

**A complete text classification project using NLP and machine learning to classify news articles into categories: World, Sports, Business, and Sci/Tech.**

---

## 🔹 Project Overview
This project demonstrates **end-to-end news classification** using the AG News dataset. It includes:
- Data loading from Google Drive
- Text preprocessing (cleaning, tokenization, lemmatization, stopword removal)
- Feature extraction using **TF-IDF**
- Classification with **Logistic Regression**
- Model evaluation with accuracy, classification report, and confusion matrix visualization

---

## 🛠️ Tech Stack & Libraries
- **Python 3.x**
- **Data Manipulation:** Pandas, Numpy
- **NLP:** NLTK
- **Machine Learning:** Scikit-learn (Logistic Regression)
- **Deep Learning (Optional):** TensorFlow/Keras
- **Visualization:** Matplotlib, Seaborn, WordCloud

---

## 📂 Dataset
- **Source:** AG News CSV dataset  
- **Columns:** `Class Index`, `Title`, `Description`  
- **Preprocessing:**  
  - Combined `Title` + `Description` into a single `Text` column  
  - Converted categories to: World, Sports, Business, Sci/Tech  
  - Removed rare labels (<2 samples)  
  - Cleaned text: lowercasing, removing special characters, tokenization, lemmatization, and stopword removal  

---

## ⚡ Key Steps
1. **Mount Google Drive** to access dataset  
2. **Load dataset** into a Pandas DataFrame  
3. **Preprocess text** for NLP  
4. **Split dataset** into train/test sets  
5. **TF-IDF vectorization** to convert text into numerical features  
6. **Train Logistic Regression model**  
7. **Evaluate model** using accuracy, classification report, and confusion matrix  

---

## 📊 Results (Sample)
- **Accuracy:** ~92% (depending on dataset version)  
- Confusion matrix visualizes correct vs. incorrect predictions  
- Classification report provides precision, recall, and F1-score for each category  

---

## 🚀 How to Run
1. Clone the repository:  
   ```bash
   git clone <your-repo-url>
