# Data Analysis Project

## Introduction
This project involves analyzing datasets related to user behavior, cooking preferences, and order trends. The analysis includes data cleaning, merging, exploratory data analysis, and generating business insights and recommendations. The project is organized using three datasets: UserDetails, CookingSessions, and OrderDetails.

## Datasets Overview
1. **UserDetails.csv**
   - Contains user information including User ID, User Name, Age, Location, Registration Date, Favorite Meal, and Total Orders.

2. **CookingSessions.csv**
   - Contains session details including Session ID, User ID, Dish Name, Meal Type, Session Start, Duration (mins), and Session Rating.

3. **OrderDetails.csv**
   - Contains order details including Order ID, User ID, Order Date, Dish Name, Order Status, Amount (USD), and Rating.

## Project Steps
1. **Data Cleaning and Preparation**
   - Removed duplicate entries.
   - Handled missing values by filling with mean values for numeric columns.
   - Ensured correct data types for date and numeric fields.

2. **Data Merging**
   - Merged `UserDetails.csv` with `CookingSessions.csv` on `User ID`.
   - Merged the resulting dataset with `OrderDetails.csv` on `User ID` and `Session ID`.

3. **Exploratory Data Analysis (EDA)**
   - Performed descriptive statistics.
   - Created visualizations to understand trends and patterns.
   - Conducted correlation analysis.

4. **Insights and Visualizations**
   - Analyzed the relationship between cooking sessions and user orders.
   - Identified popular dishes.
   - Explored demographic factors influencing user behavior.

5. **Business Recommendations**
   - Based on findings, provided actionable recommendations to improve user engagement and optimize business performance.

