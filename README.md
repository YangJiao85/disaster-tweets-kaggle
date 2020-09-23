# Real or Not? NLP with Disaster Tweets from [Kaggle](https://www.kaggle.com/c/nlp-getting-started)

Natural language processing (NLP) getting started project.

**Table of contents**
- [**Exploratory data analysis**](disaster_tweets_getting_started.ipynb)
- [**Machine learning model**](disaster_tweets_MLmodel.ipynb)


The challenge in this competition is to build a machine learning model that predicts which Tweets are about real disasters and which one's aren't. The dataset contains 10,000 tweets that were hand classified. 


I built pipline using scikit-learn to do data cleaning, text data preprocessing, model training and prediction. 
In text data preprocessing I used 
regular expression (RE) matching operations from _re_ module in Python to extract url, tag, hashtag from tweets. 
- OneHotEncoder to encode the location.
- CountVectorizer to vectorize the key words.
- TfidfVectorizer to vectorize the text.
- LinearSVC, GradientBoostingClassifier models have been tested.
- GridSearchCV to optimize the hyperparameters.

**Python libraries:** _numpy, pandas, scikit-learn, matplotlib, seaborn, pyspellchecker_
