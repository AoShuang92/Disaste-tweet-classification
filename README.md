# Disaste-tweet-classification
This repo is about the project in Kaggle <a href = "https://www.kaggle.com/c/nlp-getting-started">"Real or Not? NLP with Disaster Tweets"</a>.<br>
I have tried three models in my code: without LSTM, with LSTM and refined LSTM version, with test accuracy of 0.496, 0.773 and 0.780 respectively.<br> 
I seperated the train.csv file into train (0.8) and validation (0.2) data for cross validation. The validation accuracy with refined LSTM model is 0.81.  <br>
The train data includes categories of "id, keyword, location, text and target" and I only focus on text and target parts. <br>
<b>Real sample</b> :Our Deeds are the Reason of this #earthquake May ALLAH Forgive us all<br>
<b>Fake sample</b>: this is ridiculous....". <br>
<b>Preprocessing</b>: I remove the unnecessary punctuation, url, HTML and emoji and lemmatize all data. <br>
The target is the "real or not" section, 1 for real and 0 for fake tweets of disaster. 
