# Task 1: News Topic Classifier Using BERT

## Objective

The objective of this project is to classify news headlines into predefined categories using the BERT transformer model. The model is fine-tuned on the AG News dataset to automatically identify the topic of a news article.

## Methodology / Approach

* Loaded the AG News dataset using Hugging Face Datasets.
* Performed text preprocessing and tokenization using BERT Tokenizer.
* Fine-tuned the pre-trained BERT model (bert-base-uncased) for text classification.
* Trained the model using Hugging Face Trainer API.
* Evaluated the model using Accuracy and F1-Score.
* Tested the model on unseen news headlines.

## Key Results / Observations

* Successfully fine-tuned a transformer-based model for news classification.
* Achieved strong classification performance on the AG News dataset.
* Demonstrated the effectiveness of transfer learning for NLP tasks.
* Learned practical implementation of tokenization, fine-tuning, and model evaluation.

## Technologies Used

* Python
* Hugging Face Transformers
* Datasets Library
* PyTorch
* Scikit-learn

## Skills Gained

* Natural Language Processing (NLP)
* Transformer Models
* BERT Fine-Tuning
* Text Classification
* Model Evaluation
