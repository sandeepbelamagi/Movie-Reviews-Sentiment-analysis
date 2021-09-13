# Movie-Reviews-Sentiment-analysis

1. First importing the required libraries like pandas, nltk, vectorizing, ML modules and pickels etc..

2. Loading the data and checking weather it contains any null values.

3.Steps to clean the reviews:
	1. Remove HTML tags
	2. Remove special characters
	3. Convert everything to lowercase
	4. Remove stopwords
	5. Stemming

4. Creating the model
	1. Creating Bag Of Words (BOW)
	2. Train test split
	3. Defining the models and Training them.
	4. Prediction and accuracy metrics to choose best model.

5. Creating pickel files of CountVectore and NLP ML module.

In this project the three ML modules are used because to vary the accuracy 
1. GaussianNB =  0.7843
2. MultinomialNB =  0.831
3. BernoulliNB =  0.8386

The Naive Bayes algorithum is for the predicting data is classification problem.

The BernouliNB model pickel file is used for deployement purpose beacause it's have good accuraccy
