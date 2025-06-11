<h1 style="text-align: center;">CHURN PREDICTION ANALYSIS FOR BLUE-VALLEY BANK</h1>
<img src="bank photo.jpg" width="1000" height="700">
<h3 style="font-size:36px;">Business Understanding</h3>
The source of my data set is from kaggle https://www.kaggle.com/datasets/pentakrishnakishore/bank-customer-churn-data 
    
My dataset is relevant since it has columns like age ,vintage which shows how long a client has stayed in a bank,customer net worth,last transaction which when doing feature engineering we can check how many days since the last transaction was done,we have dependents these are the people rellying upon the client,we have occupation what the client does we have the monthly ,average and current balances that helps us gauge what balance the clients have.
<h3 style="font-size:36px;"><b>Problem Statement</b></h3>
<body>
Blue-Valley Bank has faced rising customer churn over the past five years,resulting in significant financial losses.The bank lacked a way to predict which customers were at risk of leavinf early enough to intervene.This project focuses on analyzing customer data to build a suitable  predictive model that identifies high risk churners and supports targeted retention efforts
</body>
<h3> DATA UNDERSTANDING  AND ANALYSIS</h3>
we observed data imbalance,skewness and outliers which we scaled to prevent data biasness

<h3> DATA ANALYSIS BASED ON OBJECTIVES</h3>
in objective 1::Which features most influence whether a client will churn or not at Blue-Valley Bank</h3>
<ol>
    for logistic regression this was the most influencing features are 
    <img src='logistic.png',width="1000",height="700">
    
    for decision trees regression we have the most influencing features and they are:
    <img src='decision_trees.png'width='1000',height='700'>
    
    based on the two the logistic regression features are highly influenced by one hot encoding making occupation and gender to be the most coefficient since they were not scaled since it was categorical column
    while decision trees since it was affected by one hot encoding and also checks for non linear relationship current balance took the lead
  
    <b>in objective 2:which is which model between decision trees and logistic regression performed better than the other</b>
    for this we can see logistic regression has :
Accuracy-72%
F1score-26%
Recall-24%
Precision-23%
for decision trees
Accuracy-76%
F1score-51%
Recall-61%
Precision:43%
based on the two models decision trees performs way better than logistic regression though we need some prunning due to overfitting
    and our model improved
<b> in objective 3 we segmented the clients based on high low and medium risk features and this helped in customized retention strategy
    <img src="segment.png" width="1000" height="700">
 in conclusion the project
 Give an early warning system for customer churn will help in early planning 
Clear understanding of customers leaving
Has risk based segmentation that better engages with clients better
Its realiable in churning since it uses a better model in prediction

    