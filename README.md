### <span style="color:blue">Exercises for Evaluation in Module 3. Data Transformation and Analyses 

This repository contains the exercises of the Evaluation of ADALAB's Module-3-Promo-B-da-pt.


Files included are a Jupyter notebook with my proposed solutions for the ejercises and 3 cvs files. The first 2, described below, are the original files provided with the exercise, they together describe customer behavior within an airline loyalty program. 
<span style="color:green">
    ```- Customer Flight Analysis.csv```
    ```- Customer Loyalty History.csv```

The third file, ```customer_flight_loyalty_clean.csv```, is the result of merging, cleaning and organizing the data.

What follows is a description of the content of the original files.

**<span style="color:green">1. Customer Flight Analysis.csv**
This file contains information about customers' flight activity, including the number of flights booked, distance flown, points accumulated and redeemed, and costs associated with redeemed points.

The different columns are:
- **Loyalty Number**: This attribute represents a unique identifier for each customer within the airline's loyalty program. Each loyalty number corresponds to a specific customer. 
- **Year**: Indicates the year in which flight activities were recorded for the customer.
- **Month**: Represents the month of the year (from 1 to 12) in which the flight activities occurred. 
- **Flights Booked**: Total number of flights booked by the customer in that specific month.
- **Flights with Companions**: Number of flights booked on which the customer traveled with companions.
- **Total Flights**: The total number of flights the customer has flown, which may include flights booked in previous months.
- **Distance**: The total distance (presumably in miles or kilometers) the customer has flown during the month.
- **Points Accumulated**: Points accumulated by the customer in the loyalty program during the month, based on distance flown or other factors.
- **Points Redeemed**: Points the customer has redeemed in the month, possibly for benefits such as free flights, upgrades, etc.
- **Dollar Cost Points Redeemed**: The dollar value of the points the customer has redeemed during the month.

**<span style="color:green">2. Customer Loyalty History.csv**
This file provides a detailed profile of customers, including their location, education level, income, marital status, and details about their loyalty program membership (such as card type, customer lifetime value, and enrollment and cancellation dates).

- **Loyalty Number**: The customer's unique identifier within the loyalty program. This number allows the information in this file to be correlated with the flight activity file.
- **Country**: The customer's country of residence.
- **Province**: The customer's province or state of residence (applicable to countries with provincial or state divisions, such as Canada).
- **City**: The customer's city of residence.
- **Postal Code**: The customer's postal code.
- **Gender**: The customer's gender (e.g. Male and Female).
- **Education**: The customer's educational level (e.g. Bachelor, College, etc.).
- **Salary**: The customer's estimated annual income.
- **Marital Status**: The customer's marital status (e.g. Single, Married, Divorced, etc.).
- **Loyalty Card**: Type of loyalty card the customer has. This could indicate different levels or categories within the loyalty program.
- **CLV (Customer Lifetime Value)**: Total estimated value that the customer contributes to the company throughout the relationship they maintain with it.
- **Enrollment Type**: Type of customer enrollment in the loyalty program (e.g. Standard). 
- **Enrollment Year**: Year in which the customer enrolled in the loyalty program.
- **Enrollment Month**: Month in which the customer enrolled in the loyalty program.
- **Cancellation Year**: Year in which the customer cancelled their membership in the loyalty program, if applicable. 
- **Cancellation Month**: Month in which the customer cancelled their membership in the loyalty program, if applicable.


The exercises consist of three phases:

**<span style="color:red">Phase 1: EDA**
- Data exploration
- Management of null and/or missing values
- Descriptive statistics of main data

**<span style="color:red">Phase 2: Visualization**

Use different visualization tools to answer these questions:

**1.** How are "flights booked" per month distributed over the year?

**2.** Is there any relation between "distance" and "points_accumulated"?

**3.** How are customers distributed by State or province?

**4.** How does the mean salary compare amongst the different education levels? 

**5.** What is the proportion of customers with each of the different loyalty cards?

**6.** How are customers distributed according to their marital status and their gender?

**<span style="color:red">Phase 3: Bonus:**

Evaluating Differences in Flight Booked by Educational Level
- Data preparation
- Descriptive analyses
- Statistic analysis




Exercises by:
- Elena Fernández Burguera
[@EFBurguera] (https://github.com/EFBurguera)

![logo adalab](adalab-logo.png)