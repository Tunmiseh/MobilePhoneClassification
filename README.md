# **Mobile Phone Classification**
The mobile phone classificationm is about a Businessman named Bob who wants to start his own mobile company, but he doesn't knmow the price estimate to give the phones created by his company.  To solve this problem he collects sales data of mobile phones of various companies. Using this data, he wants to find out the relationship between the features of a mobile phone and its price range.
## Overview of the database
The dataset was gotten from kaggle (https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification?select=train.csv)
The dataset consists of 21 columns and 2000 rows. 
The data consists of 2 datasets the train.csv and test.csv. The two datasets share the same column names. 
Some of the column names includes:
1. battery_power
2. blue
3. clock_speed
4. dual_sim
5. int_memory
6. ram
7. n_cores
8. 4g
9. 3g
## Data Visualization
For my data visualization, I used a pairplot, through which I was able to visualize the insights i gained from the dataset
## Machine learning 
for my machine learning i used 3 models
1. LogisticREgression
2. DecisionTreeClassifier
3. RandonForestClassifier

## Endnotes
I was able to create a model that can classify a pnone into low cost(1), medium cost(2), high cost(3) and very high cost(4) based on the phone features
i was also able to predict a class for the test.csv which doesn't have a target
