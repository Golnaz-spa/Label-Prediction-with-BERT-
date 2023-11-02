# BERT - Label Prediction

## About

Welcome to the BERT Label Prediction project. This project utilizes BERT (Bidirectional Encoder Representations from Transformers), a pre-trained deep learning model developed by Google for natural language processing (NLP) tasks. BERT is based on the transformer architecture, a powerful neural network design that excels in processing sequential data by selectively attending to different parts of the input sequence.

## Project Purpose

In this project, we leverage BERT to predict top-level labels for code review comments and questions. The primary goal is to classify each question into one of five categories:
- Suggestion
- Requests
- Attitudes and emotions
- Hypothetical scenario
- Rhetorical questions

To achieve this, we use the "Question" column in the dataset as the independent feature for the model. The target variable is the "top-level label," representing the category to which the question belongs.

## BERT Overview

BERT operates by encoding the input sequence (in this case, the code review comment question) into a vector representation. This encoding is accomplished by passing the input through multiple layers of the transformer architecture. After encoding the input sequence, the model performs a classification task to predict the most likely top-level label for the given question. This is achieved using a softmax function, which assigns probabilities to each category based on the encoded input representation.

## Project Details

- Pre-trained BERT model is used for fine-tuning.
- Python and PyTorch are used for the project's implementation.
- The code includes training, evaluation, and prediction functions.
- Data preprocessing is performed to prepare the dataset for training.

## Data

The dataset used in this project contains code review comments and questions with corresponding top-level labels. The "Question" column serves as the primary input feature for the BERT model.

## Model Training

To train the model, the code review comment questions are tokenized, and the resulting tokens are used as input to the BERT model. The model is fine-tuned on the labeled data to optimize for the classification task.

## Usage

To utilize this project for label prediction, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/your-username/bert-label-prediction.git
cd bert-label-prediction
