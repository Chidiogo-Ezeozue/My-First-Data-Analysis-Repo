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

![2 Columns for UK cars](https://github.com/Chidiogo-Ezeozue/My-First-Data-Analysis-Repo/assets/161604924/135824a3-9a66-46d1-bc07-eb50305a2249)

------
# Findings

* There are 11 brands and 195 models in the dataset

* The average price of cars is  £16,863k

* The average mileage is 23,220 miles

* The average age of cars is 7 years

* Mercedes has the highest average price of £25k followed by C Class, Audi, BMW, BW, Skoda, Focus, Hyundi, Toyota, Ford, and Vauxhall with lowest average of  £10k

![Uk Brands Chart](https://github.com/Chidiogo-Ezeozue/My-First-Data-Analysis-Repo/assets/161604924/581846ba-b4ba-40ea-b4d4-3362244aa8f7)

* Petrol is the most used fuel type by 48.85% followed by diesel, hybrid, and others while electronic is the least used fuel type showing extremely low significance in the distribution

![Fuel Distribution chart](https://github.com/Chidiogo-Ezeozue/My-First-Data-Analysis-Repo/assets/161604924/c117fe4e-f60b-432a-b499-471b46c39bb8)

* The scatter plot indicates a positive correlation between price and mileage, that is, as mileage increases, prices decreases

* The relationship between price and road tax is inconsistent as depicted in the line chart and this confirms that road tax does not have any significant impact on the price of cars


-------
# Recommendation
