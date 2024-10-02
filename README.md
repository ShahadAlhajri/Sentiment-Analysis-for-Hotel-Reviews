
# Sentiment Analysis of Hotel Reviews



## Introduction

Sentiment analysis is a crucial aspect of natural language processing (NLP) that captures public opinion, particularly in the hospitality industry. This project focuses on classifying hotel review sentiments as positive or negative, providing valuable insights into customer satisfaction and service improvement.



## Data Collection

The dataset used for this analysis comprises **20,491 hotel reviews** sourced from Trip Advisor, available on Kaggle. Each review is annotated for sentiment classification, categorized into positive and negative sentiments based on ratings from 1 to 5.



## Data Preprocessing

The preprocessing steps involved:

- **Cleaning**: Ensured data integrity by checking for duplicates and missing values.

- **Tokenization and Lowercasing**: Split the text into tokens and standardized them to lowercase.

- **Stop Words and Punctuation Removal**: Removed common words and punctuation that do not contribute to sentiment.

- **Stemming and Lemmatization**: Reduced words to their base forms for clarity and efficiency.



## Feature Extraction

We utilized three primary methods for converting text data into numerical features:

1. **TF-IDF (Term Frequency-Inverse Document Frequency)**: Emphasizes unique terms in the reviews.

2. **Bag of Words (BoW)**: Represents the frequency of words without considering their order.

3. **n-Grams**: Considers sequences of words, capturing more context.



## Model Selection

Multiple machine learning models were evaluated, including:

- **Logistic Regression**: Achieved the highest accuracy of **96.27%**, making it the best performing model for sentiment analysis.

- **Naive Bayes Classifier**

- **Random Forest**

- **Gradient Boosting Machines**



Logistic Regression was selected due to its high accuracy, interpretability, and computational efficiency.



## Model Evaluation

The evaluation metrics used include:

- **Accuracy**: Overall accuracy of **96%**.

- **Precision**: 0.97 for negative and 0.96 for positive sentiments.

- **Recall**: 0.96 for negative and 0.97 for positive sentiments.

- **F1-Score**: Balanced at 0.96 for both classes.



## Conclusion

This project demonstrates the effectiveness of sentiment analysis in classifying hotel reviews, highlighting the practical utility of machine learning models in understanding customer feedback. The methodologies applied offer a robust framework for enhancing customer satisfaction and service quality in the hospitality sector.
