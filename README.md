# reverse_auction_engine
Detecting bots in online auctions.

Data set - https://www.kaggle.com/c/facebook-recruiting-iv-human-or-bot/data 
We have two datasets .One is a bidder dataset that includes a list of bidder information, including their id, payment account, and address. The other is a bid dataset that includes 7.6 million bids on different auctions. The bids in this dataset are all made by mobile devices. 

    train.csv - the training set from the bidder dataset
    test.csv - the test set from the bidder dataset
    sampleSubmission.csv - a sample submission file in the correct format
    bids.csv - the bid dataset

--> run the 33_ire_main.py with all the datasets in the current working directory.

--> Output is a results.csv file with bidder_id and the prediction probability ( 0 - human , 1 - bot. according to probability we can decide whether it is a human or bot ) 



