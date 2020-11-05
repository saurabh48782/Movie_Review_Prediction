# Movie_Review_Prediction
Using the concept of Natural Language Processing and Naive Bayes Classifier to make a supervised machine learning model that learns from previous data and predicts about the class of reviews as either they belong to positive or negative class.
#### Used the NLTK (Natural Language Processing Toolkit) library to preprocess the words through a Bag of Words pipeline:
 - Tokenization : Tokenized each review
 - Stopword removal : removed unuseful words from the reviews, that are not relevant for prediction purpose.
 - Stemming/Lemmitization: Converting words into their base form to reduce redundancy.
 - Vocab/Feature Vector creation
#### Used Naive Bayes classifier to learn from the Vocab/Feature vector and classify the reviews as positive or negative.
 - used Multinomial and Multivariate Bernoulli Naive Bayes classification algorithms.
