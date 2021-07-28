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

| Vectorizer    | Algorithm    | Nearest Neighbour | Train AUC | Test AUC |
| -------------:|-------------:| -----------------:| ---------:| --------:|
| BOW           |  Brute Force |       49          | 0.833     | 0.792    |
| Tf-iDF        |  Brute Force |       49          | 0.905     | 0.862    |
| Avg W2V       |  Brute Force |       49          | 0.906     | 0.872    |
| Weighted W2V  |  Brute Force |       49          | 0.906     | 0.872    |
|    ----       |   ----       |      ----         |  ----     |  ----    |
| BOW           |  Kd - Tree   |       49          | 0.833     | 0.792    |
| Tf-iDF        |  Kd - Tree   |       49          | 0.905     | 0.862    |
| Avg W2V       |  Kd - Tree   |       49          | 0.906     | 0.872    |
| Weighted W2V  |  Kd - Tree   |       49          | 0.906     | 0.872    |
