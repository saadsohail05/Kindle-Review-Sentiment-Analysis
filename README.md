
# Kindle Reviews Sentiment Analysis

## Introduction
The Kindle Reviews Sentiment Analysis project aims to analyze user reviews for Kindle products and classify their sentiments based on star ratings. By employing natural language processing (NLP) techniques, this project seeks to extract valuable insights from the textual data, helping stakeholders understand customer sentiments and improve product offerings.

## Usage
To use this project, ensure you have the dataset (`all_kindle_review.csv`) in the same directory as your Jupyter Notebook. Open the notebook and execute the cells sequentially. The notebook performs data loading, preprocessing, visualization, and model training to classify sentiments.

### Example
After running the notebook, you can see visualizations of ratings and obtain accuracy metrics of the sentiment classification model.

## Features
- **Data Visualization**: Generates plots for rating distributions.
- **Text Preprocessing**: Cleans the review text by removing URLs, HTML tags, punctuations, chat words, emojis, and stopwords.
- **Sentiment Classification**: Utilizes Naive Bayes classifiers with Bag of Words and TF-IDF for sentiment analysis.
- **Model Evaluation**: Provides accuracy scores and confusion matrices to assess model performance.

## Data
The dataset used in this project is sourced from Kindle user reviews, stored in a CSV file named `all_kindle_review.csv`. The data includes two columns: `reviewText` (the review content) and `rating` (the associated star rating). The project preprocesses the text data to improve analysis accuracy.

## Methodology
The project follows these main steps:
1. **Data Loading**: Imports the review dataset.
2. **Text Preprocessing**: Implements various cleaning techniques including:
   - Lowercasing
   - URL removal
   - HTML tag removal
   - Punctuation removal
   - Chat word replacement
   - Spelling correction
   - Stopword removal
   - Emoji removal
   - Lemmatization
3. **Model Training**: Splits the data into training and testing sets, then vectorizes the text using Count Vectorizer and TF-IDF Vectorizer.
4. **Model Evaluation**: Trains a Naive Bayes classifier and evaluates its performance based on accuracy and confusion matrices.

## Results
The project presents key findings, including:
- The accuracy of the Naive Bayes model using Bag of Words and TF-IDF.
- Visual representations of the distribution of ratings, which provide insights into customer sentiments.

## Conclusion
The Kindle Reviews Sentiment Analysis project demonstrates the effectiveness of NLP techniques in sentiment classification. The insights derived from the analysis can guide product improvements and enhance customer satisfaction.

