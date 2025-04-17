# Drug Perdiction Analysis

## Overview:
This repository contains Python code for analyzing a dataset related to drugs. The dataset, named 'Drug.csv', encompasses information on various drugs, including their effectiveness, ease of use, satisfaction ratings, medical conditions, and more.

## Dataset Description:
- The dataset comprises several columns including:
  - **Drug:** Name of the drug.
  - **Condition:** Medical condition for which the drug is prescribed.
  - **Type:** Type of drug.
  - **Indication:** Indication for drug usage.
  - **Information:** Additional information about the drug.
  - **Reviews:** Reviews associated with the drug.
  - **Effective:** Effectiveness rating of the drug.
  - **EaseOfUse:** Ease of use rating of the drug.
  - **Satisfaction:** Satisfaction rating of the drug.

## Analysis Tasks:
1. **Data Preprocessing:**
   - Initial data inspection, checking for missing values, and removing duplicates.
   - Converting data types and cleaning string data.

2. **Exploratory Data Analysis (EDA):**
   - Visualizing data distribution using histograms.
   - Calculating summary statistics and correlation between variables.
   - Analyzing top medical conditions, drugs, types, indications, and information.
   - Identifying top drugs based on effectiveness and ease of use.
   - Visualizing relationships between variables using scatter plots.
   - Performing linear regression analysis to predict effectiveness and satisfaction based on ease of use.

3. **Drug Recommendation:**
   - Recommending drugs for specific medical conditions based on effectiveness, ease of use, and satisfaction.

4. **Random Forest Classifier:**
   - Building a Random Forest classifier model to predict drug types based on various features.
   - Evaluating model performance using a confusion matrix and accuracy metric.
   - Making predictions for drug types based on the trained model.

## Dependencies:
- Python 3
- Required Python libraries: pandas, numpy, matplotlib, seaborn, statsmodels, scikit-learn

## Usage:
1. Ensure Python and the required libraries are installed.
2. Clone or download the repository.
3. Execute the Python script to perform data analysis and explore the results.

## Author:
Ravichabdra Lakkappa
