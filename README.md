# AtliQ Hotels Data Analysis Project

## Project Overview

This project focuses on analyzing hotel booking data for AtliQ Hotels to uncover key business insights related to occupancy, revenue, room performance, and booking trends.
The goal is to help stakeholders make data-driven decisions using structured analysis and clear metrics.

## Problem Statement

**AtliQ Hotels wants to understand:**

How bookings and revenue vary across cities and hotels
Room category performance
Occupancy trends over time
Factors affecting revenue and utilization
This analysis answers those questions using real-world hospitality datasets.

## Datasets Used

**The project uses 5 CSV files:**

dim_date.csv – Date-related attributes
dim_hotels.csv – Hotel details (city, property name, category)
dim_rooms.csv – Room category details
fact_aggregated_bookings.csv – Aggregated booking metrics
fact_bookings.csv – Transaction-level booking data

## Tools & Technologies

Python
Pandas – Data cleaning & transformation
NumPy – Numerical operations
Jupyter Notebook – Analysis & documentation

## Key Analysis Performed

Data cleaning and validation
Exploratory Data Analysis (EDA)
Occupancy percentage calculation
Revenue and booking trend analysis
Room category performance comparison
City-wise and hotel-wise insights

## Key Insights

Identified top-performing hotels and cities based on revenue
Compared room categories by occupancy and bookings
Analyzed booking trends across different time periods
Highlighted underperforming properties for improvement
Detailed insights are available inside the notebook.

## Project Structure
```bash
AtliQ-Hotels-Analysis/
│
├── hotels_analysis.ipynb
├── dim_date.csv
├── dim_hotels.csv
├── dim_rooms.csv
├── fact_aggregated_bookings.csv
├── fact_bookings.csv
└── README.md
```

## How to Run the Project
**Clone the repository**
```bash
git clone https://github.com/your-username/AtliQ-Hotels-Analysis.git
cd AtliQ-Hotels-Analysis
```

**Install required libraries**
```bash
pip install pandas numpy jupyter
```
Open the notebook
```bash
jupyter notebook hotels_analysis.ipynb
```

## Future Improvements

Add data visualization using Matplotlib / Seaborn / Power BI
Automate KPI dashboards
Perform forecasting on bookings and revenue

## Author

Ayaz Khan
Aspiring Data Analyst | Python | SQL | Power BI | Business Analytics