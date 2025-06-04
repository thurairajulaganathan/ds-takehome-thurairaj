# BonusLink Data Science Take-Home Assessment (Thurairaj)

## Overview
This repository contains my solution for the BonusLink Senior Data Analyst/Scientist take-home assessment. The objective was to predict member churn using transaction, member, and engagement data.

## Repository Structure
- `/assessment/`: The pdf answer file for 'ds-assessment-1' and 'ds-case-study-2' assessment.
- `/data/`: Datasets.
- `/notebooks/`: Jupyter notebooks with implementing the models, feature engineering, and modeling and evaluation.

## Approach Summary
1. **Problem Framing**: Defined churn as members with no transactions in the last 3 months.
2. **Feature Engineering**: Created aggregated spend, transaction counts, recency, engagement metrics, and demographic features.
3. **Modeling**: Built a logistic regression model pipeline using scikit-learn.
4. **Evaluation**: Used classification report, ROC AUC, precision-recall curves.
5. **Explainability**: Applied permutation importance to identify key drivers of churn.

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/ds-takehome-thurairaj.git
