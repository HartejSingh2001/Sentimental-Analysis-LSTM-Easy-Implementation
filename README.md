# Sentimental-Analysis-LSTM-Easy-Implementation
INTRODUCTION 

Sentiment is just as human emotion is a wide – ranging spectrum of varying intensity. And this intensity matters, especially when it comes to social media monitoring. People make positive, neutral and negative attitudes about events, places, people, and products. These types of attitudes can be termed as sentiments.
Sentiment analysis is a layer applied to the rest of our analytics, to put data analytics into context and categorize consumer emotions by type and intensity. Or in other words we can say that sentiment analysis is the study of automated techniques which is used for extracting sentiments from written languages. Sentiment Analysis Tool is the tool that analyses user sentiments and gets the correct polarity of the given sentiments.
Growth of social media has resulted in an explosion of publicly available, user generated text on the World Wide Web (WWW). These data and information from the social media platform can potentially be utilized to provide real-time insights into the sentiments of people.

PROBLEM STATEMENT

In the Sentiment Analysis In Social Media Project, we will try to implement a twitter sentiment analysis model that helps to overcome the challenges of identifying the sentiments of the tweets. In this project we will try to classify or identify tweets from twitter as “positive”, “neutral” or “negative” sentiment. Or we can say that by using Machine Learning or Deep Learning techniques and NLP (Natural Language Processing) we will extract the subjective information of  tweets and try to classify it according to its polarity such as positive, neutral or negative sentiment. Our aim or task is to analyze the sentiment of the tweets of twitter provided from the dataset in terms of Subjectivity and Polarity. We are using Python Programming Language to perform sentiment analysis of twitter along with the Machine Learning or Deep Learning techniques and NLP (Natural Language Processing). 


EXPERIMENTAL SETUP

In our Sentiment Analysis In Social Media Project, we have taken the dataset from the available resources. We have done with reading the dataset in our code part. We have imported different libraries of Python Programming Language which are necessary and required for our project. We have performed pre-processing task in our code part which includes tokenization, stop words removal, normalization and noise removal. We have made our own data for the project which includes all the emotions and its corresponding meaning in it which we have mapped it with the dataset for analyzing the sentiment. 
We have implemented a LSTM (Long Short – Term Memory) model or architecture to find a solution for sentiment analysis. We experimented with 2 layers of LSTMs. We adjusted the hyperparameters, as this could help the model learn more quickly. 
After all these procedures we have trained our model for better results. During training of the model, batch size of 32 and epochs of 100 are used. We have plot the values of epoch and loss to visualize the loss value in every epoch step. We are doing the testing of our model in our code part. At last, in the form of output we will try to classify or identify tweets from twitter social media platform as “positive”, “neutral” or “negative” sentiment. 


PROPOSED MODEL AND HYPERPARAMETERS USED

In our project we have implemented a LSTM (Long Short – Term Memory) model or architecture to find a solution for sentiment analysis. We experimented with 2 layers of LSTMs. We adjusted the hyperparameters, as this could help the model learn more quickly.          


LSTMs are a special kind of RNN (Recurrent Neural Network), capable of learning long-term dependencies. LSTMs are explicitly designed to avoid the long-term dependency problem. Remembering information for long periods of time is practically their default behaviour.



No of layers = 2
LSTM and EMBEDDING size = 256
Direction = Unidirectional
Epochs = 100
Batch size = 32
Dropout = 0.3
Activation function = Softmax
Loss = Categorical CrossEntropy
Optimizer = adam

IMPORTANT POINTS REGARDING LSTM-

1) It fails on longer dependencies beacuase the analysis of information is sequential.
2) It is resource hungry.
3) It is prone to overfitting and using dropout is difficult.
4) It does not solve the problem of Vanishing Gradient completely.
5) Better version of LSTM is to use Transformers.
6) LSTM use BPTT (Back Propagation Through Time).
7) LSTM has better output than RNN.
8) LSTM has 3 gates namely -
   a) Input Gate - It sees what amount to information to write into internal cell state.
   b) Output Gate - It sees what amount of information should go out.
   c) Forget Gate - It basically forgets unnecessary information which is not required.
9) It also has a modulation gate which modulates the information being written into the internal cell state by making the information Zero Mean.
10) LSTM has 3 sigmoid gates and 1 tan h layer.

CONCLUSION 

The aim or objective or task is to analyze the sentiment of the tweets of twitter provided from the dataset in terms of Subjectivity and Polarity.





