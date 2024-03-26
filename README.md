"# Covid_R" 
# COVID-19 Line List Data Analysis

This repository contains an analysis of the COVID-19 line list data. The dataset used is from the "COVID19_line_list_data.csv" file.

## Purpose
The purpose of this analysis is to investigate various factors related to COVID-19 cases, including age, gender, and mortality rate.

## Prerequisites
To run the analysis, you need to have R installed on your machine. Additionally, you need to install the `Hmisc` package, which is used for descriptive statistics.

To install the `Hmisc` package, run the following command in your R console:
```R
install.packages("Hmisc")

Analysis

The analysis is performed in R programming language. Here's an overview of what's included:

Data Import: The dataset is read from the "COVID19_line_list_data.csv" file.

Descriptive Statistics: The describe function from the Hmisc package is used to obtain descriptive statistics of the dataset.

Data Cleaning: A new variable death_dummy is created to indicate whether a case resulted in death or not.

Death Rate Calculation: The death rate is calculated as the proportion of cases resulting in death.

Age Analysis: A t-test is performed to compare the mean age of deceased and surviving cases.

Gender Analysis: A t-test is performed to compare the mortality rates between genders.

Results

1.There is a statistically significant difference in age between deceased and surviving cases (p-value < 0.05).

2.Gender has a statistically significant effect on mortality rate (p-value < 0.05).

Conclusion

Based on the analysis, it can be concluded that age and gender are significant factors influencing COVID-19 mortality rates.

Usage

To run the analysis, simply execute the R script provided (analysis_script.R) in your R environment.

