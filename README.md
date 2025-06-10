<h1 style="text-align: center;">CHURN PREDICTION ANALYSIS FOR BLUE-VALLEY BANK</h1>

<img src='bank photo.jpg'>
<h3 style="font-size:36px;">Overview</h3>


<body>
At the Blue-Valley Bank,we noticed a worrying trend that clients were leaving and by the time this was realized it was too late to keep them.As the senior data scientist ,i led and investigation into five years of operational data to understand the root cause of these losses.By exploring features in the data uncovering of hidden signals that indicated customers churning was indentified

Using these insights we built a predictive model to segment customers by their churn risk that is high,moderate and low.Through this  the model transformed the bank's approach from reacting after the fact to proactively reaching out to vulnerable clients.Now armed with the model built the Blue valley bank is at a better position to retain valuable clients and prevent losses
</body>

<h3 style="font-size:36px;">Business Understanding</h3>
The source of my data set is from kaggle https://www.kaggle.com/datasets/pentakrishnakishore/bank-customer-churn-data 
    
My dataset is relevant since it has columns like age ,vintage which shows how long a client has stayed in a bank,customer net worth,last transaction which when doing feature engineering we can check how many days since the last transaction was done,we have dependents these are the people rellying upon the client,we have occupation what the client does we have the monthly ,average and current balances that helps us gauge what balance the clients have.
<h3 style="font-size:36px;"><b>Problem Statement</b></h3>
<body>
Blue-Valley Bank has faced rising customer churn over the past five years,resulting in significant financial losses.The bank lacked a way to predict which customers were at risk of leavinf early enough to intervene.This project focuses on analyzing customer data to build a suitable  predictive model that identifies high risk churners and supports targeted retention efforts
</body>    
<h3 style="font-size:36px;">Main Objective</h3>
<body>
    How can we predict which clients of Blue-Valley bank are likely to churn and how can we segment them based on their churn risk using an appropriate predictive model?
    </body>
    <h3 style="font-size:36px;">Specific Objective</h3>
<ul>
<li>Which features most influence features will influence churn?</li>
<li>Which predictive model between logistic and decision tree will most effectively identify clients likely to churn in terms of performance?</li>
<li>How can clients be segmented into high,moderate and low churn risk categories based on their predicated probability of churning?</li>
</ul>
<h3 style="font-size:36px;">DATA UNDERSTANDING</h3>
 We have 28382 entries with 21 columns 6 integer columns 3 objects and 11 float columns
 <h3 style="font-size:36px;">DATA PREPARATION</h3>
 There was presence of outliers and we removed,missing values were dropped and changed date to its right format
<img src='outliers.jpg'>
<h4 style="font-size:36px;">EXPLORATIVE DATA ANALYSIS</h4>
we observed skeweness,imbalance and did feature engineering too
<img src='imbalance.jpg'>
<img src='skewness.jpg'>

