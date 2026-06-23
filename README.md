# Sentiment Analysis using BERT & DistilBERT
# Overview
This project demonstrates Sentiment Analysis using Transformer-based models from Hugging Face.
The project explores multiple approaches:

* Sentiment Analysis using Hugging Face Pipeline
* Sentiment Analysis using DistilBERT
* Sentiment Analysis using BERT
* Fine-Tuning BERT on a Custom Dataset
* Model Evaluation and Prediction

The objective is to classify text reviews into sentiment categories such as Positive and Negative using state-of-the-art Natural Language Processing (NLP) techniques.

# Technologies Used
* Python
* Pandas
* NumPy
* PyTorch
* Hugging Face Transformers
* Hugging Face Datasets
* Scikit-Learn
* Google Colab


# Project Files

| File                                       | Description                                    |
| ------------------------------------------ | ---------------------------------------------- |
| Sentiment_Analysis(Pipeline01).ipynb       | Sentiment Analysis using Hugging Face Pipeline |
| Sentiment_Analysis(Pipeline02).ipynb       | Advanced Pipeline-based Sentiment Analysis     |
| Sentiment_Analysis(Using Distilbert).ipynb | Sentiment Analysis using DistilBERT            |
| Sentiment_Analysis(BERT).ipynb             | BERT Fine-Tuning and Evaluation                |
| sentiment_data.csv                         | Dataset used for training and testing          |

# Models Used
Model Name:
distilbert-base-uncased-finetuned-sst-2-english

Features:
* Lightweight version of BERT
* Faster inference
* Pre-trained for sentiment analysis
* 
# BERT
Model Name:
bert-base-uncased

Features:
* Transformer-based architecture
* Fine-tuned on custom sentiment datasets
* High contextual understanding

# Workflow

Data Collection
↓
Data Preprocessing
↓
Train-Test Split
↓
Tokenization
↓
Input IDs & Attention Masks
↓
BERT / DistilBERT
↓
Training & Fine-Tuning
↓
Model Evaluation
↓
Sentiment Prediction

# Understanding the Training Process

The BERT model is trained using:

* BertTokenizer
* BertForSequenceClassification
* TrainingArguments
* Hugging Face Trainer API

Training Flow:

Review Text
↓
Tokenization
↓
BERT Prediction
↓
Loss Calculation
↓
Backpropagation
↓
Weight Update
↓
Model Learning

## Evaluation Metric
The project evaluates performance using:
* Accuracy Score

Formula:
Accuracy = Correct Predictions / Total Predictions






---

⭐ If you found this project useful, feel free to star the repository.

