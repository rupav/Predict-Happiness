
# Predict-Happiness
Hackerearth Challenge( deadline- 30th nov. 2017)

![Smileys]( https://github.com/rupav/Predict-Happiness/blob/master/smileys.jpg )

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


* My Final Private Leaderboard Ranking and score : 177/554 and 86.781
* Private Leaderboard top score : 91.051
* My Final Public Leaderboard Ranking and score : 
* Public Leaderboard top score :

## Comments:
This repository is made to accumulate and test various techniques in sentiment analysis.
Couldnt make any submissions in nov. because of college exams :( . 
Should have tried Deep Learning. 

# References:
[Stopwords analysis](http://www.lrec-conf.org/proceedings/lrec2014/pdf/292_Paper.pdf) : For 2nd approach- key points :
 * TF1 outperforms other stoplists.
 * standard stoplist has a negative impact on sentiment analysis.
 * NB is more sensitive to stopwords removal than MaxEntropy.
 * Two more approaches- TBRS and Mutual Information can be explored!

# TO DO after challenge deadline:
 * To explore Deep Learning Techniques on sentiment Analysis.
   * CBOG (continuous bag of words) techniques
   * skip grams with negative sampling.
 * Other techniques with different preprocessing.
 
# Contribution:
Please create an issue first, and then make a relevant PR for it.
