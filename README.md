# Retail Sales Performance Analysis 

## Table of Content

  - [Project Overview](#project-overview)
  - [Data Source](#data-source)
  - [Tools](#tools)
  - [Data Cleaning and Preparation](#data-cleaning-and-preparation)
  - [Exploratory Data Analysis](#exploratory-data-analysis)
  - [Data Analysis](#data-analysis)
  - [Results/Findings](#results-findings)
  - [Recommendations](#recommendations)
  - [References](#references)
  
### Project Overview
---
This Data analysis project aims to provide insight into the Sales Performance of a Superstore retail Outlet for the past 4years(2014-2017). By analyzing Various aspect of the Sales data, we seek to identify the products and regions that are driving growth and where they are losing money.

### Data Source
---
The primary source of the Data used was downloaded from Kaggle [Download here](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final) and it contains the detailed information about each sale made by the retail store. It is also attached to this project for your reference

### Tools
---
- Excel - Data Cleaning, Analysis and Visualization
    - [Download here](https://microsoft.com) 

### Data Cleaning and Preparation
---
In the data preparation phase, the following task was performed:
  1. Data loading and inspection : The dataset was verified that Sales and Profit were numerical types and that Order Dates were consistently formatted to allow for Time Series analysis
  2. Handling Missing Values : Power Query was used to handle null values in the "Postal Code" column
  3. Data Cleaning: Power Query (Data > Get Data) was used to remove duplicates and ensure dates are formatted correctly.

### Exploratory Data Analysis
---
EDA invloved reploring the sales data to answer key questions such as:
  - What country and region has the highest Sales and Profit?
  - What Product has the lowest Profit Margin?
  - What is the Year Over Year Sales growth?
  - What product has the highest discount applied?

### Data Analysis
---
This include the formulars used during Analysis

```Excel Formular
Cost = Net Sales- Profit

Profit Margin % = Profit/Net Sales

Profit Margin Category =IF(“Cell” > 0.2, "High Margin", "Low Margin")

YoY Sales Growth % = (Current Year sales - Previous Year Sales)/Previous Year Sales *100
```
![YoY% growth](https://github.com/user-attachments/assets/3ac26aea-fa0f-4333-87be-8eb01dcc90f7)


### Results /Findings
---
<img width="742" height="471" alt="dashboard new" src="https://github.com/user-attachments/assets/296dd246-869c-4db4-8200-350a2769d900" />


 The Analysis Results are summarized as follows:
   - California  had the highest sales and profit of $457,687.63 and $76,381.39 respectively for the duration.
![top 10 sales](https://github.com/user-attachments/assets/1bb702d5-cecf-4bbe-a751-e421da47ecd9)
   
   - The South region has the highest sales volume but the lowest profit due to a 20% average discount rate on furniture.
![South Dashboard](https://github.com/user-attachments/assets/6c7aff2e-cca3-400c-b3cf-d81f6a7b8e18)

   - Furniture category had the second highest Sales of $741,999.80 , Lowest Profit of  $18,451.27 and lowest Profit Margin of 82.26%.
![category amount](https://github.com/user-attachments/assets/1ab0fc77-1672-4842-9065-b7f33d179368)
   - The YoY Sales growth for the duration was 0%, 0.03%, 0.29% and 0.20% for the respective years of 2014-2017
   - In the Central Region, we noticed that as the Average Discount increased beyond 20%, the Profit Margin turned negative. This suggests that our current discount strategy in this region is destroying value rather than driving profitable growth.
<img width="746" height="478" alt="central dashboard" src="https://github.com/user-attachments/assets/9db35bbc-02d8-4223-ac83-be0d9da36947" />

### Recommendations
---
Based on the analysis, we recommend the following action
- Reduce discount caps on furniture in the South region to a maximum of 10%
- Pivot marketing efforts toward the Technology category, which has a 35% higher margin.

### References
---
1. Google
2. Gemini
3. Kaggle


