 Fake News Prediction System

## 📌 Overview

The **Fake News Prediction System** is a Machine Learning mini project that classifies news content as **REAL** or **FAKE** using Natural Language Processing (NLP) techniques.

This project helps in detecting misinformation and understanding how ML models can be applied to text classification problems.

---

## 🎯 Objectives

* Predict whether a news article is **Real or Fake**
* Reduce misinformation spread
* Learn practical implementation of NLP & ML

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* NLP (TF-IDF Vectorization)

---

## 📂 Project Structure

```
Fake-news-prediction-system/
│── data/
│   └── news.csv
│── model/
│   └── model.pkl
│── train.py
│── predict.py
│── main.py
│── README.md
```

---

## ⚙️ Working Process

1. Load dataset with news text
2. Clean and preprocess the data
3. Convert text into numerical features using TF-IDF
4. Train model using Machine Learning algorithm
5. Predict news as REAL or FAKE

---

## ▶️ How to Run

### 1. Install Requirements

```
pip install pandas numpy scikit-learn
```

### 2. Train Model

```
python train.py
```

### 3. Run Project

```
python main.py
```

---

## 💻 Example

**Input:**

```
India successfully launched Chandrayaan-3 mission to the Moon to study the lunar surface.
```

**Output:**

```
🟢 Real News
```

---

**Input:**

```
NASA confirmed that aliens are living inside the Moon.
```

**Output:**


🔴 Fake News

## 📊 Features

* Simple and beginner-friendly project
* Uses Machine Learning for prediction
* Command-line interface
* Easy to extend

## 🚀 Future Scope

* Improve accuracy using advanced models (BERT, LSTM)
* Add GUI (Tkinter / Web App)
* Real-time news detection API

## 📚 Learning Outcomes

* Text preprocessing
* Feature extraction using TF-IDF
* Model training and evaluation
* Building ML projects in Python

## 📌 Conclusion

This project demonstrates how Machine Learning can be used to detect fake news and classify textual data effectively.


