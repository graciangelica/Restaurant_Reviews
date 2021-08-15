# Restaurant_Reviews

The goal of this project is to train the machine to understand the text reviews and can predict whether it's a positive or negative review.


## Description

Most of the Restaurants ask for reviews from their customers and based on the reviews the restaurant can improve customer satisfaction. So Reviews play a vital role in the successful growth of the restaurant. In this project, you asked to make a machine that can predict if the review is good or bad for the restaurant.

## Output of the project

To solve the problem I use Natural Language Processing(NLP) to teach the machine so it can understand what is written in the reviews by:
- exploring the data, 
- cleaning the texts by removing not useful or meaningful words such as 'the', 'a', 'an' and etc, using stopwords,
- get rid of tenses that are used in the word and transform it to the root form. For example, 'loved' transform to 'love'
- Then transform the data into vectors so that we can apply NLP algorithm using the bag-of-words model

Last, trained and tested the data with some machine learning algorithms, and it shows that RandomForest is the best classifier with 83% accuracy. And now the machine can predict the reviews quite well.



















