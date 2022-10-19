
# Win Prediction Analytics Capstone Project

In this project, you will analyse and predict the win possibilities of deals/projects for an IT consulting company and see how the possibility of winning a deal is impacted by other variables. This will enable the IT consulting company to manage the effort required to win a deal to meet the growth targets.  

## Market Outlook

IT firms compete for winning large deals by designing and proposing solutions to their clients. These deals often differ from each other in terms sector of the client, solution to be delivered, technology to be used and the scope of the project. The deal value can reach up to millions of dollars, which leads to highly competitive bidding processes. Even a marginal improvement in the win rate can result into substantial revenue addition for IT firm.

By predicting the probability of winning a deal, the engagement teams can prioritize the pipeline of opportunities to staff the most attractive options first. With the probability of winning known in advance, deal engagement manager can ensure that for the most profitable deals there are resources available.

## Overview Of the problem

You have been provided with a single file which contains data related to the projects/deals won or lost. This data contains the project category, price and sector from 2011 to 2018.

## Data and Problem Detail

Your organization puts in a lot of effort in bidding preparation with no indications whether it will be worth it. With multiple bid managers and SBU Heads willing to work on every opportunity, it becomes difficult for the management to decide which bid should be given to which bid manager and SBU Head. You are hired to help your organization identify the best bid manager-SBU Head combination who can convert an opportunity to win with the provided data points.

Objective 1: Predictive Analytics - Build a ML model to predict the probability of win/loss for bidding activities for a potential client.

Objective 2: Prescriptive Analytics – Identify variable/s that are most likely to help in converting an opportunity into a win.

## Tools Used

Python - Jupyter Notebook

Tableau

## Libraries Used 

Pandas

Numpy

Matplotlib

Seaborn

## Roadmap To The Project

### Exploratory Data Analysis

We have performed multi-variate analysis by create tables with the help of PrettyTable library to get the insight of the data for both Win-Lost counts as well as Win-Lost percentage.  

### Data Preprocessing

We have treat missing values by replacing it with mode.

Replaced the 0.00 value in Deal Cost column with mean and perform Logarithmic Transformation to balance the data as it was right skewed.

Removed Outliers by capping the extremes to 3rd inter Quartile Formula.

We have decided to opt for Target Encoding for Independent categorical variables and Label Encoding for dependent variable.

After this, We have performed Feature Selection with the help of HeatMap.

### Model Building

Before building the model we have splited our data into train and test by the ratio of 70:30 and Scaled the data.

We have used different models for building our model however Random-Forest-Classifier fit good in this data sets which is robust to the outliers and avoid the overfitting also gives the best accuracy as compared to others.

### Model Accuracy & Performance

We have got 84% of by RFC.


Note: 
This repository includes the information of a Capstone project which I had completed during my Data Science Prodegree Program.


