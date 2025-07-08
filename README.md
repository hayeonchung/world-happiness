# world-happiness
Capstone Project (Spring 2025)

# World Happiness Analysis – Capstone Project

This capstone project investigates what factors most influence country-level happiness, using a multivariable approach. We combined data from the World Happiness Report and global development indicators to uncover the strongest predictors of happiness using a combination of regression models, classification techniques, PCA, and composite scoring.

---

## Project Overview

- **Objective**: Explore which economic, health, and social variables best explain and predict happiness levels across countries.
- **Dataset**: World Happiness Report (2015–2021) merged with UN, WHO, and World Bank indicators.
- **Tools Used**: R, tidyverse, caret, FactoMineR, DALEX, glmnet

---

## Methods & Techniques

-  **Exploratory Data Analysis (EDA)**
-  **Multiple Linear Regression** (with variable selection + regularization)
-  **Classification Modeling** (Binary classification of high vs. low happiness using logistic regression and decision trees)
-  **Principal Component Analysis (PCA)**
-  **Principal Component Regression (PCR)**
-  **Composite Scoring of Domains**
-  **Cluster Analysis of Global Patterns**

---

## Project Structure

| File | Description |
|------|-------------|
| `Capstone Project - Technical Report.pdf` | Final capstone report |
| `visuals/` | Project visualizations (e.g., PCA plots, feature importance) |
| `snippets/` | R code snippets from each method |
| `README.md` | Overview of the project |

> **Note**: This was a group project. Each member contributed across different sections. I worked on multiple areas including regression analysis, classification modeling, visualization, interpretation, and collaborative writing.

---

## Key Findings

- **Regression results**: GDP per capita and life expectancy were strong predictors, but social trust and personal freedom became more significant once basic economic needs were met.
- **PCA**: Condensed multiple indicators into principal components representing economic strength, social infrastructure, and institutional trust.
- **Classification**: Binary models effectively predicted "high" vs. "low" happiness countries with accuracy over 80%.
- **Composite Scoring**: Highlighted regional strengths and weaknesses in happiness dimensions.
- **Clustering**: Grouped countries with similar happiness profiles, even when raw scores differed.

---

## Policy Relevance

This study shows that national well-being is driven by more than just economic success. To build happier societies, countries must invest in personal freedom, strong social support, healthcare access, and trustworthy institutions.

---

## Skills Demonstrated

R, Regression Modeling, Classification, PCA, Composite Scoring, Data Cleaning, Data Visualization, Clustering, Report Writing, Team Collaboration

---

## Links

-  GitHub Repository: https://github.com/hayeonchung/world-happiness-analysis

---

## Author

Hayeon Chung  
Capstone Project – B.A. in Applied Statistics, University of Virginia
