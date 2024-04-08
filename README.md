# Codsoft-GENRE-CLASSIFICATION
Using Multinomial Naive Bayes, this code snippet illustrates a text classification task. It starts by loading training and testing data sets containing text descriptions and the associated genres. Language detection, text cleaning by removing URLs, Twitter handles, punctuation and single characters are part of the data processing phase. Using Google Translate, it is also translated into English of those descriptions which are not in English.

To gain insight into the data, a visual representation of text length distribution is presented. In order to convert text data to TFIDF features, the Tfidfizer is then used. In order to deal with the imbalance in classes, statistical sampling is employed. 

The Multinomial Naive Bayes model is programmed with preprocessing training data and the predictions are based on testing data. Finally, the accuracy of the model shall be assessed and its running time measured in order to evaluate how efficient the classification procedure is.

Accuracy : 0.6947416974169742         

Running Time :  0.36 Secounds

                 precision    recall  f1-score   support

                 
 documentary        0.73      0.69      0.71     13096
 
       drama        0.69      0.43      0.53     13612
       
        other       0.68      0.83      0.75     27492
        
     accuracy                           0.69     54200
     
    macro avg       0.70      0.65      0.66     54200
    
 weighted avg       0.70      0.69      0.68     54200
