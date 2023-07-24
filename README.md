# TYP-project

Abstract

The project reported in this paper will aim to investigate the effect of trading volume data on the performance of deep learning models used for cryptocurrency market price prediction.
Among many other crypto coins, Ethereum (ETH) is the coin of choice in this paper, as it will allow a more flexible interpretation of results and comparison to other studies in the field.
Forecasting is made based on the closing price of ETH, and the aim is to predict the closing price for the following week.
The main focus is made on deep-learning-based hybrid models made of Gated Recurrent Units (GRU) and Long Short Term Memory (LSTM), in addition to a customised Transformer model. The performance of the above models was evaluated before and after applying the Volume of day trading as an additional parameter.
The study results show that Hybrid Models do not experience significant improvements after adding Volume. However, Transformer model performance was notably harmed by Volume. Overall, it is not suggested to use the Volume of day trading as an additional parameter when performing cryptocurrency price prediction using deep neural networks.

Data-Preprocessing -> here we download the initial data set and convert everything to appropriate formats suitable for our models and save it to google docs for easier access via google colab.

Deep Learning Model GRU-LSTM -> 
Deep Learning Model LSTM-GRU ->
Experiment With Models ->
