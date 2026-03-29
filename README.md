# Poster

The project can be repeated through the codes here present. Some codes are independent, others must be concataneted.

### Independent
First, FedScrapping provides all the Federal Reserves statements that are used for controls. 

### In concatenation
Then, "Tweet extraction" gets the necessary tweets. Tweets and Embeddings, get the embeddings. THen the final code *Sentiment and VIX* extracts all the data for financial volatility, as well as trains the BERT and VADER models. Finally, within the same code in the last part (using the data from FedScrapping) we run the final regressions, both OLS FE, RF, and Event studies
