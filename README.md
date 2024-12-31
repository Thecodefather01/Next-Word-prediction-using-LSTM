# Next-Word-prediction-using-LSTM

This is is a simple next word prediction using LSTM

key notes:
You can use callbacks if needed but the optimal accuracy reaches around 270 epoches somewhere around "8.3".My GPU is Nvidia RTX - 2060(6GB) which took 1 H for 300 epoches.We will do more complex models in cloud next time

Also this is trained on a small sample dataset from nltk-gutenberg(shakespeare-hamlet) : if you have more computational power use 3-4 text data and train and also try to substitute GRU instead of LSTM.

Also try to find optimal layers using gridsearch

Process:

there is no need to download the data hamlet.txt it is being loaded in model.ipynb file.

1)run model.ipynb 
