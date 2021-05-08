# Detecting-Scam-Emails-Using-Machine-Learning-

Have you ever wanted to learn how to detect scams in emails? In this Github, I go in-depth on building different machine learning models to do just that. This Github requires a basic knowledge of Python and Pandas to be able to build the model. We will use Sci-kit Learn's machine learning library to build algorithms to detect whether the email is a scam or not. We will be using [UCI's Scambase Dataset](https://archive.ics.uci.edu/ml/datasets/spambase), which includes a list of features and a classification if it is a scam (1) or not(0). You can see the data and the data definitions through the Scambase website.

The results of the models are below:
<img width="259" alt="Screen Shot 2021-05-07 at 11 30 47 PM" src="https://user-images.githubusercontent.com/71193439/117524833-5bc7c380-af8d-11eb-9b2f-a6fd5d2e942e.png">

As you can see, the Second Random Forest Classification, XGBoost, and AdaBoost Classifier were very close and had an accuracy of 95%. The #1 predictor I found for classifying emails as spam or not spam is "char_freq_%21".
