# Module 12 Report

## Overview of the Analysis

Lending companies provide loans to borrowers with the anticipation that the borrower will either return or repay the loan. Credit Risk arises when a borrower fails to do this, resulting in losses for the lender. Lenders assess the risk through various methods, but in this study, we will use Machine Learning to examine a dataset of past lending transactions from a peer-to-peer lending platform. The objective is to develop a model that can assess the creditworthiness of borrowers.

I used a machine learning model to determine if loans are safe (low-risk) or risky (high-risk) based on the loan status provided by the lending company, developing a Logistic Regression Model.

## Results

In comparison to the original dataset, the number of healthy loans is greater than the number of unhealthy loans.
The model has a good accuracy model of 99%, the precision score for 0 (healthy loans) is 100% and the precision for 1 labels is not bad at 85%.
The recall score is also quite high at 99% for prediction of 0 labels and 91% for high-risk loans with the label 1.

## Summary

The model performs well, and predict both '0's and '1's with over 90% accuracy.
It feels more important to correctly predict high-risk loans than to correctly predict healthy loans for this particular problem.