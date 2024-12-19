# Power BI Dashboard: Customer Data Analysis

This project involves the creation of a Power BI dashboard that analyzes customer churn using the provided clean CSV dataset. The dashboard presents various insights into customer behavior, including churn distribution, customer engagement, and subscription patterns.

## Dataset Overview

The dataset `clean_data.csv` contains the following columns:

- **Churn**: Whether the customer has churned (1 = Yes, 0 = No).
- **Age**: Age of the customer.
- **Gender**: Gender of the customer.
- **Customer ID**: Unique identifier for each customer.
- **Mails Subscribed**: Number of mail subscriptions the customer is subscribed to.
- **Maximum Daily Minutes**: Maximum number of minutes the customer spent on a given day.
- **Maximum Days Inactive**: Maximum number of days the customer has been inactive.
- **No of Days Subscribed**: Total number of days the customer has been subscribed.
- **Phone No**: Phone number of the customer.
- **Year**: Year the data was recorded.
- **Videos Watched**: Number of videos watched by the customer.
- **Weekly Mins Watched**: Total weekly minutes watched by the customer.
- **Weekly Max Nights Mins**: Maximum minutes watched during a night in a given week.

## Dashboard Visualizations
Dashboard screenshot

![Screenshot 2024-12-19 155854](https://github.com/user-attachments/assets/50996dfb-457c-43b3-b94e-9334059fce69)

The Power BI dashboard includes the following visualizations:

1. **Sum of Churn by Gender (Pie Chart)**: 
   - This pie chart visualizes the sum of churned customers categorized by gender.

2. **KPI Cards**:
   - **Customer Count**: Total count of unique customers (`Customer ID`).
   - **Average Maximum Daily Minutes**: The average value of `Maximum Daily Minutes` across all customers.

3. **Churn Analysis by Gender**:
   - A visual that displays churned customers grouped by gender.

4. **Churn Analysis by Age**:
   - A chart showing the distribution of churn based on customer age.

5. **Average Age by Videos Watched**:
   - A visual to show the average age of customers based on the number of videos they have watched.

6. **Customer Engagement and Subscription Behavior by Gender**:
   - Insights into customer behavior with respect to engagement metrics like `Weekly Mins Watched`, `Videos Watched`, and `No of Days Subscribed`, segmented by gender.

## Project Files

- `clean_data.csv`: The cleaned dataset used for the analysis.
- `Customer data Dashboard (1).pbix`: The Power BI project file containing all visualizations and analyses.

## Installation and Usage

To use this project:

1. **Power BI Desktop**: Download and install Power BI Desktop from [here](https://powerbi.microsoft.com/desktop/).
2. **Load the Dataset**: Open the `Customer data Dashboard (1).pbix` in Power BI Desktop and connect it to the `clean_data.csv` dataset.
3. **Explore the Dashboard**: Use the various visualizations to explore insights regarding churn, customer engagement, and subscription behaviors.



 
