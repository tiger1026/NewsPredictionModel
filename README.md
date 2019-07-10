# NewsPredictionModel
Practice of News prediction with data proved from Kaggle.
This code is a practice coding project from https://www.kaggle.com/ndrewgele/omg-nlp-with-the-djia-and-reddit
The data is also provided from https://www.kaggle.com/aaron7sun/stocknews\n

Our raw data consists of DJIA_table.csv, Combined_News_DJIA.csv, and RedditNews.csv. In my practice I will be using only the data from Combined_News_Djia.csv. The purpose of this data is to find a relation of specific words or sentences to headlines. In otherwords trying to predict what specific word or phrases has the most influence and relation to a news becoming a headline article. 

The model uses the CountVectoroizer function to split headlines in to single words or phrases, and we will model these with a logistic model. Divide them into a train and test model, then predicting our test model with the training model. 

All codes are practice learned from the link above, apart from the last part of the model where I set the ngram_range = (4,4). I do not own the data as well, it is provided by the second link. 
