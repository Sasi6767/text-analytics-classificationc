# Logistic Regression Based Text Classification

## Overview
This project implements and compares two supervised text classification approaches using Logistic Regression. The objective is to evaluate traditional NLP feature extraction against transformer-based embeddings for document classification tasks.

The project demonstrates an end-to-end text analytics pipeline including preprocessing, feature extraction, model training, evaluation, and result generation.

## Models Implemented
- **Model 1:** TF-IDF Vectorization with Logistic Regression  
- **Model 2:** BERT Tokenization using CLS Embeddings with Logistic Regression  

## Dataset
- `test.csv`  
Contains preprocessed text data used for generating final predictions.

> Note: Dataset content is anonymised and used for academic and experimental purposes.

## Methodology
- Text cleaning and preprocessing
- TF-IDF feature extraction
- BERT-based text embedding (CLS token)
- Logistic Regression model training
- Evaluation across train, validation, and test splits
- Automated saving of prediction outputs

## Tools & Technologies
- Python
- pandas, NumPy
- scikit-learn
- transformers (BERT)
- PyTorch

## Project Structure
├── text_classification_logistic_regression.ipynb   # Main notebook with models and evaluation
├── test.csv                                       # Input dataset for prediction
└── README.md                                     # Project documentation
                        


---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Sasi6767/text-analytics-classification.git



## Author
Sasikumar Venkatesan — MSc Data Science


