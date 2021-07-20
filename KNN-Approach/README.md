# Amazon-Food-Reviews-Analysis using KNN

#### Performed Exploratory Data Analysis, Data Cleaning, Data Visualization and Text Featurization(BOW,TFIDF,AVG Word2Vec,TF-IDF W2V). 

KNN
1. Applied K-Nearest Neighbour on Different Featurization & Data Visualization. BOW(uni-gram), tfidf, Avg-Word2Vec and tf-idf-Word2Vec 
2. By using both brute & kd-tree implementation of KNN 
3. Evaluated the test data on various performance metrics like accuracy also plotted Confusion matrix 
using seaborne

###### Conclusions:
1.  KNN is a very slow Algorithm takes very long time to train.
2.  Best Accuracy  is achieved by Avg Word2Vec Featurization.
3.  Both kd-tree and brute algorithms of KNN gives comparatively similar results.
<hr>

**Results :-** 
+--------------+---------+----------------+-------+
|  Vectorizer  |  Model  | Hyperparameter |  AUC  |
+--------------+---------+----------------+-------+
|     BOW      |  brute  |       17       | 0.781 |
|    TFIDF     |  brute  |       37       | 0.854 |
|   AVG W2V    |  brute  |       31       | 0.873 |
| Weighted W2V |  brute  |       9        | 0.837 |
|     BOW      | kd_tree |       27       | 0.787 |
|    TFIDF     | kd_tree |       37       | 0.854 |
|   AVG W2V    | kd_tree |       31       | 0.873 |
| Weighted W2V | kd_tree |       9        | 0.837 |
+--------------+---------+----------------+-------+
