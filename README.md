# Legal Document Classification Using NLP

## Overview
This project applies Natural Language Processing (NLP) techniques to classify legal documents based on their textual content. The goal is to demonstrate how machine learning can analyze unstructured legal text and automatically categorize documents such as Non-Disclosure Agreements (NDAs), employment contracts, and lease agreements.

The project builds a machine learning pipeline that converts raw legal text into numerical features and trains a classification model to predict document type.

---

## Problem Statement
Legal organizations handle large volumes of documents that must be reviewed and categorized. Manually organizing these documents is time-consuming and inefficient.

This project explores how NLP can be used to automatically identify the type of legal document based on its language and structure.

---

## Dataset
For demonstration purposes, the dataset consists of sample legal text snippets representing common legal document categories, including:

- Non-Disclosure Agreements (NDA)
- Employment Agreements
- Lease Agreements
- General Contracts

Each document is labeled with its corresponding document type.

---

## Methodology

The NLP pipeline includes the following steps:

1. Text preprocessing
2. Feature extraction using TF-IDF vectorization
3. Training a classification model
4. Evaluating prediction accuracy

Text data is transformed into numerical feature vectors using TF-IDF and then used to train a classification model.

---

## Model

The classification model was implemented using logistic regression from  
:contentReference[oaicite:1]{index=1}.

The model learns patterns in legal language that correspond to different document types.

---

## Results

The trained model can successfully classify legal text into document categories. Example prediction:

Input text:
"This agreement protects confidential information between two parties."

Predicted document type:
NDA

---

## Tools & Libraries

- Python
- pandas
- :contentReference[oaicite:2]{index=2}
- TF-IDF Vectorization

---

## Example Workflow

1. Load legal document text
2. Convert text to TF-IDF features
3. Train classification model
4. Predict document type for new text

---

## Future Improvements

Possible extensions for this project include:

- Using larger legal document datasets
- Implementing deep learning NLP models
- Extracting key legal clauses automatically
- Adding named entity recognition for legal entities

---

## Author

Machine learning and NLP portfolio project demonstrating document classification using natural language processing techniques.
