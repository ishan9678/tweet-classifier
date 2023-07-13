# Natural Language Processing with Disaster Tweets

This repository contains my solution for the "Natural Language Processing with Disaster Tweets" Kaggle competition. The goal of the competition is to predict whether a given tweet is about a real disaster or not.

## Competition Overview
- Competition: [Natural Language Processing with Disaster Tweets](https://www.kaggle.com/c/nlp-getting-started)
- Description: Predict whether a given tweet is about a real disaster or not.
- Evaluation: Submissions are evaluated using F1 score between the predicted and the actual target.
- Data: The dataset consists of tweets that are labeled as either disaster or not disaster. It includes features like keyword, location, and text.

## Approach
1. Data Preprocessing: I performed several preprocessing steps on the data, including removing unnecessary columns, handling missing values, cleaning text, tokenizing, removing stopwords, and lemmatizing/stemming the text.
2. Feature Engineering: I used the TF-IDF (Term Frequency-Inverse Document Frequency) technique to convert the text data into numerical features.
3. Model Selection: I have used SVM.
4. Model Training: I trained the selected model on the preprocessed and feature-engineered data.
5. Model Evaluation: I evaluated the trained model using F1 score on the validation set to assess its performance.
6. Predictions: I made predictions on the test data using the trained model.
7. Submission: I created a submission file in CSV format with the tweet IDs and corresponding predictions.

## Results
- Accuracy: The final model achieved an accuracy of 80% on the validation set.
- Kaggle Submission: The model's predictions were submitted to the Kaggle competition for evaluation.

