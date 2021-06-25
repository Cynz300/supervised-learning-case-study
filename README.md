## Case Study

Today we are going to use all the skills we have learned to tackle a real
problem in industry. The problem is churn prediction with a ride-sharing
company in San Francisco.  Since the data is sourced from a real company, we
ask you not to share the dataset. See more about the problem in
[group.md](group.md). 

## Table of Contents


1. [Overview](#Overview)
    1. [The Data](#The-Data)
    1. [Project Goals](##Project-Goals)
1. [Data Wrangling](##Data-Wrangling)
1. [EDA](#EDA)
    1. [Importing & DataFraming](##Importing-&-DataFraming)
    
1. [Model Analyses](#Model-Analyses)
1. [Visualizations](#Visualizations)
    1. [Slide Deck](https://docs.google.com/presentation/d/1IN5UFuAzI6oDC38MMX2rFdKyShlF5065ZbD-_D--Lm4/edit#slide=id.p5)

# Team SAIL

Sasha Sabater 

Aqeel Ali

Ilya Getsin

Liben Hagos 

## The Data

We have 40,000 rows by [NUM COLUMNS] columns, containined ___ features. 

We had to clean NaNs

Our first glance at notable features included average ratings by driver and of driver. 

surge pct would be interested in comparing / showcasing customer's willingness to pay. 

16% of the data f
- we felt this was a significant part of the data and wanted to
- in order to attain a proper way to fill the data, we conducted a paired sample t-test to test for idfferences. If there's a statistictially significant difference, we'd fill in with the mean. If not, we'd set that row's value of 'by driver' to be the same as 'of driver.' 
- we had a test statistic of 41, and given that our means were within 0.2 (out of 5) from each other, so we filled the NaNs with the column mean. 

when there IS a rating of the driver, there is 41% retention (of ~33,000) of app users.

when there is NO rating for the driver, there is 20% attention (of ~6,000) of app users. 

when there IS a rating of the driver, there is 31% retention (of ~33,000) of app users.

when there is NO rating by the driver, there is 10% attention (of ~6,000) of app users. 

## EDA 

1. Initially cleaning data 
2. Cleaning 
3. Dropping columns of irrelevance ??

churn.corr
- luxury car users are more likely, 

[Insert scatter matrix plot here]



## Discovery

Conducting Feature importance:


Using pd.corr():
PHONE type to geographic location has impacts


# Model Analyses

Baseline model has:
print(np.mean(scores['test_acc']))

​

print(np.mean(scores['test_prec']))  

​

print(np.mean(scores['test_rec']))  

0.7571500000000001
0.6819445955994825
0.6633189295168529

Baseline Model Feature importance:

Feature #0: avg_dist, Score: 0.29977796903502507
Feature #1: avg_rating_by_driver, Score: 0.10940844267320009
Feature #2: avg_rating_of_driver, Score: 0.07047895716175374
Feature #3: avg_surge, Score: 0.06927725857030959
Feature #4: surge_pct, Score: 0.08292960227797312
Feature #5: trips_in_first_30_days, Score: 0.08013858160502824
Feature #6: luxury_car_user, Score: 0.03182962055024575
## Findings

# Visualizations
1. [Slide Deck](https://docs.google.com/presentation/d/1IN5UFuAzI6oDC38MMX2rFdKyShlF5065ZbD-_D--Lm4/edit#slide=id.p5)

