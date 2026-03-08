# Legal Document Classification Using NLP

## Overview
This project applies Natural Language Processing (NLP) techniques to classify legal documents based on their textual content. The goal is to demonstrate how machine learning can analyze unstructured legal text and automatically categorize documents such as Legal Demands, Letters of Protection (LOPs), Non-Disclosure Agreements (NDAs), employment contracts, and lease agreements.

The project builds a machine learning pipeline that converts raw legal text into numerical features and trains a classification model to predict document type.

---

## Problem Statement
Legal organizations often handle a large volume of documents that must be reviewed and categorized. Manually organizing these documents is time-consuming and inefficient.

This project explores how NLP can be used to automatically identify the type of legal document based on its unique language and structure.

---

## Dataset
In this prokect, we create a sample dataset that consists of sample legal text "snips" that represent common legal document categories, including:

- Legal Demands
- Non-Disclosure Agreements (NDA)
- Letters of Protection (LOPs)
- Employment Agreements
- Lease Agreements
- General Contracts

Each document is labeled with its corresponding document type.

---

## Natural Language Processing Methodology

The NLP pipeline includes the following steps:

1. Text preprocessing
2. Feature extraction using TF-IDF vectorization
3. Training a classification model
4. Evaluating prediction accuracy

Text data is transformed into numerical feature vectors using TF-IDF and then used to train a classification model.

---

## Model

The classification model is implemented using logistic regression from  
:contentReference[oaicite:1]{index=1}.

The model learns patterns in legal language that correspond to different document types.

---

## Results
 
The trained model, with enough data, can successfully classify legal text into document categories. 

Example prediction:

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

This project can be improved in a couple of key ways:

The most apparent improvement would be the model's accuracy. Right now, our model's accuracy is 0.0. This is may be due to the small dataset that we have given it. By increasing the dataset from which the model can learn and be evaluated from, we can improve the accuracy. 

Additionally, we could also use deep learning NLPs more suitable for smaller datasets, or we could add more detailed or robust data to improve the accuracy. 



---

## Author

Machine learning and NLP portfolio project demonstrating document classification using natural language processing techniques.
