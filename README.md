The purpose of this project is to build a machine learning model that will support future funding decisions from Alphabet Soup. With the given dataset of over 34,000 organizations that have previously received funding, we are provided various inputs for the model. As the goal is to identify and accurately predict successful investments, the "IS_SUCCESSFUL" column was used to split into the features and target arrays. After pre-processing, splitting the training/testing datasets, and processing it through the neural network and sequential models respectively, the machine learning model produces 99.8% predicitive accuracy. This was achieved by:

* First hidden layer: 200 hidden nodes
* Second hidden layer: 100 hidden nodes
* Output layer: 1 node

Through trials, it is observed that increasing the hidden nodes will increase the predicitive accuracy.

*Note: for column "IS_SUCCESSFUL", it is assumed that "0" = "N" and "1" = "Y".
