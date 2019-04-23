# Sentimental Analysis on Google Play Store App's reviews

## Dataset
The dataset contains web scraped data of 10k Play Store apps for analysing the Android market.
It contains the first 'most relevant' 100 reviews for each app. Each review text/comment has been pre-processed and 
attributed with 3 new features - Sentiment, Sentiment Polarity and Sentiment Subjectivity.
The Dataset has 64.3K instances.More details of the dataset can be found in the kaggle website.
[https://www.kaggle.com/lava18/google-play-store-apps#googleplaystore_user_reviews.csv](https://www.kaggle.com/lava18/google-play-store-apps#googleplaystore_user_reviews.csv) 


## Install
This project requires python 3.6 or any other higher versions of python, along with these libraries
* NumPy
* Pandas
* matplotlib
* scikit-learn
* seaborn
* nltk
* keras<br/>

You also need a software to run this python notebook "Jupyter Notebook". It is highly recommended that you install the Anaconda 
distribution of Python, which already has most of the above packages and more included.

## Feature Description
The dataset contains the following features:
* App - Name of the app
* Translated_reviews - User review (Preprocessed and translated to English)
* Sentiment - Positive/Negative/Neutral (Preprocessed)
* Sentiment Polarity - Sentiment polarity score
* Sentiment Subject - Sentiment subjectivity score

## Desired Target
Sentiment - Positive/Negative/Neutral

## Models Trained On
| Algorithm | Accuracy |
| --- | --- |
| Logistic Regression | 0.90 |
| Neural Networks | 0.90 |
