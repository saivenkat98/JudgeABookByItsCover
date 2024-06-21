# JudgeABookByItsCover

INTRODUCTION:
The specific problem I intend to address and solve is the need to choose the right book based on one’s existing preferences.

Currently, the problem people face in maintaining their reading habit is the choice of books. Once I find a book I enjoy, I try to relive that experience by searching for a book similar to the previous one.

This exact need is fulfilled by our attempt, where based on the cover page of a book of our choice, I classify and predict its genre to find books that are of a similar nature.

IMPLEMENTATION:
In the feedforward network, there are three layers: the input layer, the hidden layer, and the output layer. Once I feed my input to the hidden layer, which hosts all the mathematical operations such as linear combinations and activation functions, they process the data and provide the transformed output.

By using this methodology, the ‘Title-of-book’ data from the dataset is split, and a count is made of each word used in the title, resulting in the grouped total of each word. Afterward, titles and genres (Target Variable) are transformed into vectors to check how many times each word sourced from all titles is repeated in each individual title and in one type of genre.

Once the data is preprocessed, the following machine learning models were used to train and predict the genres from the data. Before implementing the major learning models, i.e., RNN and LSTM, the following simpler models were used to predict the genres and simultaneously calculate the accuracy parameter, the ‘F1 Score’.

Logistic Regression

Multi Nominal Naïve Bayes

Multi Layer Perceptron

XGBoost
