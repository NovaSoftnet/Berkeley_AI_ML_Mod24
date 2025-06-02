<center>
    <center>
        <img src = images/lstm.png width = 35%/>
    </center>
</center>

## Data Set Information:

The data belongs AC4MEX INC, a large IT firm that recently merged with one of their competitors, 
each original firm is now an independent Division of the new corporative group.
Even when some of their products overlap, they keep complementary product portfolios, 
and look forward to approach the combined customer base with product bundles from both division´s catalog. 
The Data was obtained from ACMEX INC Anual Bookings report. 
It is synthetic in nature and anonymized to obfuscate identifiable information.


#### Business Understanding

##### What is Data Driven go to Market strategy?

Out there every customer has plenty of options for every acquisition , we need to strenght our customer´s satisfaction and loyalty. At the same time we need to reduce the probability that competitors can take over our clients. Using Data Driven go to Market strategy, we will create product bundles with more attractive prices and promote synergy among different product business units to reduce production and marketing costs.

##### Why a Classifier Ensemble?

A classifier ensemble combines multiple classifiers to enhance classification accuracy and generalization. It's a technique where diverse individual classifiers are trained, and their predictions are combined using various methods like voting or averaging.

##### Why Oversampling ?
Imbalanced datasets impact the performance of the machine learning models and the Synthetic Minority Over-sampling Technique (SMOTE) addresses the class imbalance problem by generating synthetic samples for the minority class.

## Data Understanding
<pre>
Data Set Characteristics:  Multivariate
Area: Finance Department
Description:Single Sales order including products from the catalog of AC4MEX INC´s  two main divisions.
Attribute Characteristics: Categorical and Real
Missing Values? None
</pre>

#### Attribute Information:

The original Data Set includes 

Product_Line: Division the product belongs to.  
Product_Subline: The category from both Divisions (Security, CRM, Management, Collaboration,etc) the products belong to.
SKU Product_Class: The Product is hardware or software
Market_Segment : The customer belongs to COMMERCIAL, SMB, PUBLIC SECTOR ,ENTERPRISE ,etc
Vertical_Market: The customer business is:  Professional_Services,Financial_Services,Manufacturing,Government, etc
Region : Geographical Region the customer is based in.
Net_Price : Sales Order Net Price, after discounts.   
Customer_Hash : Customer´s unique ID


#### Instructions
<pre>
1) - Clone the GitHub repository

├──capstone_full_arnoguer_v1.ipynb
├── capstone_EDA_arnoguer_v2.ipynb
├──capstone_modeling_arnoguer_v2.ipynb
├── data
│    ├── Bookings_24_25_v2.cvs

2a) -Please run first **capstone_EDA_arnoguer_v2.ipynb**,  to execute the Exploration and Data Analisys to cleand and prepare the Data Set
    At the end of the this step, and additional File (Bookings_for_Modeling.csv) will show under the Data directory.

├── data
│    ├── Bookings_for_Modeling.cvs

 
2b)  -Please then the second notebook **capstone_modeling_arnoguer__v2.csv** to execute the creation, tuning and deployment of the modeling phase.


Note: A consolidated version of both phases is included as **capstone_full_arnoguer_v1.csv** for ilustrative purposes,
to review it please run  the notebook **capstone_full_arnoguer_v1.csv** for a full deployment

</pre>

## Data Preparation and Visulalization
<pre>
Code Used: Python
Packages: Pandas, Numpy, Matplotlib
</pre>
## Data Cleansing, processing, and modeling
<pre>
Code Used: Python
Packages: Pandas, Nunmpy , Sklearn:model_selection, metrics , preprocessing ,compose ,LogisticRegression,KNeighborsClassifier
,DecisionTreeClassifier,SVC,GridSearchCV,VotingClassifier
</pre>

## Process Summary
**By performing different ML models, we aimed to improve at predictively optimizing following**
- Operational efficiency
- Inventory optimization
- Reduce Marketing Costs
- Improve customers satisfaction
- Create synergy between product divisions



<center>
    <img src = images/copyright.png width = 15%, align = "right"/>
</center>
