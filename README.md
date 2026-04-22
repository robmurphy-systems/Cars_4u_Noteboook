**Overview**

The used car market has rapidly outpaced new car sales, creating a complex pricing environment driven by variability in condition, usage, and location.

This project builds a data-driven pricing model to help Cars4U accurately estimate the value of pre-owned vehicles and support profitable, competitive pricing strategies.

**Business Context**

The Indian pre-owned car market has grown significantly:

📊 ~4 million used cars sold vs ~3.6 million new cars
📉 Slowdown in new car sales
🔄 Shift toward pre-owned vehicle purchases

**Unlike new cars—where pricing is controlled by OEMs—used cars face:**
High price variability
Uncertain supply-demand dynamics
Inconsistent valuation across locations

**For Cars4U, pricing is not just a number—it is a strategic control point.**


**Objective**
Perform Exploratory Data Analysis (EDA) to understand key drivers
Build a Linear Regression model to predict used car prices
Generate insights and recommendations to guide pricing strategy

**Problem Statement**

Develop a model that can:

Predict the market price of used cars
Reduce pricing uncertainty
Enable the business to:
Avoid underpricing
Stay competitive in the market
Optimize margins through data-driven decisions

**Dataset Overview**

The dataset includes key attributes influencing car pricing:

Vehicle Details
Brand, Model Name, Year
Usage
Kilometers Driven, Owner Type
Specifications
Fuel Type, Transmission, Mileage
Engine (CC), Power (bhp), Seats
Market Factors
Location
New Price
Target Variable
Price (used car price in INR Lakhs)
🛠️ Solution Approach
1. Data Exploration (EDA)
Distribution analysis of features
Outlier detection
Missing value handling
Feature relationships and correlations
2. Data Preprocessing
Handling null/missing values
Encoding categorical variables
Feature scaling (if applicable)
3. Model Development
Linear Regression model
Feature selection and refinement
Model evaluation using performance metrics
📈 Key Insights
Car age and kilometers driven strongly impact price
Brand and model influence baseline valuation
Location-based variation reflects regional demand
New price acts as a strong anchor for resale value
