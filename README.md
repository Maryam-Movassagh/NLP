# Natural Language Processing and Agentic AI
The folders contain the code for both sentiment analysis of AI using Jupyter Notebook as well as the basic building of a chatbot using Open AI model.
The first project is the different airlines about which comments have been tweeted are going to be compared. For this purpose, unique names of people and unique airline names have been extracted. Also, for comparison, sentiments have been converted to numercial values, and the average of them have been calculated for comparison between airlines as well.

In the second part of the code, all the tweets have been considered. Also, since some comments include reference to other comments, they have been joined. To estimate the sentiment from the text, two approaches have been made:

First, count of words have been calculated after processing the sentences in the texts.
In the second approach, tf-idf has been calculated as features of the classifier used.
In addition to the two approaches, two comparisons have been made:

Models with more features than text have been compared to models with text only.
Imbalance in data have been removed to prevent the model from being biased towards one label. The resultant two models have been compared.
