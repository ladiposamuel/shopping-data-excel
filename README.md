# shopping-data-excel
![Shopping](shopping.jpg)
Analysis of a shopping dataset using excel

## Introduction
The goal of this project is to apply the Excel skills I have been learning over the past month, by documenting my analysis of a shopping dataset that the organization I am learning from has provided. :smile:

## Problem Statement
The marketing department aims to launch a campaign in the second quarter of 2024. However, they require a dashboard to monitor business activity during the waiting period. This will provide insights into where to channel the campaign efforts. The Marketing lead would like to track various metrics over time, including product performance, changes in customers' choice of color, location, and seasonality patterns in relation to orders. Additionally, any other metric(s) deemed necessary should be incorporated into the dashboard.

## Tools, skills and concepts used
- Excel
- Formulas and Functions
- Pivot Tables
- Dashboard Building

## Data Cleaning
The first step I took was is to ensure that my data is clean enough for use, this is to ensure that my analysis is void of error and the results are more reliable. The steps I took to clean the data are stated below:

### Step 1
Remove duplicates: I used the excel remove duplicates tool in the data tab to do this. It was realized that there 9 duplicates in the dataset, which could have resulted from error when inputting the values. 
![Duplicates Removed](removeduplicates.png)

### Step 2
Missing Values: I noticed that there were about 10 missing values in the customer ID column, also they all followed each other which brought me to the conclusion that it was probably manually altered. So it was very easy to rectify. I used Flash fill to fill the empty columns because the follow an order.
![Missing Customer ID](missingcustomerid.png)

There were also some missing values in the colour column of the dataset. Since this is a categorical data, I filled the blank cells with “UNKNOWN”, using the find and replace feature in excel. This was done to minimise errors in the analysis
![Colour Category](colourcategoryblank.png)

### Step 3
Input Errors: There were some worngly inputed values, I came to this conclusion because of some unrealistic ages in the age column, '280' and '3100' to be specific. I corrected this by adjusting the numbers manually to be 28 and 31. 
![Age error](agenumericalerror.png)

### Step 4
Incorrect categorical data: There were some incorrect values in the colour column of the dataset. The incorrect values were different variations of what is meant to spell “BLACK” but the error could have risen from human input error. So I just corrected them manually as they were not much
![Colour](colourcategory.png)


