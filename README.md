# Sentiment Analysis of TripAdvisor Hotel Reviews
This is a repository for the Sentiment Analysis of TripAdvisor Hotel Reviews project.

## Abstract

Performing sentiment analysis on hotel reviews can help companies understand the guest experience. In this project, three models- Logistic Regression, BiLSTM and a pre-trained DistilBERT model- are implemented to classify reviews from a TripAdvisor hotel dataset as negative, neutral or positive sentiment. For the Logistic Regression model, TF-IDF was used to transform the text into numerical features. GloVe was used to generate the embedding matrix for the BiLSTM model, while a pre-trained tokenizer was used to generate the contextual embeddings for the DistilBERT model. The results showed that the DistilBERT model performed best with the highest accuracy and macro F1 score, indicating that a pre-trained transformer can enhance sentiment classification tasks.
