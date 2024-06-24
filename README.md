


# Religion and Crime Rates Analysis

## Table of Contents

- Introduction
- Setup
- Data
- Exploration and Analysis
- Conclusion


# Introduction

This project aims to explore the relationship between the religious composition of various countries and their crime rates. The analysis is performed using data on different religions and crime rates from various countries over a specified period.The primary objective of this project is to understand how different religious compositions of a population correlate with various crime rates. This includes examining data for different religions such as Islam, Christianity, Hinduism, Buddhism, Judaism, and non-religious groups. 


# Setup

To run the analysis, ensure you have the following libraries installed:

 pandas
 numpy 
 matplotlib.pyplot 
 seaborn
 plotly.express

# Data

The [dataset](<../../../Desktop/18-06-24 09_42_58_theglobaleconomy.csv>) provided by The Global Economy includes: Kidnappings per 100,000 people, Robberies per 100,000 people, Homicides per 100,000 people, Burglaries per 100,000 people, and Prisoners per 100,000 people. These data points are segmented by year and country, alongside the religious composition of the population. The raw dataset had a range from 1960 - present. 


# Exploration and Analysis

## Average Crimes Rates and Religious Composition
After importing and cleaning my data using 'pandas', I wanted to get a futher understanding of the data by getting the average crime rates and religous compositions for each country.  **insert interactive map here** this showed me the countries to be used in the analysis, make up based on the crime and religious indicators.

## Defining thresholds and Comparing 
The next goal was to define thresholds for categorizing countries based on the percentage of the population adhering to different religions. threshold were defined as: 0-20 as low, 20-60 as mediums, and 60-100 as high. Once the religious compositions were defined. I wanted to get the average crime rates by religious composition and compare. The following bar graphs provide some insight into how the religious composition of countries compare to each other based on the crime indicators.

![Online Image](https://github.com/bikerdouglas/religions_crimes/blob/main/images/graphs/islam.png?raw=true)
![Online Image](https://github.com/bikerdouglas/religions_crimes/blob/main/images/graphs/christians.png?raw=true)
![Online Image](https://github.com/bikerdouglas/religions_crimes/blob/main/images/graphs/non-religious.png?raw=true)
![Online Image](https://github.com/bikerdouglas/religions_crimes/blob/main/images/graphs/hinduism.png?raw=true)
![Online Image](https://github.com/bikerdouglas/religions_crimes/blob/main/images/graphs/buddhism.png?raw=true)
![Online Image](https://github.com/bikerdouglas/religions_crimes/blob/main/images/graphs/judaism.png?raw=true)

## Comparing Religious Compositions Against Each Other
Finally I wanted to compare the different religious compositions against each other. the following graph shows the relationship between the religious composition of a country's population and its crime rates. Each religious group is analyzed separately, and the crime rates are compared across different categories.
![Online Image](https://github.com/bikerdouglas/religions_crimes/blob/main/images/graphs/all%20religions.png?raw=true)

# Conclusion
Lastly, was to check for a correlation between the religious composition and crime rates. The result is a bar chart that visualizes the correlation between the religious composition of countries and their overall average crime rate. Each bar represents a different religion, and the height of the bar indicates the correlation value. This visualization helps to easily compare how the percentage of each religion in the population correlates with crime rates. A positive value indicates a positive correlation. As the percentage of the religion increases, the overall average crime rate tends to increase. A negative value indicates a negative correlation. As the percentage of the religion increases, the overall average crime rate tends to decrease. A value close to zero indicates little to no correlation.

