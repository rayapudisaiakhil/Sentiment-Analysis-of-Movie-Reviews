# Sentiment Analysis of IMDB Movie Reviews

This is a project for sentiment analysis on IMDB movie reviews data using machine learning techniques like Naive Bayes, Logistic Regression and Support Vector Machines (SVM).

## Project Overview

- The project aims to classify the sentiment of IMDB movie reviews as positive or negative using machine learning algorithms.

- Different models like Naive Bayes, Logistic Regression and SVM are trained and evaluated on the dataset. 

- Performance metrics like accuracy, precision, recall and F1 score are used for comparison.

- The results indicate Logistic Regression performs best on this dataset.

## Data

The dataset used is the IMDB movie reviews dataset containing 50,000 highly polarized reviews divided into 25,000 train and 25,000 test sets.

- The data is preprocessed by removing HTML tags, lemmatization, removing stopwords, punctuation and tokenization.

- For feature extraction bag-of-words, count vectorizer and TF-IDF are used. 

## Algorithms

The following machine learning algorithms are used:

- Naive Bayes 
- Logistic Regression
- Support Vector Machines

## Usage

The project is implemented in Python. To run the code:

1. Clone the repository
```
git clone https://github.com/user/sentiment-analysis.git
```

2. Install dependencies
```
pip install -r requirements.txt
```

3. Run the Jupyter notebook
```
jupyter notebook sentiment_analysis.ipynb
```

## Results

Logistic Regression achieved the best performance with 86.89% accuracy on the dataset.

Naive Bayes achieved 85.48% accuracy.

SVM achieved 85.29% accuracy with a linear kernel.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

