# AmExpert CodeLab-2021

Credit Default risk is the chance that companies or individuals will not be able to return the money lent on time. 
Details of the competition can be found [here](https://www.hackerearth.com/challenges/competitive/amexpert-code-lab/machine-learning/credit-card-default-risk-5-95cbc85f/).

### Task
You are given the relevant information about the customers of a company. You are required to build a machine learning model that can predict if there will be credit card default. 

### Data Description

| __Variable__ | __Description__ |
|-------------|------------|
| customer_id          | Represents the unique identification of a customer    |
| name          | Name of the customer |
| age  |Ae of the customer |
| gender | Gender of the customer |
| owns_car | Represents whether the customer owns a car (Y means Yes, Nmeans No) |
| owns_house | Represents whether the customer owns a house (Y means Yes, Nmeans No) |
| no_of_children | Represents the number of children of the customer |
| net_yearly_income | Represents the net yearly income of a customer |
| no_of_days_employed | Represents the number of days the customer is employed |
| occupation_type | Represents the occupation type of the customer (IT staff, Managers, Accountant etc.) |
| total_family_members | Represents the family members of the customer |
| migrant_worker | Represents whether the customer is a migrant worker (1 means Yes, 0 means No) |
| yearly_debt_payments | Represents the yearly debt payments of a customer (in USD) |
| credit_limit | Represents the credit limitof the customer (in USD) |
| credit_limit_used(%) | Represents the percentage of total credit limit used by the customer |
| credit_score | Represents the credit score of the customer |
| prev_defaults | Represents the number of previous defaults by the customer |
| default_in_last_6months | Represents whether the customer has defaulted in last 6 months (1 means Yes, 0 means No) |
| credit_card_default | Represents whether there will be credit card default (1 means Yes, 0 means No) |

### Evaluation Metric
The evaluation metrics for this competition is 100*(metrics.f1_score(actual,predicted,average="macro"))

### Leaderboad
LB Score: 92.63609
LB Rank: 31/615
Link to the Leaderboard can be found [here](https://www.hackerearth.com/challenges/competitive/amexpert-code-lab/leaderboard/credit-card-default-risk-5-95cbc85f/).

### Approach
The detailed approach and insights found during the Exploratory Data Analysis can be found in the Approach_Document word file in the repository. 



