# fakeNews

## Overview
Used a TfidfVectorizer and PassiveAggressiveClassifier from sklearn library to classify real and fake news in a dataset.

## Results
Confusion matrix and model accuracy score pictured below. There were 589 true positives, 598 true negatives, 50 false positives, and 30 false negatives.

![image](https://user-images.githubusercontent.com/92554586/179366594-c0b24546-ecfd-42af-8471-e1345ed38f55.png)

## Summary
On a relatively simple dataset this model achieved an accuracy score of 93.69%. It performed very well at identifying true positives and negatives, with very low false positives and negatives. After fitting and transforming the initial datset with the TfidfVectorizer (term frequency and inverse document frequency), it was ready to be trained with a PassiveAggressiveClassifier model. This model could be used on larger and more complex data, with adjustments to the code.   
