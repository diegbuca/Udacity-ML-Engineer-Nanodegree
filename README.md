# Starbucks Capstone Project

This is the Capstone Project for the Udacity Machine Learning Nanodegree Program

## Project Overview

Udacity created a partnership with Starbucks in order to analyse a dataset that mimics customer behaviour on offers that Starbucks extended via the App. The aim of this project is to analyse the dataset and develop a machine learning algorithm to improve how offers are targeted to customers.

## Files

- **data/portfolio.json** - This file contains info about the offers. 10 Offers are included in the file.
- **data/profile.json** - Demographic data on 17000 customers.
- **data/transcript.json** - Data on customer events which includes both transactions and offers. 
- **Project Proposal.ipynb** - The Project proposal
- **Capstone Project.ipynb** - Python code used to develop the ML algorithm and to analyse the data
- **project report.pdf** - The project report 

## Results 

Random Forest is the model with the highest accuracy on test set.

|                  Model                   | Accuracy|
| :--------------------------------------: | :------:|
|   Logistic Regression __\[test set\]__   | 0.7855  |
| Random Forest Classifier __\[test set\]__| 0.8575  |
| XGBoost Classifier __\[test set\]__      | 0.8555  |

The following features are the most influential in determining the offer acceptance:

![Image](FeatureImportance.png)
