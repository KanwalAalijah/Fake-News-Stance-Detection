# Fake-News-Stance-Detection

**Dataset:**
           Headlines and body text of 49972 news articles.
           
**Task:**
          1) Labelling of Training Sample
          2) Feature Extraction
          3) Classification using two different classifiers
          4) Determination of accuracy over the classifiers
          
**Method:**
          The task of classification was performed in the following steps (Implemented in Python):
          
**A.** **Data Preprocessing:**
       The dataset was preprocessed first;
       The duplicate records were removed and merged into a single file containing (headline, body id, stance, article body)
       
**B.** **Tokenization, Stopping , Stemming and Lemmatization:**
      The headline and body text was preprocessed by applying tokenization, stopping , stemming and lemmatization using nltk toolkit.
      
**C.** **Feature Extraction:**
      The features were extracted using:
      Bag of words
      Term Proximity
      SentiWordNet
      
**D.** **Data Normalization:**
      The final extracted features were normalized before applying classification algorithms.
      Min-Max normalization was applied to the features.

**E.** **Train and Test Set construction:**
      The data was split into 70/30 where 70% of instances were used for training and remaining 30% for testing the accuracy of the classifiers.
      Classification and Model Accuracy:
      The data was classified using 4 classifiers:
        **.** K Nearest Neighbor
        **.** Decision Tree
        **.** Random Forest
        **.*** Neural Networks
