# Amazon-Food-Reviews-Analysis using KNN

#### Performed Exploratory Data Analysis, Data Cleaning, Data Visualization and Text Featurization(BOW,TFIDF). 

Naive Bayes
1. Applied Naive Bayes on Different Featurization & Data Visualization. BOW, tfidf 
2. Try different alpha values 
3. Evaluated the test data on various performance metrics like accuracy also plotted Confusion matrix

###### Conclusions:
1.  Adding two features Text Summary & Text reviews shown a improve in accuracy and reduce overfitting
<hr>

**Results :-** 

| Vectorizer    | Feaured Used     |   Hyperparameter | Train AUC | Test AUC |
| -------------:|-----------------:| ----------------:| ---------:| --------:|
| BOW           |   Review         |       1          |  0.972    | 0.946    |
| Tf-iDF        |   Review         |       1          |  0.984    | 0.956    |
|    ----       |   ----           |      ----        |   ----    |  ----    |
| BOW           | Review + Summary |       0.1        |  0.98     | 0.961    |
| Tf-iDF        | Review + Summary |       0.1        |  0.988    | 0.969    |
