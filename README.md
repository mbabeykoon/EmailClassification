**#Email_Classification**
**Overview**
In this project, We'll apply various data engineering skills(natural language tool kit) to classify emails.

The project uses a data set which contains real emails. We will be creating various machine learning models(MLP Classifier,Multinomial Naive Bayes Classifier,Random Forest Classifier,Support Vector Classifier) to classify these emails.
The training set comes from a collection of emails. Each email was modeled as a \Bag of Words": a set of words present in the email along with its frequency of occurrence.
Some neutral words such as ‘the’, ‘a’, ‘an’ have been removed.

![image info](.jpg/confusion matrix.jpg)

## **Project Components**
There are two components we'll constitute the whole workfow of the project:

**1. Data clean**
In a Python script, email-classification.ipynb, create a data cleaning pipeline that:

.Loads the emails and categories datasets
.Remove stopwords
.Clean dataset
.Create dictonary
.Calculate tf-idf values
.Create data frame



**2. ML Models**

.Splits the dataset into training and test sets
.Builds a text processing and machine learning pipeline
.Trains MLP Classifier,Multinomial Naive Bayes Classifier,Random Forest Classifier,Support Vector Classifier
.Tunes a model using GridSearchCV
.Outputs results on the test set


Getting Started
This project deals with classification of emails. The training set comes from a collection of emails. Each email
was modeled as a \Bag of Words": a set of words present in the email along with its frequency of occurrence.
Some neutral words such as ‘the’, ‘a’, ‘an’ have been removed.
For the training set, you are provided with 9 files. The names of the files are, respectively, class A train.zip,
class B train.zip, ...... , and class I train.zip. Each of the files is given as a compressed archive. Each of the
compressed archive consists of several files. Each of these files consists of a list of words (one per line) along with
their frequency count. The files inside the archives class A train.zip to class I train.zip have their class labels as
the name of the compressed file. For example, a file named 1.res in compressed file class A train.zip has its class
label ‘A’. Using this training set you need to develop a model of the classifier.
A validation set with 9 files (class A validation.zip, class B validation.zip, ...... , class I validation.zip) is also
provided. It can be used to evaluate and select a classifier with the \best" performance, which is defined as the
misclassification rate, i.e., the number of misclassified emails in the test set divided the size of the test set.

Prerequisites
All the required packages and libraries are listed in file requirements.txt. They can be installed in venv using pip install requirements.txt.
