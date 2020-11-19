# Credit_Card_Approval_Predictor

I have created this project to explore my curiosity and to get a taste of how commercial banks 🏦 accept or reject applications requesting credit cards. Times have changed and today, commercial banks receive a lot of applications for credit cards. At my bank branch, I had inquired as to why credit card applications are rejected and I was provided with a couple of potential reasons like an unusually high number of inquiries on an individual's credit report, high loan balances, and low-income balances to name a few.     

In my understanding, banks are definitely not analyzing these applications manually as it would be a mundane, error-prone, and time-consuming process and in this notebook, I have tried to use the power of machine learning to build an automatic credit card approval using machine learning techniques.   

The dataset we are using for this project is from the UCI Machine Learning Repository and can be downloaded found - <a href = "http://archive.ics.uci.edu/ml/datasets/credit+approval">here </a> The dataset can also be found in the project repository.

## Flow of the Notebook

The flow of the project is as follows -

1. Load and inspect the dataset.  

2. Explore the numerical and non-numerical features that the notebook has. In addition, as mentioned in the dataset description we have to deal with values having different ranges and the missing values.  

3. Preprocess the model to ensure the machine learning model we choose can make good predictions.       

4. After preprocessing is complete, we need to do some EDA or Exploratory Data Analysis to build our intuition.    

5. Finally we try to build a machine learning model that can predict if an indivisual's application for a credit card will be accepted or not ?

## Repository Structure

Repositorty Credit_Card_Approval_Predictor contains -

* <code>final_notebook.ipynb</code> -- The main jupyter notebook.    

* <code>README.md</code>  -- The readme file for this repository.   

* <code>data</code> -- The dataset folder which contains <code>cc_approvals.data</code> dataset.   

* <code>LICENSE</code>  -- The MIT LICENSE File for this repository. 

## Packages   

The ipython notebook uses python 3 (https://www.python.org/download/releases/3.0/) and the folowing python packages:

* numpy == 1.18.5     
* pandas == 1.0.5        
* matplotlib == 3.2.2      
* seaborn == 0.10.1      
* scikit-learn == 0.23.1         

## What makes this interesting ?        

* This project is interesting to me as it gives me a taste of the real world data.

* Since the data was sensitive, its anonymized and I had to research through articles to understand how to deal with such data.   

* I had to deal with some of the most widely-known preprocessing steps such as scaling, label encoding, and missing value imputation.    
