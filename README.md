# SENTIMENTY
We will make a Sentiment analyser model for the IMDB 50k movie review dataset taking into account BERT,logistic regression and linear svm and compare their accuracies.

# IMPLEMENTATION
1)<b>Data preprocessing or cleaning</b> : I start by reading the given dataset.I then cleaned the data by performing tasks like tokenization, stop word removal,url removal,html tag removal, and lemmatization with data exploratory analysis done in between using word cloud etc libraries to convert the text into a format that can be used by the model.
<br>
<br>
2)<b>Feature extraction</b>: Once the data was preprocessed, I extracted features that can be used by the model to make predictions. I used the approaches of bag-of-words and tf-idf methods for the vectorization where each movie review is represented as a vector of word counts.
<br>
<br>
3)<b>Model training</b>: I then split the data into training and testing sets, and then trained the logistic regression model and linear support vector machine model on the training set. During training, I experimented by using tf-idf with linear svm,tf-idf with logistic regression,bag of words with linear svm and bag of words with logistic regression to compare their accuracies.
 <br>
 <br>
And the last step<br>
4)<b>Model evaluation</b>: Once the model was trained, I evaluated its performance on the testing set. Using the evaluation metrics of accuracy, precision and recall.
<br>
<br>

# DEPENDENCIES
<br>
omw-1.4
<br>
wordnet
<br>
wordcloud
<br>
stopwords
<br>
transformers
<br>
tensorflow
<br>
tensorflow_hub
<br>
torch
<br>

# END RESULT
<br>
Logistic Regression with tf-idf vectorization: Accuracy=87.44%
<br>
Logistic Regression with bag of words vectorization: Accuracy=86.19%
<br>
Linear Support Vector with tf-idf vectorization : 87.63%
<br>
Linear Support Vector with bag of words vectorization : 83.64%
<br>
Bert Model(deployed on external machine due to high eda time on local machine) accuracy-88.55%
<br>
<br>
<b>Clearly Bert model has emerged as the winner among all the models we have implemented
