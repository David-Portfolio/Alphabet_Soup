The purpose of this project is to use machine learning techniques to support future funding decisions from Alphabet Soup. The csv file provides over 34,000 organizations that have previously received funding. After pre-processing the data, we are able to run our model.

* Layer 1: 20 neurons, activation = "relu"
* Layer 2: 10 neurons, activation = "relu"
* Layer 3: 1 neurons, activation = "sigmoid"

<img width="217" alt="Model Accuracy - Test Dataset" src="https://user-images.githubusercontent.com/65242270/94119287-8c465d00-fe03-11ea-9ba0-d9aff3f76d60.PNG">

<img width="242" alt="Model Accuracy - Train Dataset" src="https://user-images.githubusercontent.com/65242270/94119297-8fd9e400-fe03-11ea-9761-be6b91c3854f.PNG">

Both the test (~81% accuracy) and train (~77% accuracy) dataset achieved the model target performance (over 75% accuracy).

*Note: it is assumed that for column "IS_SUCCESSFUL" that "0" = "N" and "1" = "Y", and for column "STATUS" that "0" = "Not Active" and "1" = "Active".
