The purpose of this project is to build a machine learning model that will support future funding decisions from Alphabet Soup. With the provided dataset of over 34,000 organizations that have previously received funding, we have various inputs for the model. As the goal is to identify and accurately predict successful investments, the "IS_SUCCESSFUL" column was used to split the features and target arrays. After pre-processing, splitting the training/testing datasets, and processing it through the neural network and sequential models, the machine learning model produces 100% predictive accuracy. This was achieved by:

* First hidden layer: 300 hidden nodes
* Second hidden layer: 200 hidden nodes
* Output layer: 1 node

EPOCH 33/50 is where 100% accuracy begins to be observed.

*Note: for column "IS_SUCCESSFUL", it is assumed that "0" = "N" and "1" = "Y".
