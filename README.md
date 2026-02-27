# 🎫 NLP Support Ticket Classifier

<p align="center">

🚀 Deep Learning based Context-Aware Ticket Classification System

🏆 Achieved **87% Accuracy** | 🤖 Multi-Input Neural Network | 🌐 Streamlit Web App

</p>

---

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-DeepLearning-orange?logo=tensorflow)
![Scikit-Learn](https://img.shields.io/badge/ScikitLearn-ML-yellow?logo=scikit-learn)
![Streamlit](https://img.shields.io/badge/Streamlit-WebApp-red?logo=streamlit)
![Status](https://img.shields.io/badge/Status-ProductionReady-brightgreen)

</p>

---

# 📌 Overview

This project is an **End-to-End NLP System** that automatically classifies customer support tickets using:

* 📧 Email Text
* ⚡ Priority
* 🏢 Queue
* 🏷️ Tags

into predefined categories:

* Incident
* Request
* Problem
* Change

This eliminates manual effort and improves operational efficiency.

---

# 💼 Business Impact

Manual ticket classification is:

❌ Time-Consuming
❌ Error-Prone
❌ Not Scalable

✅ This system automates classification instantly
✅ Improves support team productivity
✅ Enables faster response time

---

# 🧠 Model Architecture

## Multi-Input Deep Learning Model

### Inputs:

* Email Text → Embedding + LSTM
* Priority → Encoded Features
* Queue → Label Encoding
* Tags → Multi-Label Encoding

### Output:

🎯 Ticket Category Prediction

📊 See architecture diagram in **screenshots folder**

---

# ⚙️ Tech Stack

| Category         | Tools             |
| ---------------- | ----------------- |
| Language         | Python            |
| Deep Learning    | TensorFlow, Keras |
| Machine Learning | Scikit-Learn      |
| NLP              | NLTK              |
| Data Processing  | Pandas, NumPy     |
| Web App          | Streamlit         |

---

# 🔬 Machine Learning Pipeline

## 1️⃣ Data Preprocessing

✔ Text Cleaning
✔ Lowercasing
✔ Special Character Removal
✔ Tokenization

---

## 2️⃣ Feature Engineering

| Feature  | Method              |
| -------- | ------------------- |
| Text     | Embedding Layer     |
| Queue    | Label Encoding      |
| Priority | Ordinal Encoding    |
| Tags     | MultiLabelBinarizer |

---

## 3️⃣ Model

Neural Network Layers:

* Embedding Layer
* LSTM Layer
* Dense Layers
* Concatenation Layer
* Output Layer

---

# 📊 Model Performance

🎯 Accuracy: **87%**
📦 Tested on **3268 real support tickets**

---

# 🌐 Web Application

Built using **Streamlit**

## Features:

✔ User enters ticket text
✔ Select metadata
✔ Instant prediction

📸 See UI in screenshots folder

---

# 🚀 How to Run

## Clone Repository

```bash
git clone https://github.com/yourusername/nlp-support-ticket-classifier
```

---

## Install Requirements

```bash
pip install -r requirements.txt
```

---

## Run Application

```bash
streamlit run app/streamlit_app.py
```

---

# ⭐ Key Highlights

✅ Multi-Input Deep Learning Model

✅ Real-World Dataset

✅ Production-Ready Structure

✅ Web Application Interface

✅ Resume-Level Project

---

# 🔮 Future Improvements

🚀 BERT Integration

☁️ AWS Deployment

📈 Improve Accuracy to 92%+

🌍 Multi-Language Support

---

# 👨‍💻 Author

**Sahil Khedekar**

🎓 CDAC DBDA
🏆 AIR 204

🔗 LinkedIn
https://linkedin.com/in/sahil-khedekar1908

🔗 GitHub
https://github.com/sahil-khedekar19

---

# ⭐ If you found this useful, consider giving it a star!
