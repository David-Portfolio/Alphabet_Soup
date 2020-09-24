The purpose of this project is to use machine learning techniques to support future funding decisions from Alphabet Soup. The csv file provides over 34,000 organizations that have previously received funding. After pre-processing the data, we are able to run our model.

* Layer 1: 20 neurons, activation = "relu"
* Layer 2: 10 neurons, activation = "relu"
* Layer 3: 1 neurons, activation = "sigmoid"

<img width="203" alt="Model Accuracy - Test Dataset" src="https://user-images.githubusercontent.com/65242270/94119517-e0e9d800-fe03-11ea-99ee-4ee51c219da7.PNG">
Model performance: ~81% accuracy

<img width="207" alt="Model Accuracy - Train Dataset" src="https://user-images.githubusercontent.com/65242270/94119522-e34c3200-fe03-11ea-80d2-420c0dbff5c3.PNG">
Model performance: ~77% accuracy<br />

Both the test and train dataset achieved the model target performance (over 75% accuracy).

*Note: it is assumed that for column "IS_SUCCESSFUL" that "0" = "N" and "1" = "Y", and for column "STATUS" that "0" = "Not Active" and "1" = "Active".
