# GloVe and BERT embeddings combined with LSTM model for predicting user rating of hotels based on the review text

Many different architectures including linear models, random forests, boostings and many different texts embeddings including `fastText`, `word2vec`, `TF-IDF`, `bag-of-words` were tested.

Two models were built for a task of prediction user rating based on the texts of positive and negative feedbacks:
* `GloVe` embeddings + `LSTM` model
* `BERT` embeddings + `LSTM` model

Validation MAE of *0.75* and train MAE of *0.55* were achieved by `GloVe` + `LSTM` model. Minor improvement over these results has been achieved by using `BERT` + `LSTM` model, but at the cost of a very high computational and time complexity. 
