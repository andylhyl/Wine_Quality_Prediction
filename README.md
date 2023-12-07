# 🍷 Wine Quality Prediction Project

## 📜 Dataset Source:

This dataset pertains to the red and white variants of Portuguese "Vinho Verde" wine. The data is sourced from the following:

- **Paulo Cortez**, University of Minho, Guimarães, Portugal. [Link](http://www3.dsi.uminho.pt/pcortez)
- **A. Cerdeira, F. Almeida, T. Matos and J. Reis**, Viticulture Commission of the Vinho Verde Region(CVRVV), Porto, Portugal, 2009.
- The dataset is also available from the [UCI machine learning repository](https://archive.ics.uci.edu/ml/datasets/wine+quality).

## 📌 Dataset Description:

The dataset focuses on the physicochemical and sensory variables to measure wine quality. It does not include attributes like grape types, brand, or selling price.

Input Variables:

- Fixed acidity: Most acids involved with wine are fixed or nonvolatile.
- Volatile acidity: Represents the amount of acetic acid in wine. High levels can lead to a vinegar taste.
- Citric acid: Found in small quantities, it can add 'freshness' and flavor to wines.
- Residual sugar: Amount of sugar remaining post fermentation. Wines with >45 grams/liter are considered sweet.
- Chlorides: Amount of salt in the wine.
- Free sulfur dioxide: Prevents microbial growth and wine oxidation.
- Total sulfur dioxide: Represents both free and bound forms of SO2.
- Density: Close to that of water, varies with alcohol and sugar content.
- pH: Describes wine's acidity on a scale from 0 (very acidic) to 14 (very basic).
- Sulphates: Contributes to sulfur dioxide gas (SO2) levels.
- Alcohol: Percent alcohol content of the wine.

## 🎯 Prediction Problem:

The primary objective is to predict wine quality using the aforementioned input variables. Two approaches can be adopted Regression  v.s Classification.
In this project, we will be focusing on using regression to solve our problem:

-  **Regression**: Predict the exact quality score ranging from 0 to 10.

## 📊 Data Split:

- Training Data: 70%
- Testing Data: 30%

## ❓ Questions to Explore:

1. Which variables are most influential in predicting wine quality?
2. If opting for classification, how should the threshold for 'good' and 'bad' be determined?

## 📚 Citation:

P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.

## 👥 Contributors:

- Hao Lin
- Zewen Song
- Shahmir Shuja
