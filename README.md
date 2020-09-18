The purpose of this project is to use machine learning to support future funding decisions from Alphabet Soup. With the provided dataset of over 34,000 organizations that have previously received funding, we have our inputs to create a deep learning model. As the goal is to identify and accurately predict successful investments, the "IS_SUCCESSFUL" column was used to split the features and target arrays. After pre-processing the data, the model returns the history. This was achieved through the following layers:

* (1) hidden layer: 300 hidden nodes
* (2) hidden layer: 200 hidden nodes
* Output layer: 1 node

~For this model iteration, 100% accuracy is returned at epoch 27/50 and <1% loss is returned at epoch 2/50. See model graphs for trends.

*Note: for column "IS_SUCCESSFUL", it is assumed that "0" = "N" and "1" = "Y".
