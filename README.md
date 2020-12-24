# Santander-Product-Recommendation
Under their current system, a small number of Santander’s customers receive many recommendations while many others rarely see any resulting in an uneven customer experience. This project is to predict which products their existing customers will use in the next month based on their past behavior and that of similar customers.

Adding the Presentation 1 python notebook to master branch.

Exploratory Data Analysis
=====================================
Visualizations of the data using Seaborn and Matplotlib libraries
Images attached

Evaluation Criteria
=====================================
**Evaluation** =  Map@5 [Map@k]
Need to predict top 5 products, offered by the Santander Bank of Spain, for each customer that they are going to add or drop in the month of May,2016

Data
=====================================
Span of data = From January,2015 to April,2016 (1,27,15,856)
Test Data = May,2016(9,31,453)

Models
=====================================
1. ***Logistic Regression*** = Public Score (0.02572)
2. ***XGBClassifier*** =  Public Score(0.04392)