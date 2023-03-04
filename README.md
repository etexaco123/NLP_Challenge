
# NLP Challenge

This assignment is about based on sentiment analysis of IMDB 50k dataset.


## Authors

- [@etexaco123](https://www.github.com/etexaco123)


## Procedure
- Download the dataset from Kaggle.
- Load the dataset in google colab.
- Mount the drive.
- Create a preprocessing pipline to clean the dataset
- Since the dataset contains a lot of noise such as html tags, stopwords, special characters etc.
- Applied lowecasing to normalize the text
- I also applied lemmatization to reduce the text in the data fram to its base form
- I discovered that the dataset was balanced.
- Transformed the data into numeric vectors using bag of words (BOW) TF-IDF to vectorize the dataset
- I sampled various methods such as support vector machines (SVM), logistic regression, Naive Bayes but support vector machines gave me the best result.
  
  
### Below is the confusion matrix of the performance of the SVM model
  

![Alt](https://github.com/etexaco123/NLP_Challenge/blob/main/confusion_matrix.png?raw=true)
