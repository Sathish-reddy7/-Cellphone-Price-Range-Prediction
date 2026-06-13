#  Cellphone Price Range Prediction

## Overview
This project predicts the price range of mobile phones 
(Low, Medium, High, Very High) based on hardware 
specifications like RAM, battery power, camera quality 
and screen resolution.

## Problem Statement
A startup mobile company wants to understand how phone 
specifications relate to pricing, in order to position 
their products competitively in the market.

## Dataset
- 2000 mobile phone records
- 20 features including RAM, battery power, screen 
  resolution, camera specs etc.
- Target: price_range (0=Low, 1=Medium, 2=High, 3=Very High)

## Approach
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Trained and compared 5 models: Logistic Regression, 
  Decision Tree, Random Forest, KNN, XGBoost

## Results
| Model | Accuracy |
|---|---|
| Logistic Regression | 97.75% |
| XGBoost (tuned) | 90.75% |
| Random Forest | 89% |
| Decision Tree (improved) | 86% |
| KNN (K=25) | 59.75% |

**Best Model:** Logistic Regression — selected for production 
due to highest accuracy, simplicity and interpretability.

## Key Insight
RAM has a 0.92 correlation with price range — making it 
the single most important factor in determining a phone's 
price tier.

## Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost
