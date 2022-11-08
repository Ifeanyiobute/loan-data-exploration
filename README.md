# Loan Data Exploration
## by Ifeanyichukwu Obute


## Dataset

The purpose of this project is to perform exploratory data analysis, then create a presentation with explanatory charts that conveys findings and insights from the data set provided.

The studied data set contains 113,937 loans with 81 variables on each loan provided by Prosper Marketplace, California-based pioneering company in the peer-to-peer lending industry in the U.S. The dataset can be found[here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv), with feature documentation available [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0)

## Summary of Findings

Over the course of various level of explorations, I found out somewhat significant patterns and relationships between variable of interest and other features. First of all, At different size of the monthly loan payment, the APR has a large range, but the range of APR decrease with the increase of loan payment. Overall, the borrower APR decrease with increase of monthly loan payment'

Secondly, The borrower APR increases with the increasingly better rating. Borrowers with the best Prosper ratings have the highest APR. It means that the Prosper rating has a strong effect on borrower APR.

Outside of the main variables of interest, I found that the state monthly income and monthly loan payment are positive correlation. These relationships could be explained in the way that customers with more stable monthly income can be approved with monthly loan payment. I also found that There are more 60 month loans on B and C ratings. 

## Key Insights for Presentation

For the presentation, I just focus on features that could affect the borrower APR.I started by showing the distribution of borrower APR.
Then, I showed the relationship between borrower APR vs. monthly loan payment as well as borrower APR vs. employment status. I also investigated the effect of rating on ralationship between APR and monthly loan payment, as well as the effect of term on relationship between borrower APR and monthly loan payment.