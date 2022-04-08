# Sentiment-Analysis-Using-Naive-Bayes-Classifier
In this project I have tried to perform the sentiment analysis on the twitter dataset which I have taken from the open source Kaggle platform( (https://www.kaggle.com/code/arunrk7/nlp-beginner-text-classification-using-lstm/data).

The dataset consist of 1600000 dataset out of which 800000 have the positive sentiment and rest 800000 have negative sentiment.
Positive sentiment is defined as 4 which I further replaced with 1 and negative sentiment is defined as 0. 

The data consists of consists of 6 attributes i.e. (sentiment, ids, date, flag, user, text) out of which only <b>sentiment</b> and <b>text</b> field are important for us. So, I dropped the rest of the attributes. 

After dropping the unnecessary attributes I have picked the 500 tuples out of 1600000 tuples randomly and then performed preprocessing on them so that I can train the model further and get better accuracy. 

Preprocessing of the text involves removing the url, number, special characters, hastages, @username, etc and  I also removed the stopwords and then performed lemmatization on each word of the text. 

When the preprocessing completes I proceeded further and used the Multinomial Naive Bayes Classifier to train and test our model. I used 70 percent of the data to train the model and rest 30 percent of the data to test the model and acchieved the accuracy of <b>63.33%. </b>

