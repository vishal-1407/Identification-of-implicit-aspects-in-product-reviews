# This project identifies implicit (hidden) aspects of various products from the product reviews in order to improve the overall approach of Aspect Based Sentiment Analysis.
It uses the frequency of corpus adjectives and their word2vec embeddings to identify implicit aspects.
It uses Multinomial Naive Bayes classifier for classifying implicit aspects.
Python (Jupyter Notebook) and its various libraries such as NLTK, pandas, NumPy, Scikit-learn were used to implement the proposed model.
Regular expression was used to extract labeled data from the set of labeled and unlabeled data.
Various data pre-processing steps were applied such as Removal of punctuation marks, tokenization, removal of stop words, and lemmatization.
Improved the overall existing performances metrices such as precision, recall, and F1 score by 4.25% using both micro and macro averaging,
and 5-fold and 10-fold cross validation techniques with maximum value approaching to 99.6% for 5-fold macro-averaging precision.
