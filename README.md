# Spam-Filter

This is an implementation of a spam filter in five different methods namely Multinomial Naive Bayes,SVM,CNN,Random Forest classifier and Gradient Boost algorithms.
The dataset is compilation of SMS or text messages which are labelled as spam or ham.

The filter is built from scratch starting from Text Preprocessing,Feature Creation,Model building to Model evaluation and comparision.

# Text Preprocessing
This notebook contains all the text cleaning methods such as stemming,lemmatizing,stopwords and punctuation removal.

# Feature Creation
Features are created based on the length of each string and the perecentage of punctuation present in them.Tfidf Vectorizer and Count Vectorizers are used as a comparision to get better features from the data.

# Model Building,Model evaluation and comparision
Several methods have been employed thereby yielding as a source of comparision to choose the best model.Aseparate comparision of Random Forest and Gradient Boost has also been made.The previously mentioned methods have been evaluated using GridSearch and K-fold cross validation too.

