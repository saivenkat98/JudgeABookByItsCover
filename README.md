# JudgeABookByItsCover

INTRODUCTION:
The specific problem I intend to address and solve is the need of choosing the right book as per one’s existing choices. 

Currently the problem people have in retaining our habit of reading is the choice of books I choose to read, once I like a book I read I’ll try to relive that experience so search about for a book that is similar to the previous one. 

This exact need is fulfilled by our attempt where in based on the cover page of a book of our choice, I classify and predict its genre so as to get the books that are of similar nature.

IMPLEMENTATION:
In the feedforward network there are three layers which are the input layer, hidden layer, output layer. Once i feed my input with the hidden layer which hosts all the mathematical operations such as linear combination/activation functions, they process the same and provide the transformed data.

By using this methodology, the ‘Title-of-book’ data from dataset are split and made a count of each word used in the title and resulted the grouped total of each word. After which titles and genres (Target Variable) are transformed to vectors to check how many times does each word I sourced from all titles repeat in each individual title and totally in one type of genre.

Once the data is preprocessed below machine learning models were used to train and predict the genres from the data. Before implementing the major learning model i.e., RNN and LSTM, following simpler model are used to predict the genres and simultaneously calculate the accuracy parameter ‘F1 Score’. 

Logistic Regression

Multi Nominal Naïve Bayes

Multi Layer Perceptron

XGBoost
