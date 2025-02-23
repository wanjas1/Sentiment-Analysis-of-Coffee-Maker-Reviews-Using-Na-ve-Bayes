# Sentiment-Analysis-of-Coffee-Maker-Reviews-Using-Na-ve-Bayes

![coffee maker2](https://github.com/user-attachments/assets/0283f565-870f-4b4b-96b7-e7a7fa8e7add)

Photo by <a href="https://unsplash.com/@jakubzerdzicki?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Jakub Żerdzicki</a> on <a href="https://unsplash.com/photos/a-coffee-maker-is-making-a-cup-of-coffee-A_90G6Ta56A?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>
      
Project Overview

Customer sentiment is a key driver of brand perception and product improvement. DeLonghi, a coffee maker manufacturer, wants to gain deeper insights into customer feedback by identifying negative reviews effectively. While overall sentiment analysis is valuable, prioritizing the accurate detection of negative sentiment is crucial for addressing customer concerns and improving product satisfaction.

The challenge lies in:

> Accurately classifying customer reviews as positive or negative based on textual feedback.

> Ensuring high precision in detecting negative reviews to minimize false positives.

> Evaluating model effectiveness beyond accuracy, with a focus on precision and recall for negative sentiment.

This project aims to build a Naïve Bayes-based sentiment classification model that helps DeLonghi effectively detect and analyze negative reviews, enabling data-driven product and service improvements.

Objectives

> Load and preprocess customer reviews from the coffee_maker.csv dataset.

> Perform data cleaning, handling missing values, and converting ratings into a binary sentiment classification (negative vs. positive).

> Train and evaluate a Multinomial Naïve Bayes model for sentiment classification.

> Assess model performance with key evaluation metrics, prioritizing those that highlight the model’s effectiveness in detecting negative reviews.

Methodology

i.) Data Preparation

> Convert ratings (1-3) to negative sentiment (0) and ratings (4-5) to positive sentiment (1).

> Explore class distribution to check for class imbalance.

ii.)  Feature Engineering & Model Training

> Tokenize and convert text data into a TF-IDF-weighted Document-Term Matrix.

> Split data into 70% training and 30% test sets for model validation.

> Train a Multinomial Naïve Bayes model using a Scikit-learn pipeline.

iii.) Model Evaluation

> Precision & Recall (especially for negative sentiment).

> F1-score, Accuracy, and ROC-AUC Score to assess overall classification performance.

Results & Conclusion

The trained Naïve Bayes model performed well, achieving:

> Accuracy: 85%

> ROC AUC Score: 0.93, indicating strong ability to distinguish between positive and negative sentiment.

> Precision (Negative Sentiment): 0.92, meaning a high proportion of correctly identified negative reviews.

> Recall (Negative Sentiment): 0.70, suggesting some missed negative reviews, but overall good sensitivity.

Despite a slight class imbalance, the model is effective for sentiment analysis and provides valuable insights into customer feedback, helping DeLonghi identify areas for product improvement.

 
