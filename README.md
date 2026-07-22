# 📧 Spam Mail Prediction System

A **Spam Mail Prediction System** built with **Python** and **Scikit-learn** that classifies emails as **Spam** or **Ham (Legitimate)** using Natural Language Processing (NLP) and Machine Learning techniques.

The project demonstrates the complete machine learning workflow, from data preprocessing and feature extraction to model training, evaluation, and prediction.

---

## 🚀 Features

- Classifies emails as **Spam** or **Ham**
- Text preprocessing and cleaning
- TF-IDF feature extraction
- Logistic Regression classifier
- Model evaluation using accuracy score
- Predicts custom email messages

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression
- Jupyter Notebook

---

## 📂 Project Structure

```
Spam-Mail-Prediction-System/
│
├── notebook.ipynb          # Model development and training
├── mail_data.csv           # Email dataset
└── README.md
```

---

## 📊 Dataset

The dataset contains email messages labeled as:

- **Spam** – Unwanted or promotional emails.
- **Ham** – Legitimate emails.

Each email consists of:

- Email Category
- Email Message

---

## ⚙️ Machine Learning Workflow

1. Load the dataset.
2. Clean and preprocess the data.
3. Convert labels into numerical values.
4. Split the dataset into training and testing sets.
5. Transform text using **TF-IDF Vectorizer**.
6. Train a **Logistic Regression** model.
7. Evaluate the model using accuracy.
8. Predict whether new email messages are spam or legitimate.

---

## 💻 Installation

Clone the repository:

```bash
git clone https://github.com/Ibragoran10/Spam-Mail-Prediction-System.git

cd Spam-Mail-Prediction-System
```

Install the required libraries:

```bash
pip install pandas numpy scikit-learn
```

---

## ▶️ Run the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
notebook.ipynb
```

Run all cells to train the model and test predictions.

---

## 📈 Model

- **Algorithm:** Logistic Regression
- **Feature Extraction:** TF-IDF Vectorizer
- **Task:** Binary Text Classification
- **Output:** Spam or Ham

---

## 🔮 Future Improvements

- Build a Streamlit web application
- Deploy the model using Streamlit Community Cloud
- Try advanced NLP models such as Naive Bayes and Support Vector Machine (SVM)
- Improve text preprocessing with stemming and lemmatization
- Display prediction confidence scores

