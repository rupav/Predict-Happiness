# Predict-Happiness
Hackerearth Challenge( deadline- 30th nov. 2017)

## Stats of 70% of the test dataset, as checked on Hackerearth:

Submission date|My Score | Leaderboard Max score| Approach
-----------    | ------- |        ------------- | ---------------
18th oct. 17   | 86.781  | 90.624               | multinomialNB with standard stoplist|
20th oct. 17   |86.363   | 90.624               | using MultinomialNB with TF1 stoplist only |
20th oct. 17   |84.070   | 90.624               | using MultinomialNB with TF1 stoplist only and TFIDF approach|
20th oct. 17   |86.300   | 90.624               | using MultinomialNB with tf_high(thresh 7500) stoplist in addition to tf1|
20th oct. 17   | 86.630  | 90.624               | using MultinomialNB with tf_high(thresh 7500) stoplist in addition to tf1 and standard stoplist|
23rd oct. 17   |80.878   | 90.624               | Random Forest Classiffier
28th oct. 17   |86.668   | 90.624               | Removed hyphens and used Lemmatizer, used MultinomialNB



# References:
[Stopwords analysis](http://www.lrec-conf.org/proceedings/lrec2014/pdf/292_Paper.pdf) : For 2nd approach- key points :
 * TF1 outperforms other stoplists
 * standard stoplist has a negative impact on sentiment analysis
 * NB is more sensitive to stopwords removal than MaxEntropy
 * Two more approaches- TBRS and Mutual Information can be explored!

