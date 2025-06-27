# Taxi-Trip-Analysis
Data cleaning, visualization, and analysis of taxi trip data to derive insights on fare, distance, and payment behavior.

## 🎯 Problem Statement

Analyze a real-world taxi trip dataset to:

- Clean and preprocess the data
- Understand fare distribution
- Investigate passenger count trends
- Compare payment types (Card vs Cash)
- Identify patterns in trip duration and distance

## 🎯 Objectives

- Perform data cleaning (missing values, outliers, data types)
- Visualize key features (fare, distance, duration, passenger count)
- Compare card vs cash usage
- Draw insights for business decisions (pricing, fleet management)

## ❓ Research Questions

- What is the distribution of fare amounts?
- How do fare and distance vary with payment type?
- Are there any anomalies in passenger count or trip duration?
- Do card users travel longer distances than cash users?
- Which passenger group size is most common?

## 🧼 Data Cleaning Steps

- Removed rows with missing, negative, or zero values
- Converted time deltas to numeric durations in minutes
- Removed outliers using IQR method for key columns
- Replaced payment type codes with readable labels

## 📊 Exploratory Data Analysis

Includes:

- Histograms of fare, distance, and duration
- Pie chart of payment preference
- Boxplots by passenger count
- Grouped bar charts comparing trends

## 🧠 Insights

- Most trips are solo or 2-passenger rides
- Cash payments slightly dominate card usage
- Fares and trip durations are strongly correlated
- Outliers removed improved visualization clarity

## 💻 Technologies Used

- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## ▶️ How to Run

1. Clone the repository  
