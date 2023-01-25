# BANGLA-FAKE-NEWS-CLASSIFICATION-USING-MACHINE-LEARNING

Problem Statement

Nowadays, everything is getting digitalized. So, with the blessings of modern technology, people can read news of the whole world through different kinds of online news portals. A large number of people in our country now read online news portals in Bengali. Among these news portals, there also have some fake news and real news. But, in maximum time mass people can’t discriminate between this two. That’s why it is necessary to classify fake news and real news. In this project, we use different kinds of machine learning models such as Random Forest, Logistic Regression, KNN, and Decision Tree for the dataset named “BanFakeNews” to classify whether the news is real or fake. Among these models, Logistic Regression comparatively performs better gaining 92%.


Dataset

The provided dataset contains around 8.5k news data on the different news portals. Between these, around 7k are authentic, and around 1k are fake news. The fake news is labeled with 0 and the real news is labeled with 1.


![dataset](https://user-images.githubusercontent.com/123116162/214581991-b0684397-4d1f-4a45-b41e-611d6f122e34.png)


Approach

 The dataset contains raw data and we have cleaned this dataset by removing stop-words, special characters, and punctuations in the pre-processing stage. For separating every word, we have used here tokenization. Then we extracted the features from the news data using TF-IDF. The following diagram is for workflow:
 
 ![approach](https://user-images.githubusercontent.com/123116162/214582599-6de407e9-192d-43e3-b38c-3fd508ce6e0b.png)
 
 
 
We have classified the news according to the following steps:
Step 1:  Load the dataset.
Step 2:  Remove stop words, punctuations, and special characters.
Step 3:  Use TF-IDF for feature extraction.
Step 4: Then split the dataset into 70% and 30% where 70% is for training and 30% is for testing part.  
Step 5:  Use Machine learning models (Random Forest, Logistic Regression, KNN, Decision Tree).
Step 6:   Calculate Recall, Precision, F1 Score, and Accuracy for every model. From these Metrics, we have got the best model for which we have got the best accuracy.

![table](https://user-images.githubusercontent.com/123116162/214582925-21bd31ed-9f0c-44e4-8bea-69f6b61e818e.png)


Conclusion
Here, Logistic Regression model performs better than the other models to classify fake and real news. We can improve the accuracy by increasing the dataset and using deep learning models in the future.


















