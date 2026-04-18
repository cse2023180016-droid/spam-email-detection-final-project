# Spam Email Detection using Machine Learning

## 1. Project Overview
This project is a comparative study of different Machine Learning algorithms applied to the task of **Spam Email Detection**. Using a dataset of over 5,000 emails, we developed a system that classifies messages as either "Spam" or "Ham" (legitimate). This project was completed as part of the Machine Learning course final requirements.

**Problem Statement:** Binary Classification (Spam vs. Ham).

---

## 2. Team Members & Individual Contributions
To ensure a fair distribution of work, each member implemented a unique algorithm and contributed to the pipeline:

* **Tann Sievmey**: Initial Data Exploratory Analysis (EDA), Text Preprocessing (Stopword removal, Stemming), and implementation of the **Naive Bayes** algorithm.
* **V. Ly Komapich**: Feature Engineering using TF-IDF Vectorization and implementation of **Support Vector Machine (SVM)** with hyperparameter tuning via GridSearchCV.
* **Leng Moniraksmey**: Implementation of the **Random Forest** algorithm, performance metric visualization (Confusion Matrices, ROC Curves), and final comparative analysis.

---

## 3. Dataset
* **Source:** [Kaggle - Spam Mails Dataset](https://www.kaggle.com/datasets/venky73/spam-mails-dataset)
* **Description:** The dataset consists of email text and a corresponding label (1 for spam, 0 for ham).

---

## 4. Methodology
The project follows a standard ML pipeline:
1.  **Data Cleaning:** Lowercasing, removing special characters, and filtering stopwords.
2.  **Vectorization:** Converting text to numerical data using **TF-IDF (Term Frequency-Inverse Document Frequency)**.
3.  **Model Training:** Training three distinct models to find the most efficient classifier.
4.  **Evaluation:** Comparing models based on Accuracy, Precision, Recall, and F1-Score.

---

## 5. Comparative Performance Results
| Algorithm | Accuracy | Precision | Recall | F1-Score |
| :--- | :--- | :--- | :--- | :--- |
| **Naive Bayes** | 97.2% | 0.94 | 0.92 | 0.93 |
| **SVM** | 98.1% | 0.98 | 0.91 | 0.94 |
| **Random Forest** | 96.5% | 0.99 | 0.85 | 0.91 |

---
