# SENTIMENTY
We will make a Sentiment analyser model for the IMDB 50k movie review dataset taking into account BERT,logistic regression and linear svm and compare their accuracies.
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
