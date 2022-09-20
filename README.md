# Imbalanced-classification-problem-with-GAIN-LIFT-chart

In this project, I have demonstrated GAIN & LIFT chart - two measures that are used for measuring the benefits of using the logistic regression model and are used in business context such as target marketing, customer churn rate, customer conversions rate.

In target marketing or marketing campaigns, customers' responses to campaign are usually very low, somtimes less than 1%. Another example of such low conversion rate is response to advertisement on the internet such as google adwords and mobile advertisements.

The organization incurs cost for each customer contact and hence would like to minimize the cost of marketing campaign and at the same time achieve the desired response level from the customers.

Formula for Gain and Lift is as below:

`GAIN = (Cumulative number of positive observations upto decile i)/(Total number of positive observations in the data)`

`LIFT = (Cumulative number of positive observations upto decile i using Logistic model)/(Cumulative number of positive observations upto decile i based on random model)`

Apart from this we will also create decision tree graph using pydotplus and graphVIZ API

Dataset is taken from UCI's ML repository and it is a part of the book Machine learning using python by U Dinesh kumar

## Feature descriptions:

1) age - Age of the client
2) job - type of job
3) marital - marital status
4) education - education qualification
5) default - customer has credit in default? (yes/no)
6) balance - average yearly balance, in euros
7) housing-loan - has housing loan?(yes/no)
8) personal-loan - has personal loan? (yes/no)
9) current camoaign - number of contact performed during this campaign
10) previos campaign - number of contact performed before this campaign
11) subscribed(Target) - subscribed or not for term deposit? (yes/no)

##  Objectives and Tasks:

- To build logistic regression model on imbalanced class dataset
- Demonstrate GAIN-LIFT chart for imbalanced class classification problem
- Decision tree model with graphVIZ API to visualize decision tree chart

## Results and learnings:

1) Learned use-case of GAIN-LIFT charts to solve imbalanced class classification problem
2) Learned use-case of decision tree visualization to make decisions based on decision tree charts
