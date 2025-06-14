# Drivers of Perceived Rental Property Quality – OLR Analysis

This project analyses tenant reviews from [shitrentals.org](https://shitrentals.org/) to identify key predictors of rental property quality using **Ordinal Logistic Regression (OLR)**. The dataset contains rental information across Sydney suburbs in 2023.

## 📌 Objective
To predict the perceived quality of rental properties (scores from 1 to 5) based on features such as:
- Weekly rental price
- Suburb
- Number of bedrooms
- Sentiment from review text
- Lessor type (Agency vs Private)

## 🧪 Methodology
- **Exploratory Data Analysis (EDA)**: Identified trends across suburbs, rental price ranges, and score distributions.
- **Ordinal Logistic Regression (OLR)**: Selected for modelling ordinal outcomes (rental quality scores).
- **Model Comparison**: Evaluated 4 models using AIC, BIC, accuracy, and precision to select the best-performing model.

## 🏆 Key Findings
- **Weekly rental price** is significantly associated with higher rental quality scores.
- **Suburb (Redfern)** has a strong positive association with perceived quality.
- **Sentiment and number of bedrooms** showed potential influence but were not statistically significant in the final model.
- The best-performing model achieved **87% accuracy**.
