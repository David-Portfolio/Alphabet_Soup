The purpose of this project is to use machine learning techniques to support future funding decisions from Alphabet Soup. The csv file provides over 34,000 organizations that have previously received funding. After pre-processing the data for optimization, we run our model.

* Layer 1: 100 neurons, activation = "relu"
* Layer 2: 50 neurons, activation = "relu"
* Layer 3: 1 neurons, activation = "sigmoid"

<img width="204" alt="Model Accuracy - Test Dataset" src="https://user-images.githubusercontent.com/65242270/94728848-b7eea900-0315-11eb-9053-13a2005067b0.PNG">

Model performance: ~77% accuracy

<img width="199" alt="Model Accuracy - Train Dataset" src="https://user-images.githubusercontent.com/65242270/94728859-bb823000-0315-11eb-8375-6e40c4014562.PNG">

Model performance: ~75% accuracy <br />


Both the test and train dataset achieved the model target performance (over 75% accuracy).

*Note: it is assumed that for column "IS_SUCCESSFUL" that "0" = "N" and "1" = "Y", and for column "STATUS" that "0" = "Not Active" and "1" = "Active".
