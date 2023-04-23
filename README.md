# Label-Prediction-with-BERT
BERT - Label Prediction
BERT (Bidirectional Encoder Representations from Transformers) is a pre-trained deep learning model developed by Google for natural language processing (NLP) tasks. 
The model is based on the transformer architecture, which is a type of neural network that processes sequential data by selectively attending to different parts of
the input sequence.

In the given project, BERT is being used to predict the top-level labels for code review comments questions. The goal is to classify each question into one of five 
categories: Suggestion, Requests, Attitudes and emotions, Hypothetical scenario, and Rhetorical questions. To do this, the "Question" column in the dataset is used 
as the independent feature for the model. The target variable is the "top-level label," which is the category that the question belongs to. The BERT model works by 
first encoding the input sequence (in this case, the code review comment question) into a vector representation. This encoding is done by passing the input through 
multiple layers of the transformer architecture. Once the input sequence is encoded, the model then performs a classification task by predicting the most likely 
top-level label for the given question. This is done using a softmax function, which assigns a probability to each category based on the encoded input representation.
