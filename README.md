# Analysis of Global Inflation Rate

The project focuses on analyzing and projecting the Global inflation market from the years 1960 - 2016 and showing how it affected the industry from all the different Countries. The data is presented through the different types of graphs allowing to see the interpretation of the gathered datas.

## Dataset Description

The Datasets provides the respective normalized inflation rate,  average annual inflation rate of different countries and the Year (per decade) rate results.

## Summary of Findings

The result shows through the decade, that around mid 1990s the Global Inflation Rate spiked. The Regions affected the most are Africa (the region listed as "Others") and North America. The Global Average Inflation rate started to drop tremendously around the early 2000s and remained consistent through out mid 2010s. 

## Data Preprocessing

Data preprocessing involved checking for missing values and removing any incomplete records to ensure data integrity. The dataset was then examined for data types, and a statistical summary was provided to understand the distribution of values across different features.

## Exploratory Data Analysis

### Visualization

#### 1. Global Average Inflation Rate Over Time 

![alt text](https://imgur.com/a/ZdD7QTB)

The line graph shows the span of time when the Gloabl Inflation Rate increases in between 1960 to 1990 then decreases from the 2000s and becomes consistent onwards.

#### 2. Inflation Rate Distribution by Region

![alt text](https://imgur.com/a/03Nlz3k)

This graph shows the distribution of the Inflation Rate per Region.

#### 3. Top 10 Countries with Highest Inflation

![alt text](https://imgur.com/a/A9SDMYh)

This graph shows the Top 10 Countries with the Highest Average Inflation that mainly consists of North and South African Countries. 

## Model Development

The model development process involved selecting multiple regression algorithms, which are Linear Regression, , Random Forest Regression, and XGBoost. The dataset was split into training and testing sets to train the models and evaluate their performance effectively. 

## Model Evaluation

Both Mean Squared Error (MSE) and R-squared (R²) metrics were used to evaluate the performance of the models. 

### 1. Linear Regression

- **MSE**: 4174.46
- **R²**: -0.01


### 2. Decision Tree

- **MSE**: 1259.02
- **R²**: 0.70


### 3. Random Forest

- **MSE**: 550.52
- **R²**: 0.87



## Conclusion
The analysis reveals that global inflation reached its peak during the 1990s, followed by a significant decline in the early 2000s. This historical trend highlights crucial economic cycles, as the high inflation of the 1990s was often marked by economic instability, whereas the lowered inflation rates in the early 2000s reflect improved economic stability and more effective monetary policies. By understanding these fluctuations, we gain insights into the factors that contribute to economic resilience and stability, such as policy adjustments, technological advances, and shifts in the global economy. This historical perspective helps inform future economic planning and decision-making by demonstrating how inflation impacts growth, purchasing power, and economic health over time.


## Contributors

❗ NOTE: Your professor be the one to fill this section.