# 100k UK Used Cars Analysis
# ![100k UK Used Cars 1](https://github.com/Chidiogo-Ezeozue/My-First-Data-Analysis-Repo/assets/161604924/96200de3-8e13-4ad7-80d1-4a7a8ad7e028)

-------
# Introduction
This is a Power BI project that conveys analysis of 100k UK Used Cars and the dataset contains information of brand, model, year, price, transmission, mileage, fuel type, tax, miles per gallon (mpg),  and engine size. The dataset housed 13 csv files corresponding to each car manufacturer. 

The purpose of this project is to study the correlation between the features and the target variable, and their significant impact in the selling price of cars

-------
# Skills demonstrated
* Data Cleaning & Transformation

* Data Visualization

* DAX and Calculated Measures

* Filters and Tooltips

* Attention to Details

* Problem Solving

-------
# Problem Statement

The objective of this project is to use power BI to visualize the data and answer the following questions and more:

1. What is the average price of each car manufacturer?

2. What is the correlation between the price and mileage of the cars?

3. What is the distribution of fuel types across the dataset?

4. What is the impact of road tax on the price of cars?

5. What is the trend of mileage and price of cars over the years?

6. What is the most commonly used fuel type?

7. What is the average price by transmission?

-------
# Data Sourcing

 The dataset was downloaded from kaggle using the link below

https://www.kaggle.com/datasets/adityadesai13/used-car-dataset-ford-and-mercedes

------
# Data Cleaning/Transformation
The Power BI  folder connector was used to import all the files in a folder at once into the power query editor. I embarked on cleaning the data thoroughly by removing duplicates, nulls, and blanks. I also removed 2 extremely dirty files from the folder since there is a clean version of the 2 brands in the folder. 

I changed the data types, renamed headers and added “ageofcar” Column from “year”. After that, I loaded my data into Power BI. 

![100k Uk Used Cars Data Image](https://github.com/Chidiogo-Ezeozue/My-First-Data-Analysis-Repo/assets/161604924/9988cd22-9182-41d1-8c79-ce4e5a9c3fd9)

I added 2 extra calculated columns to show the “AvgPricePerModel” & “PricePerMileage”.

------
# Findings and Recommendation
