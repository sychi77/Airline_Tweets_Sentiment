# Airline_Tweets_Sentiment
Sentiment Prediction for Virgin America and United Airline tweet data using NLP. 
Data obtained from ZS for a hackerearth data scientist challenge.

### Main
[Predict_Sentiments_of_Tweets](https://github.com/sychi77/Airline_Tweets_Sentiment/blob/master/Predict_Sentiments_of_Tweets.ipynb "Predict Tweet Sentiments Jupyter Notebook") contains the main code.

### Cleaning
* Tweets cleaned for punctuations, @, link addresses 
* Use BeautifulSoup from bs4 and WordPunctTokenizer from nltk.tokenize

### Predictive Models
* Classification of tweet sentiment (positive, neutral, negative).
* TfidfVectorizer w/ or w/o stop words and ngram range 1 to 2.
* RandomForestClassifier, LinearSVC, MultinomialNB, LogisticRegression
* 5-fold Cross-validation

### Best Performer
* LinearSVC w/ Bigrams, no stopwords on cleaned tweets (Accuracy: 74.48%)
