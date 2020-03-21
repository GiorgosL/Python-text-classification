# Python-text-classification

This is a twofold project that attempts firstly to classify the type of a subreddit and then the type of the discourse occuring within a Reddit post.

For the subreddit prediction the following steps where followed;

-- Utilize BernouliNB, Logistic regression and SVC with one hot encoding and tfidf vectorizer

-- Improve parameters of the best model using Randomized grid search.

-- Engineer two new features to add in the improved model.

For the discourse prediction the following has been done;

-- Test on the existing features with the above model.

-- Engineer 6 new features from the existing ones.

-- Test the feature combination on the above model.
