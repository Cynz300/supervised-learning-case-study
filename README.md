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
    1. [Slide Deck](https://docs.google.com/presentation/d/1iIjkURRV3yMbMUNnj3k_r3jpHNOrMHAOR2SaIU2j2O8/edit?usp=sharing)

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


[Insert scatter matrix plot here]

## Discovery

Notable features were:


# Model Analyses

## Findings

# Visualizations
1. [Slide Deck](https://docs.google.com/presentation/d/1iIjkURRV3yMbMUNnj3k_r3jpHNOrMHAOR2SaIU2j2O8/edit?usp=sharing)

