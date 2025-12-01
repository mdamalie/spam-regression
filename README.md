# Spam Detection Using Logistic Regression

This project builds a spam detection model using **Logistic Regression** to classify text messages as *spam* or *ham*. The workflow includes data cleaning, text preprocessing, TF-IDF feature extraction, model training, and evaluation using standard machine learning metrics.

---

## 📌 Project Summary
- Uses a labeled SMS dataset (`spam.csv`)
- Converts text into numerical vectors using **TF-IDF**
- Trains a **Logistic Regression** classifier with scikit-learn
- Evaluates performance using accuracy and classification metrics
- Fully implemented in a Jupyter Notebook

---

## ⚙️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Jupyter Notebook  

---

## 📁 Dataset
The dataset `spam.csv` contains two main columns:
- **text** — message content  
- **label** — spam or ham  

Ensure `spam.csv` is located in the project folder.

---

## 🚀 How to Run
Install dependencies:
```bash
pip install scikit-learn pandas numpy
