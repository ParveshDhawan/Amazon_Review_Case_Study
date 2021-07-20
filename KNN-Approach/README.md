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

| Vectorizer    | Algorithm    | Nearest Neighbors | AUC Score |
| -------------:|-------------:| -----------------:| ---------:|
| BOW           |  Brute Force |       17          | 0.781     |
| Tf-iDF        |  Brute Force |       37          | 0.854     |
| Avg W2V       |  Brute Force |       31          | 0.873     |
| Weighted W2V  |  Brute Force |       9           | 0.837     |
|                                                              |
| BOW           |  Kd - Tree   |       27          | 0.787     |
| Tf-iDF        |  Kd - Tree   |       37          | 0.854     |
| Avg W2V       |  Kd - Tree   |       31          | 0.873     |
| Weighted W2V  |  Kd - Tree   |       9           | 0.837     |
