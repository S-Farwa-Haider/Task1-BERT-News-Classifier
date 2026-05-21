# Task 1: BERT News Classifier

## Problem Statement

News websites publish a huge number of articles every day. Manually organizing news into categories is difficult and time-consuming.

This project uses BERT to automatically classify news headlines into topic categories.

---

## Objective

Build a transformer-based text classification model using BERT and classify news headlines into categories using Natural Language Processing (NLP).

Evaluate model performance using:
- Accuracy
- F1 Score

---

## Dataset Used

Dataset Name:
AG News Dataset

Source:
Hugging Face Datasets

Categories:
- World
- Sports
- Business
- Science / Technology

---

## Methodology / Approach

### Step 1 — Dataset Loading
Loaded AG News dataset using Hugging Face.

### Step 2 — Text Preprocessing
- Tokenization
- Padding
- Truncation

### Step 3 — Model Development
Loaded pre-trained BERT model.

Model:
- bert-base-uncased

### Step 4 — Model Training
Fine-tuned BERT using Trainer API.

### Step 5 — Evaluation
Measured performance using:
- Accuracy
- F1 Score

### Step 6 — Prediction
Tested model using sample news headlines.

---

## Technologies Used

- Python
- Transformers
- Hugging Face
- NumPy
- Google Colab

---

## Skills Gained

- NLP
- Transformers
- Transfer Learning
- Fine-Tuning
- Text Classification
- Model Evaluation

---

## Results / Observations

- Successfully implemented news classification
- Learned tokenization and preprocessing
- Fine-tuned transformer model
- Evaluated using classification metrics

---

## Conclusion

This project demonstrated how BERT can be fine-tuned for news topic classification using transformer-based NLP techniques.
