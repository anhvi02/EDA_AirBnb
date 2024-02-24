# **Airbnb Project: Exploratory Data Analysis of Properties in Denmark**
**Author: Anh Vi Pham - Henry Pham**  

**Scope:** The project's objective is to explore and analyze Airbnb data related to properties in Denmark. Furthermore, it aims to investigate the various aspects that differentiate properties in Sealand from the rest of Denmark. Finally, the project involves building a machine learning model to predict house prices.

**Data Source:** The data pertains to properties listed on Airbnb in Denmark during the period 2016-2019, provided by Deakin University for educational purposes.  

**General Process:** 
- Phase 1. Data Cleaning and Exploring
    + Handling missing values, duplicated values
    + Specify properties in Sealand
    + Data distribution
    + Data correlation   
- Phase 2. Data Analysis: Properties in Sealand compared to the rest of Denmark  
    + Price comparision: overall price, average price over time, price estimation with Linear Regression Analysis
    + Customer Satisfaction comparison with Hypothesis Testing
    + Property Count and Average Satisfaction Score for Landlords in Sealand
- Phase 3. Prediction Model: Properties price classification
    + Labeling
    + Handling outliers with IQR
    + Examining Data Balance and Multicollinearity with VIF 
    + Normalization
    + Modelling: Logistic Regresison, KNN, Decision Tree
    + Model Optimization with GridSearch
    + Model evaluation    

**Executive Summary:**  

Based on the analysis, several observations have been made: 
-	The nightly Airbnb rates in Sealand are slightly higher than the rest of Denmark, but the prices vary significantly. On the other hand, there are many outliers in the prices of Airbnb properties outside Sealand.
-	Over the three-year period from November 2016, the average prices in both areas show an increasing trend. Particularly in Sealand, there is a recurring price cycle, with a price dip usually occurring in January each year before gradually rising again.
-	The location of the property is the most influential factor in price fluctuations, alongside other factors such as room type and the number of occupants allowed in a rental.
-	There is sufficient evidence, at a 95% confidence level, to conclude that the average satisfaction of properties in Sealand is higher than the rest of Denmark.
-	5 is the recommended number of properties that a landlord should own to ensure the quality of their Airbnb services.
