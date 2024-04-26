# NLP Tweet Project

In this project, I aim to classify tweets into three categories:

1. Positive about the corona vaccine
2. Negative about the corona vaccine
3. Tweets that are unrelated to the corona vaccine

The tweet collection from social media can be downloaded from [here](https://drive.google.com/file/d/1KepfzAhJ7dloG8XaWQf0ovQipDHYS8aI/view?usp=sharing).

## Approach

I started by visualizing the data to gain insights and performed text preprocessing. Then, I extracted the Bag of Words feature using CountVectorizer and employed various machine learning models, including Logistic Regression as a baseline, as well as some deep learning models.

## Results

The following table shows the performance metrics of different models and preprocessing methods:

| Model Name                                  | Preprocessing Methods                                        | Accuracy   |
|---------------------------------------------|--------------------------------------------------------------|------------|
| Logistic Regression with Bag of Words       | None                                                         | 0.761870   |
| Logistic Regression with Bag of Words       | Removing emojis, removing URLs, remove_tweets_...            | 0.768495   |
| Logistic Regression with TF-IDF             | Removing emojis, removing URLs, remove_tweets_...            | 0.768495   |
| Model using LSTM and Embedding with Balance | Removing emojis, removing URLs, remove_tweets_...            | 0.728400   |

