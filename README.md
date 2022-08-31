# Nlp_tweet-project
I try to classify the tweet as Positive about the corona vaccine (1) or negative  about the corona vaccine (2) or It has nothing to do with the Corona vaccine
this tweet collection from social media can download from "https://drive.google.com/file/d/1KepfzAhJ7dloG8XaWQf0ovQipDHYS8aI/view?usp=sharing".
-I make visualization for data to understand it and make some text Preprocessing, then extract the Bag of words feature using CountVectorizer and use some model machine learning like LogisticRegression as a baseline then using some deep learning model.
<tbody>
    <tr>
      <th>0</th>
      <td>logistic regression with bag of words</td>
      <td>none</td>
      <td>0.761870</td>
    </tr>
    <tr>
      <th>1</th>
      <td>logistic regression with bag of words</td>
      <td>removing emojis, removing urls, remove_tweets_...</td>
      <td>0.768495</td>
    </tr>
    <tr>
      <th>2</th>
      <td>logistic regression with tfidf</td>
      <td>removing emojis, removing urls, remove_tweets_...</td>
      <td>0.768495</td>
    </tr>
    <tr>
      <th>3</th>
      <td>model using lstm and embadding with balanse</td>
      <td>removing emojis, removing urls, remove_tweets_...</td>
      <td>0.728400</td>
    </tr>
  </tbody>
