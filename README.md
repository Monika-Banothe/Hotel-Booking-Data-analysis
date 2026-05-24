Hotel Booking Data Analysis

Project Overview

This project focuses on analyzing hotel booking data using Python to identify booking trends, cancellation behavior, customer preferences, and revenue insights for City Hotels and Resort Hotels.

The project includes:

Data cleaning
Exploratory Data Analysis (EDA)
Data visualization
Business insights generation

The analysis was performed using Jupyter Notebook with libraries such as Pandas, Matplotlib, and Seaborn.

Dataset Information

The dataset contains hotel reservation details such as:

Hotel type
Booking cancellations
Customer stay information
Arrival dates
Customer demographics
Average Daily Rate (ADR)
Reservation status
Columns Used in the Analysis
Column Name	Description
hotel	Type of hotel (City Hotel or Resort Hotel)
is_canceled	Booking cancellation status
lead_time	Days between booking and arrival
arrival_date_year	Arrival year
arrival_date_month	Arrival month
stays_in_weekend_nights	Weekend stay duration
stays_in_week_nights	Weekday stay duration
adults	Number of adults
children	Number of children
babies	Number of babies
meal	Meal plan selected
country	Customer country
market_segment	Booking market segment
distribution_channel	Booking distribution channel
reserved_room_type	Reserved room type
assigned_room_type	Assigned room type
deposit_type	Deposit type
customer_type	Type of customer
adr	Average Daily Rate
reservation_status	Reservation status
reservation_status_date	Reservation status date
Objectives of the Project

The main objectives are:

Analyze hotel booking patterns
Understand cancellation trends
Compare City Hotels and Resort Hotels
Analyze monthly reservation behavior
Study ADR (Average Daily Rate) trends
Identify top countries with booking cancellations
Generate business recommendations
Technologies Used
Programming Language
Python
Libraries
Pandas
NumPy
Matplotlib
Seaborn
Environment
Jupyter Notebook
Project Workflow
1. Importing Libraries

Imported required Python libraries for data analysis and visualization.

2. Loading the Dataset

Loaded the hotel booking CSV dataset using Pandas.

3. Data Cleaning

Performed:

Missing value handling
Duplicate removal
Data type conversion
Null value treatment
4. Exploratory Data Analysis (EDA)

Analyzed:

Reservation cancellation rates
Hotel-wise booking comparison
Monthly reservation trends
ADR trends
Country-wise cancellations
5. Data Visualization

Created visualizations such as:

Bar charts
Count plots
Line graphs
Pie charts
Visualizations Included
Reservation Status Count

Shows total canceled and non-canceled bookings.

Reservation Status by Hotel Type

Compares cancellation trends between City Hotels and Resort Hotels.

Average Daily Rate Analysis

Shows ADR trends for both hotel types.

Monthly Reservation Analysis

Displays booking and cancellation trends by month.

Top Countries with Cancellations

Shows countries with the highest booking cancellation rates.

Key Insights
City Hotels have higher booking volume compared to Resort Hotels.
Longer lead times increase cancellation probability.
Certain months experience higher booking cancellations.
Resort Hotels generally show higher ADR values.
Some countries contribute significantly to cancellation rates.
Business Recommendations
Offer discounts for non-refundable bookings.
Improve cancellation policies.
Increase promotions during low booking months.
Focus customer retention strategies for repeated guests.
Optimize pricing based on seasonal demand.
Project Structure
Hotel-Booking-Analysis/
│
├── Data Analysis on Hotel Booking.ipynb
├── hotel_bookings.csv
├── README.md
└── images/
Installation

Install required libraries using:

pip install pandas numpy matplotlib seaborn
How to Run the Project
Download the dataset
Open Jupyter Notebook
Install required libraries
Run all notebook cells
Explore visualizations and insights
Future Improvements
Build machine learning models for cancellation prediction
Create Power BI dashboard
Perform customer segmentation
Deploy interactive analytics dashboard
Conclusion

This project provides valuable insights into hotel booking behavior, customer trends, and cancellation analysis. The findings can help hotel businesses improve operational efficiency, reduce cancellations, and optimize revenue strategies.

Author

Monika Banothe

Aspiring Data Analyst | Python | Power BI | SQL
