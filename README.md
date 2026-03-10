# Credit Risk IFRS9

Credit risk modelling project focused on IFRS 9 Expected Credit Loss estimation using loan-level data.

## Project objective

This repository builds an end-to-end credit risk pipeline to estimate and analyse expected credit losses through the main risk components:

- Probability of Default (PD)
- Loss Given Default (LGD)
- Exposure at Default (EAD)
- Expected Credit Loss (ECL)

The project is designed as a portfolio-grade risk analytics repository combining reproducible data preparation, predictive modelling and portfolio risk analysis.

## Dataset

The project uses Lending Club loan data as a proxy for a retail lending portfolio.

## Repository structure

data  
raw and processed datasets

notebooks  
analysis workflow and modelling

src  
reusable functions for data preparation, features and modelling

reports  
figures and tables generated in the analysis

docs  
methodology notes and variable documentation

## Workflow

1 Data loading and cleaning  
2 Exploratory data analysis  
3 Feature engineering  
4 PD modelling  
5 LGD and EAD modelling  
6 IFRS9 Expected Credit Loss estimation  
7 Portfolio segmentation and reporting

## Tools

Python  
pandas  
numpy  
scikit-learn  
xgboost  
matplotlib  
seaborn  

## Author

Alejandro Palomo Morales