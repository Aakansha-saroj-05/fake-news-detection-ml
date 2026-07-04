# 📰 Fake News Detection using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?logo=scikitlearn)
![NLP](https://img.shields.io/badge/NLP-TF--IDF-green)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Project Overview

Fake news has become a major challenge in today's digital world. This project uses **Natural Language Processing (NLP)** and **Machine Learning** to automatically classify news articles as **Fake** or **Real**.

The project demonstrates the complete machine learning workflow, including data preprocessing, text cleaning, feature extraction, model training, evaluation, and prediction.

---

## 🎯 Objectives

- Build a machine learning model to classify fake and real news.
- Apply Natural Language Processing techniques for text preprocessing.
- Convert text into numerical features using TF-IDF.
- Train and evaluate a Logistic Regression classifier.
- Save the trained model for future predictions.

---

## 📂 Dataset

This project uses the **Fake and Real News Dataset** consisting of two CSV files:

- **Fake.csv**
- **True.csv**

Each news article contains:

- Title
- Text
- Subject
- Date

After preprocessing:

- Fake News → Label **0**
- Real News → Label **1**

> **Note:** The dataset is not included in this repository due to its size. You can download it from Kaggle.

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Scikit-learn
- WordCloud
- Joblib

---

## 🧠 Machine Learning Workflow

```
Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Text Preprocessing
      │
      ▼
Tokenization
      │
      ▼
Stopword Removal
      │
      ▼
Lemmatization
      │
      ▼
TF-IDF Vectorization
      │
      ▼
Train-Test Split
      │
      ▼
Logistic Regression
      │
      ▼
Model Evaluation
      │
      ▼
Prediction
```

---

## ✨ Features

- Data Cleaning
- Missing Value Analysis
- Exploratory Data Analysis
- Text Preprocessing
- Tokenization
- Stopword Removal
- Lemmatization
- TF-IDF Feature Extraction
- Logistic Regression Model
- Accuracy Evaluation
- Classification Report
- Confusion Matrix
- Word Cloud Visualization
- News Prediction Function
- Model Saving using Joblib

---

## 📊 Model Performance

The Logistic Regression model achieved excellent performance on the testing dataset.

Evaluation Metrics include:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

> Replace this section with your actual accuracy after training.

Example:

```
Accuracy: 98.96%
```

---

## 📷 Project Screenshots

### Dataset Distribution

<img width="748" height="515" alt="image" src="https://github.com/user-attachments/assets/e26213db-c4dd-4449-83ca-a6c06b9b5098" />


---

### Confusion Matrix

<img width="662" height="582" alt="image" src="https://github.com/user-attachments/assets/2d5f79de-7657-4f9d-90b5-01fed5a8a1a8" />


---

### Fake News Word Cloud

<img width="721" height="383" alt="image" src="https://github.com/user-attachments/assets/b86127ce-20d4-4202-a472-05bb511b50df" />


---

### Real News Word Cloud

<img width="720" height="387" alt="image" src="https://github.com/user-attachments/assets/f7f392b0-afeb-419e-a7e5-7e04bce5afb0" />


---

## 📁 Repository Structure

```
fake-news-detection-ml
│
├── Fake_News_Detection.ipynb
├── README.md
├── requirements.txt
├── fake_news_model.pkl
├── tfidf_vectorizer.pkl
└── images
```

---

## 🚀 How to Run

### Clone Repository

```bash
git clone https://github.com/your-username/fake-news-detection-ml.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Open Notebook

Run:

```
Fake_News_Detection.ipynb
```

---

## 🔮 Future Improvements

- Compare multiple Machine Learning models.
- Deploy the model using Streamlit.
- Add Deep Learning models (LSTM/BERT).
- Create a web interface for real-time prediction.

---

## 👩‍💻 Author

**Aakansha Saroj**

B.Tech Electronics & Communication Engineering (AI)

Indira Gandhi Delhi Technical University for Women (IGDTUW)

GitHub: https://github.com/Aakansha-saroj-05

LinkedIn: https://www.linkedin.com/in/aakansha-saroj-120a46329

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
