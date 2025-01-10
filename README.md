# Introduction
## Background Information

The occurrence of bankruptcies that are linked to business failures is becoming a common concern for many companies and their stakeholders. They can occur through the natural course of progression (such as smartphone cameras replacing the non-professional dedicated camera market), or be exacerbated through exogenous shocks (such as the dot-com bubble of 2001, or the 2007 financial crisis).

## Predictive Question

In this analysis, we will determine if we can predict the looming bankruptcy of a company based on a variety of fundamental financial metrics, specifically related to debt and liabilities. Moreover, we will be looking at metrics that may indicate an imminent bankruptcy as opposed to a drawn-out downfall.

## Dataset

We will use the Taiwanese Bankruptcy Prediction dataset from the Taiwan Economic Journal (TEJ), spanning from 1999-2009. Since its 1990 inception, the TEJ has focused on delivering essential financial market data. Within this 1999-2009 period, the TEJ recorded 220 observations of bankruptcy within the total 6,819 observations they collected data on (“About TEJ - TEJ,” 2023). Company bankruptcy was defined based on the business rules of the Taiwan Stock Exchange (Lyon, 2017). The dataset comes from the UCI Machine Learning Repository.

The dataset includes 95 columns of financial metrics, and a 96th column for a bankruptcy flag (yes/no). We will use the bankruptcy flag as our classification variable.
