The purpose of this project is to use machine learning techniques to support future funding decisions from Alphabet Soup. The csv file provides over 34,000 organizations that have previously received funding. After pre-processing the data, we are able to run our model.

* Layer 1: 20 neurons
* Layer 2: 15 neurons
* Layer 3: 10 neurons
* Layer 4: 5 neurons
* Layer 5: 1 neurons

<img width="237" alt="Model Accuracy - Test Dataset" src="https://user-images.githubusercontent.com/65242270/94116979-8733de80-fe00-11ea-9d20-d6716f05c945.PNG">

<img width="230" alt="Model Accuracy - Train Dataset" src="https://user-images.githubusercontent.com/65242270/94116995-8b5ffc00-fe00-11ea-8610-603428d6faf6.PNG">

Both the test (~80%) and train (~77%) dataset achieved the model target performance (over 75% accuracy).

*Note: it is assumed that for column "IS_SUCCESSFUL" that "0" = "N" and "1" = "Y", and for column "STATUS" that "0" = "Not Active" and "1" = "Active".
