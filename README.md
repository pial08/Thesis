This project was part of my thesis project. There were 3 parts that were associated with this project. 
  1. Scrapping Data from various website.
  2. Annotating these data using crowd sourcing and
  3. Finally, analyze these data using LSTM, a recurrent neural network algorithm. 
 
This part of code is all about analyzing the data.  

The library pandas was used as a data reading and data manipulation tool.
Numpy was used to play with the data and format the data accordingly. 
wordToVec model was used to convert the corpus into a numerical form that deep net can understand. 
Given a certain word, the vordToVec model can find the words that are related to the given word. 
It can also find which words are not similar within a bunch of words. 
After cleaning the data, there were almost 8000 sentences among them around 4500 are positive and 3500 are negative. The rest were neutral sentences. 
After training and splitting the data into the ration of 0.9, and training them with LSTM, an accuracy of 74.06 was achieved. 
In the latter part of the analysis, there are some graphs, which denotes how the sentiment of a sentence goes up and down with each word comes.
