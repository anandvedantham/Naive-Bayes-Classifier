# Naive-Bayes-Classifier

A Naive Bayes classifier is a probabilistic machine learning algorithm commonly used for classification tasks, such as spam email detection, sentiment analysis, and text classification. It's based on Bayes' theorem, which is a fundamental theorem in probability theory.

The "naive" in Naive Bayes refers to a simplifying assumption made by the algorithm. It assumes that the features used to classify data are conditionally independent of each other, given the class label. In other words, it assumes that the presence or absence of one feature does not affect the presence or absence of any other feature. While this assumption rarely holds in the real world, Naive Bayes can still perform well in practice, especially for text classification tasks.

## Implementation
- Importing the required Libraries
- Reading the train and the test datasets
- Performing EDA on both the datasets (train and test)
- Splitting the train and the test data
- Normalization of the data
- Building the Model
  - using Gaussian Naïve Bayes
  - using Multinomial Naïve Bayes
- Conclusion

## Packages Used
- pandas
- numpy
- matplotlib.pyplot
- seaborn
- warnings
- from sklearn.preprocessing import LabelEncoder
- from sklearn.metrics import accuracy_score, confusion_matrix
- from sklearn.naive_bayes import GaussianNB
- from sklearn.naive_bayes import MultinomialNB


