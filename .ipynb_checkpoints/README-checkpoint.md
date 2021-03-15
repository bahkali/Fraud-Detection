# Detecting Payment Card Fraud
Using credit card fraud detection dataset we'll build a binary classification model that can identify transactions as either fraudulent or valid, based on provided, *historical* data. In a [2016 study](https://nilsonreport.com/upload/content_promo/The_Nilson_Report_10-17-2016.pdf), it was estimated that credit card fraud was responsible for over 20 billion dollars in loss, worldwide. 
Accurately detecting cases of fraud is an ongoing area of research.

![](notebook_ims/fraud_detection.png)

### Binary Classification

Since we have true labels to aim for, we'll take a **supervised learning** approach and train a binary classifier to sort data into one of our two transaction classes: fraudulent or valid.  We'll train a model on training data and see how well it generalizes on some test data.

![](notebook_ims/linear_separator.png)

The notebook will be broken down into a few steps:
* Loading and exploring the data
* Splitting the data into train/test sets
* Defining and training a LinearLearner, binary classifier
* Making improvements on the model
* Evaluating and comparing model test performance