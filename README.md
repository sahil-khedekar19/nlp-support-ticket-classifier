# NLP Support Ticket Classifier

An end-to-end NLP system that automatically classifies customer support tickets using email text and contextual metadata such as priority, queue, and tags.

Achieved **87% classification accuracy** using a multi-input deep learning model.

---

## Business Problem

Manual ticket classification is:

• Time consuming
• Error prone
• Not scalable

This system automates classification into:

* Incident
* Request
* Problem
* Change

---

## Project Architecture

Multi-Input Deep Learning Model:

Inputs:

* Email Text
* Priority
* Queue
* Tags

Output:

* Ticket Category

As shown in project architecture diagram (see screenshots folder)

---

## Tech Stack

Python
TensorFlow / Keras
Scikit-Learn
Pandas
NumPy
NLTK
Streamlit

---

## Machine Learning Pipeline

### Step 1: Data Preprocessing

* Text cleaning
* Lowercasing
* Remove special characters
* Tokenization

### Step 2: Feature Engineering

Text → Embedding Layer

Metadata Encoding:

* Queue → Label Encoding
* Priority → Ordinal Encoding
* Tags → MultiLabelBinarizer

### Step 3: Model

Multi-Input Neural Network

Components:

* Embedding Layer
* LSTM Layer
* Dense Layers
* Concatenation Layer

---

## Model Performance

Accuracy: **87%**

Detailed metrics:

Precision: 0.87
Recall: 0.87
F1-Score: 0.87

(Tested on 3268 samples)

(Source: Project evaluation results) 

---

## User Interface

Streamlit based web interface

User can:

• Enter ticket text
• Select priority
• Select queue
• Select tags

System predicts ticket category instantly

---

## How to Run Project

### Step 1

Clone repo

```
git clone https://github.com/yourusername/nlp-support-ticket-classifier
```

### Step 2

Install requirements

```
pip install -r requirements.txt
```

### Step 3

Run

```
streamlit run app/streamlit_app.py
```

---

## Project Highlights

Multi-Input Deep Learning

Real-world use case

Production ready structure

Web app included

---

## Future Improvements

• Use BERT
• Deploy on AWS
• Improve accuracy to 92%+

---

## Author

Sahil Khedekar

CDAC DBDA
AIR 204

LinkedIn: add link
