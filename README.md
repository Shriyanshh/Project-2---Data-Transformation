# Project-2---Data-Transformation 

## Rpubs Link to 3 Datasets:
### https://rpubs.com/shriii/1231431 
### https://rpubs.com/shriii/1231433
### https://rpubs.com/shriii/1231436

# 1. Diabetes Dataset Analysis

## Overview
This repository contains a comprehensive analysis of a Diabetes dataset. The dataset includes records of individuals with and without diabetes, along with several factors associated with the risk of developing diabetes. Key variables include age, BMI, glucose levels, insulin levels, blood pressure, and the diabetes pedigree function. 

## Dataset Details
The dataset includes multiple predictors related to diabetes risk, such as:

- **Age**
- **BMI (Body Mass Index)**
- **Glucose Levels**
- **Insulin Levels**
- **Blood Pressure**
- **Diabetes Pedigree Function**

These predictors have been used to analyze the correlation between various risk factors and the likelihood of having diabetes.

## Analysis Breakdown

### 1. Data Cleaning
Initial data cleaning was performed to streamline the analysis. All key predictors were organized into a single, cohesive column for easier processing and analysis.

### 2. Descriptive Analysis
Basic statistical measures such as mean, median, and standard deviation were calculated to assess the distribution of each predictor across the dataset. This helped to identify key risk factors related to diabetes.

### 3. Diabetes Pedigree Function Analysis
The effectiveness of the **Diabetes Pedigree Function** as a predictive marker for diabetes was evaluated. While it proved useful, the analysis indicates it may not be a fully reliable indicator on its own.

### 4. Predictor Averages
The average values for each predictor were compared between individuals with diabetes and those without. It was found that elevated **insulin** and **glucose levels** were strong indicators of diabetes risk.

### 5. Blood Pressure Distribution
An analysis of blood pressure distributions between diabetes-positive and diabetes-negative groups was conducted. Although the mean blood pressure was slightly higher in the diabetes-positive group, the overall distribution was similar across both groups, suggesting that blood pressure alone is not a strong predictor of diabetes.

## Conclusion
- **Insulin** and **glucose levels** are the most significant predictors for the presence of diabetes.
- The **diabetes pedigree function** can be a helpful risk marker but should not be relied upon as a standalone predictor.
- **Blood pressure**, while slightly elevated in diabetes-positive individuals, does not show significant differences between groups and is unlikely to serve as a reliable standalone predictor.

## Future Work
Further analysis could be conducted by exploring advanced predictive models like logistic regression or machine learning algorithms to improve diabetes prediction accuracy.

# 2. NYS Prison Employee Misconduct Analysis

## Overview

This repository contains an analysis of **Prison Employee Misconduct** in the State of New York, covering the period from **July 2020 to April 2022**. The goal of this project is to identify the most common types of misconduct, the penalties typically administered, and how misconduct varies by job title and facility.

## Data Source

The dataset used in this analysis was obtained from the Marshall Project's repository on **ObservableHQ**. The data was acquired through a **Freedom of Information Act (FOIA)** request to the **NYS Department of Correction**.

You can explore the original dataset by visiting the following link: [New York Prison Employee Discipline Data](https://observablehq.com/@themarshallproject/new-york-prison-employee-discipline-data).

This project provides insights into prison employee discipline and aims to enhance understanding of employee behavior and administrative actions within the correctional system.

# 3. World Population Dataset Analysis

## Overview

This repository contains an R script designed to analyze the **World Population Dataset**, focusing on key population metrics such as population size, area, population density, and growth rates for various countries and territories from 1970 to 2022.

## Dataset Details

The **World Population Dataset** provides a comprehensive overview of global population trends. The dataset includes the following variables:

- **Population Size**
- **Area (in square kilometers)**
- **Population Density**
- **Growth Rate**
- **Percentage of World Population**

The dataset is transformed into a long format to facilitate easy manipulation and visualization. This structure enables effective analysis of trends and comparisons across different countries and time periods.

## Analysis Summary

### Population Growth Rate Analysis

The analysis highlights the **top 10 countries** with the **highest population growth rates** and the **bottom 10 countries** with the **lowest growth rates**. These findings are visualized on a **world map**, with countries color-coded based on their respective growth rates. 

Additionally, **bar plots** are generated to display the population sizes of these countries in 2022, and **line graphs** depict population growth trends over the years, segmented by continent. This provides a comprehensive view of population dynamics across different regions.

### Geographical Data Integration

To enhance the visual representation of population trends, the analysis incorporates geographical data using **map files**. These map files are read into the R script using the `st_read()` function from the **sf** package. They serve as the base layer for visualizations, enabling the creation of spatial maps that highlight countries with the highest and lowest population growth rates.

The shaded maps offer a **spatial dimension** to the analysis, making it easier to identify geographical patterns or anomalies in population growth. This adds clarity and context to the numerical data, enhancing the interpretability of the study's findings.

### Visualization Output

A **shaded map** highlighting the top 10 and bottom 10 countries based on population growth rates is generated as part of the analysis. The map uses distinct colors to represent countries with the highest and lowest growth rates, providing a quick, visual summary of global population trends. This map is saved as a **PNG file** in the working directory, offering a visually impactful conclusion to the analysis.

## Conclusion

This analysis provides crucial insights into global population dynamics, identifying countries with notably high and low population growth rates. Key takeaways include:

- **Asia** has experienced the most significant population increase over the past decades.
- Countries with extreme population growth rates are visualized, offering important context for potential **policy decisions**.
- The findings can serve as a foundation for further **socio-economic studies** and global planning efforts.








