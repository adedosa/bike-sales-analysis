# Bike Sales Analysis - May 8 2025

## Overview

This project involved analyzing a small dataset of bike sales for an online store in different regions. The goal was to understand bike usage trends by analyzing the average income, age bracket and commute distance of the customers.  The analysis was performed using Microsoft Excel.
## Dataset

The dataset used in this project is named `Excel Project Dataset.xlsx` and contains the following columns:

* **ID:** ID number of each customer (Integer)
* **Marital Status:** Marital status of each customer (Text)
* **Gender:** The gender of the customer(Text)
* **Income:** How much the customer makes monthly (Currency)
* **Children:** Number of children the customer has(Integer)
* **Education:** The highest level of education completed(Text)
* **Occupation:** The occupation of the cutomer(Text)
* **Home Owner:** Whether or not the cusotmer has a home(Text)
* **Cars:** Number of cars the customer has (Integer)
* **Commute distance:** The distance travelled by the customer(Integer)
* **Region:** The region in which the customer resides(Text)
* **Age:** The age of the customer (Integer)
* **Purchased bike:** Whether or not the customer purchased a bike (Text)


The dataset was created for this exercise.

## Analysis Steps

The following steps were taken to analyze the data:

1.  **Data Cleaning:**
    * Checked for and removed any duplicate rows. 
	* Used the find and replace function to edit the marital status to show the full word instead of M/S
2.  **Descriptive Statistics:**
    * Used a nested if statement to ceate age brackets to make analysis easier . 
3.  **Basic Visualization:**
    * Created a bar chart to visualize the average income per purchase of a bike. 
    * Created a line chart to visulaize the customer age bracket.
    * Created a line chart to visualize the customer commute distance.
	* Inserted 3 slicers for the marital status, education and region to filter the dashboard and show specific info. 

## Key Findings

Based on the analysis, some key findings include:

* The average income per purchase is $53,440 and $56,208 for female and male customers that havent purchased a bike.
* The average income per purchase is $55,774 and $60,124 for male and male customers that have purchased a bike.
* The middle age bracket is the group with the highest number of purchased bikes

## Files Included

* `Excel Project Dataset.xlsx`: The raw dataset used for the analysis.
* `DayoBikeSalesDashboard.xlsx` : The Excel file containing the formulas, calculations, and charts.
* `README.md`: This file, providing an overview of the project.

## Tools Used

* Microsoft Excel


## Author

* Dayo Akerele
* https://www.linkedin.com/in/dayo-akerele/
* https://github.com/adedosa

---