The purpose of this project is to use machine learning techniques to support future funding decisions from Alphabet Soup. The csv file provides over 34,000 organizations that have previously received funding. After pre-processing the data, we are able to run our model.

* Layer 1: 100 neurons, activation = "relu"
* Layer 2: 50 neurons, activation = "relu"
* Layer 3: 1 neurons, activation = "sigmoid"

<img width="198" alt="Model Accuracy - Test Dataset" src="https://user-images.githubusercontent.com/65242270/94314735-04ad3b00-ff36-11ea-910e-b704a950fabd.PNG">

Model performance: ~78% accuracy

<img width="197" alt="Model Accuracy - Train Dataset" src="https://user-images.githubusercontent.com/65242270/94314747-07a82b80-ff36-11ea-8503-72197a23e887.PNG">

Model performance: ~77% accuracy <br />


Both the test and train dataset achieved the model target performance (over 75% accuracy).

*Note: it is assumed that for column "IS_SUCCESSFUL" that "0" = "N" and "1" = "Y", and for column "STATUS" that "0" = "Not Active" and "1" = "Active".
