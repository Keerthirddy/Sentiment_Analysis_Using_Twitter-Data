Sentiment Analysis on Twitter Data

Overview
This project focuses on performing sentiment analysis on Twitter data to classify tweets as positive or negative. The goal is to preprocess the text data, train various machine learning models, and evaluate their performance to determine the best model for sentiment classification.

Literature Survey
The literature survey covers various methodologies and techniques used in sentiment analysis, particularly on social media platforms like Twitter. It includes a review of existing algorithms, preprocessing techniques, and the challenges associated with sentiment analysis in short text messages.

Project Structure
The project is structured as follows:

Data Collection: Gathered tweets using Twitter API.(Sentiment140 dataset with 1.6 million tweets-kaggle)
Data Preprocessing: Cleaned and prepared the data for analysis.
Model Training and Evaluation: Trained multiple machine learning models and evaluated their performance.
Results and Conclusion: Identified the best-performing model and tested it on sample text.
Preprocessing
The preprocessing steps involved:

Cleaning the Text Data: Removing URLs, special characters, and irrelevant information.
Tokenization: Splitting text into individual words.
Stemming and Lemmatization: Reducing words to their root forms.
Removing Stopwords: Eliminating common words that do not contribute to sentiment.
Machine Learning Models
Three different machine learning models were trained and tested:

Naive Bayes
Support Vector Machine (SVM)
Logistic Regression
Performance Evaluation
The performance of each model was evaluated based on accuracy. The Logistic Regression model achieved the highest accuracy of 82%.

Sample Text Classification
The Logistic Regression model was further tested with sample texts to classify them as positive or negative sentiments. The results demonstrated the model's effectiveness in sentiment classification.

Conclusion
The project successfully implemented sentiment analysis on Twitter data, with the Logistic Regression model providing the best performance. This model can be used for real-time sentiment analysis on new Twitter data.
