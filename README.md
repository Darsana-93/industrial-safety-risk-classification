# Industrial Safety Risk Classification using NLP

This project involves building a machine learning pipeline to assess and classify industrial safety incident reports based on their risk levels using natural language processing (NLP) techniques.

---

## 📌 Problem Statement

Accurately identifying and classifying the severity of industrial incidents is critical for safety compliance and risk mitigation. This project automates the risk classification process using AI, enabling faster and more consistent safety reporting.

---

## 🧠 Solution Overview

- Collected and preprocessed raw incident reports using NLP
- Applied TF-IDF vectorization to convert textual data into numerical features
- Built classification models using Logistic Regression, SVM, Random Forest
- Evaluated models using precision, recall, F1-score, and ROC-AUC
- Ensured interpretability using SHAP analysis

---

## 🧰 Tools & Technologies Used

- **Python 3.9**
- **Pandas, NumPy, Scikit-learn**
- **Matplotlib, Seaborn**
- **TF-IDF (from scikit-learn)**
- **Jupyter Notebook / Google Colab**

---

## 🔎 Key Features

- **NLP Preprocessing**: Tokenization, lowercasing, stopword removal, TF-IDF
- **Multi-class Classification**: Low, Medium, High risk levels
- **Model Tuning**: GridSearchCV for hyperparameter optimization
- **Explainability**: SHAP plots to visualize feature importance

---

## 📊 Results

- Best performance from **Random Forest Classifier**
 
## 📂 Project Structure

industrial-safety-risk-classification/
│
├── README.md                       # Project overview and documentation
├── notebook.ipynb                  # Jupyter Notebook with full code and analysis

---

## 📈 Future Work

- Deploy model using Flask/Streamlit for real-time predictions
- Explore BERT or other transformer models for improved NLP performance
- Integrate with workplace safety dashboards (e.g., Power BI)

---

## 👩‍💻 Author

**Darsana Bordoloi**  
Master of Data Science (Global), Deakin University  
LinkedIn: www.linkedin.com/in/darsana-bordoloi-970a9314a  
Email: bordoloi.darsana29@gmail.com

---
