# CREDIT-CARD-FRAUD-DETECTION-USING-SUPERVISED-LEARNING-WITH-FEATURE-ENGINEERING-

Problem statement:-

The aim of the project is to predict fraudulent credit card transactions using machine learning models. This is crucial from the bank’s as well as customer’s perspective. The banks cannot afford to lose their customers’ money to fraudsters. Every fraud is a loss to the bank as the bank is responsible for the fraud transactions.

The dataset contains transactions made over a period of two days in September 2013 by European credit cardholders. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions. We need to take care of the data imbalance while building the model and come up with the best model by trying various algorithms.

The datasets contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class
(frauds) account for 0.172% of all transactions.

Steps in Implementing Credit Card Fraud Detection:-

The steps are broadly divided into below steps. The sub steps are also listed while we approach each of the steps.
Reading, understanding and visualising the data
Preparing the data for modelling
Building the model
Evaluate the model

We have used a total of 5 algorithms in our project
1. Logistic Regression
2. K-Nearest Neighbours
3. Decision Tree
4. Random Forest
5. XgBoost

Six Techniques are used for undersampling or oversampling
1. Random oversampling
2. SMOTE Oversampling
3. Random Undersampling
4. Tomek Links Undersampling
5. Cluster centroids undersampling
6. SMOTE + Tomek Links

We have compared each of the 5 algorithms in all 7 (Normal data + Six undersampled or oversampled data) scenarios comparing their accuracy through Area under curve of ROC Curve.

The results show to the company that there is a clear performance gain when the model is updated more frequently, e.g. once a week or every 15 days. We also used different classification algorithms. In particular, XgBoost has emerged as the best algorithm in many simulations. We actually used 5 different algorithms i.e. Logistic Regression, K nearest neighbours, Decision tree, Random forest and XGBoost Algorithms. We concluded that XGboost performed far better than other algorithms in all scenarios.

The results of also showed that, in case of fraud detection, the performance of a classifier can be significantly improved when sampling methods are used to rebalance the two classes.

Given the large imbalance ratio and number of transactions, over sampling should perhaps be favoured w.r.t. under sampling techniques. We have analysed various different types of oversampling and undersampling techniques. The various types were Random oversampling and SMOTE technique for oversampling and random, tomek links and cluster centroids for undersampling.We also used a combination of SMOTE and Tomek links. We found out that SMOTE and SMOTE with Tomek Links gave very good results as compared to others. Cluster centroids performed the worst.

Installation, Setup, and Execution

1. Download the project Credit Card Fraud Detection Using Machine Learning
2. Extract the downloaded project into your computer
3. Follow the link to Download the dataset and Extractinto project directory
	https://drive.google.com/file/d/1YUiJpUcrAYWkzzYTdRI7jkJUStLrDsu3/view?usp=sharing
	
	
Local Machine Version

1. Install Anaconda IDE
2. Goto the project directory
3. Open Jupyter Notebook
4. Open the Credit Card Fraud Detection Using Machine Learning - Local Version
5. Execute all cells

Google Colab Version
1. https://colab.research.google.com/
2. Login with your Gmail acount
3. Upload the Credit Card Fraud Detection Using Machine Learning - Local Version - Colab version
4. Run all cells

