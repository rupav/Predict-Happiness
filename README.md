# Predict-Happiness
Hackerearth Challenge( deadline- 30th nov. 2017)

## Stats of 70% of the test dataset, as checked on Hackerearth:

Submission date| My Score  | Leaderboard Max score | Approach
----------- | ------------- | ------------- | ---------------
18th oct. 17| 86.781  | 90.624 | multinomialNB with standard stoplist


# References:
[Stopwords analysis](http://www.lrec-conf.org/proceedings/lrec2014/pdf/292_Paper.pdf) : For 2nd approach- key points :
 * TF1 outperforms other stoplists
 * standard stoplist has a negative impact on sentiment analysis
 * NB is more sensitive to stopwords removal than MaxEntropy
 * Two more approaches- TBRS and Mutual Information can be explored!

