# PHISHCOOP phishing website detection
Detection of phishing websites is a really important safety measure for most of the online platforms. So, as to save a platform with malicious requests from such websites, it is important to have a robust phishing detection system in place.

## DATA SELECTION LIKE A EXPERT

The dataset is downloaded from UCI machine learning repository. The dataset contains 31 columns, with 30 features and 1 target. The dataset has 2456 observations.

## MODELS

To fit the models over the dataset the dataset is split into training and testing sets. The split ratio is 75-25.  Where in 75% accounts to training set. 

Now the training set is used to train the classifier. The classifiers chosen are:  
#### * Logistic Regression
#### * Random Forest Classification
#### * Support Vector Machine

We will see which one fits best in our dataset.

### 1.Logistic Regression

Fitting logistic regression and creating confusion matrix of predicted values and real values I was able to get 92.3 accuracy. Which was good for a logistic regression model.

### 2.Support Vector Machine

Support vector machine with a rbf kernel and using gridsearchcv to predict best parameters for svm was a really good choice, and fitting the model with predicted best parameters I was able to get 96.47 accuracy which is pretty good.

### 3.Random Forest Classification

Next model I wanted to try was random forest and I will also get features importances using it, again using gridsearchcv to get best parameters and fitting best parameters to it I got very good accuracy 97.26.

Random forest was giving very good accuracy. We can also try artificial neural network to get a improved accuracy.

## FEATURE IMPORTANCES

![FEATURE IMPORTANCE](https://raw.githubusercontent.com/abhishekdid/PHISHCOOP-phishing-website-detection/master/variable_Importances.png)

