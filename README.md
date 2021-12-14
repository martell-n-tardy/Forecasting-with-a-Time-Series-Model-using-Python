![](https://github.com/martell-n-tardy/Forecasting-with-a-Time-Series-Model-using-Python/blob/main/LexusLogo.jpeg)
# Demand Forecasting Using Time Series Analysis #
An end-to-end capstone project completed for a prior employer, Lexus of Mishawaka, displaying a deep understanding of time series analysis and forecast modeling. The goal of this forecast model is to predict vehicle demand 24 months into the future using 12+ years of provided historical sales data. 

## Contents ##
* **data:** Contains three folders - raw, interterim, and processed - each pertaining to specific versions of the data used in this project.
* **notebooks:** Contains four Python formatted code files - data wrangling, EDA, preprocessing & training, and models - for this project.
* **reports:** Contains four PDF documents pertaining to problem identification, detailed project report, project slide deck presentation, and an additional 5 year analysis report requested by the dealership's Dealer Principal. This last document was the motivation behind exploring the original questions more deeply.

# Project Overview #
## Background ##
Lexus of Mishawaka is an authorized Lexus dealership conveniently located on Grape Road in Mishawaka, Indiana. Lexus of Mishawaka is a full-service dealership offering their guests not only a full line-up of all new and L/Certified Lexus vehicles, numerous luxury and mid-range vehicles from similar brands, but also a friendly and reliable service and parts department. In order to ensure Lexus of Mishawaka is accurately serving their market and the needs of their guests’, the dealership has tasked their in-house Marketing and Information Specialist, Martell Tardy, with analyzing their 2004 -2017 historical data for insight.

## Problem Statement ##
* **(Business)** Can examining historical sales data provide insight on future vehicle demand and help make data-drive decisions on corporate inventory requests?
* **(Analytical)** How can the historical sales data from 2004 - 2017 be analyzed and used to deploy a machine learning model forecasting the next 24 months of consumer vehicle demand in the Lexus of Mishawaka market?

## Methodology ##
To solve this business problem Lexus of Mishawaka will be training and deploying a machine learning model that will be able to forecast which Lexus, Toyota, and non-Toyota models are necessary to have in the dealership inventory 12 to 24 months starting April 2017. This forecast will improve dealer order and inventory management, optimize plant production scheduling, and increase understanding of consumer demand in the market. 

**To address this task five high level research questions were developed and explored:**
* Q1: What are my target variables and what can be gathered about their distribution?
* Q2: Does the time series show any consistent pattern? 
* Q3: Is there seasonality or a significant trend?
* Q4: Based on what is observed in response to Q4, what kind of model is appropriate for this time series?
* Is there any association between the years available and the number of units sold yearly?
