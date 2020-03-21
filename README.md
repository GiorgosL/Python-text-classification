# Python-text-classification

This is a twofold project that attempts firstly to classify the type of a subreddit and then the type of the discourse occuring within a Reddit post.  This project was part of my MSc in Data Science in University of Glasgow.


For the __subreddit prediction__ the following steps where followed;

- Develop BernouliNB, Logistic regression and SVC using both one hot encoding and tfidf vectorizer

- Improve parameters of the best model using Randomized grid search.

- Engineer two new features to add in the improved model.


For the __discourse prediction__ the following has been done;

- Test on the existing features with the above model.

- Engineer 6 new features from the existing ones.

- Test the feature combination on the above model.

- Explore the model's outcome using Eli5 to better understand the feature weights.
