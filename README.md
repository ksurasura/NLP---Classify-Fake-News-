# Capstone 2: NLP - Classify Fake News

### Determine if an article is fake news or not.

## Purpose
The aim of this project was to identify whether a given news article is real news or fake news.

## Data
Data was downloaded from [Kaggle](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset) 
Data contains a total of 44898 news articles. Target classes as well balanced with 23481 articles classified as fake and 21417 classified as real.For our analysis the fake news table and real news tables were merged to form a single table.

## Feature Engineering
Implemented the following ideas to obtain relevant features from the dataset:

- Text/NLP based features:
  - Count of words
  - Count of words starting with upper case 
  - Count of characters
  - Average length of the words
  - Punctuation count
  - Frequency distribution of Part of Speech Tags:
    - Noun Count
    - Verb Count
    - Adjective Count
    - Adverb Count
    - Pronoun Count
- TF-IDF (n-gram level) features as vectors


## Date processing

- Case conversion
- Remove accented characters
- Expand contractions
- Remove special characters
- Lemmatization

## Model used



## Result

### **Extreme Gradient Boosting** classifier achieved **Accuracy** of **99.53%**  
