# Strava_Fitness
Data analysis project exploring user activity, sleep patterns, and health metrics from a fitness tracking app using Python, SQL, and Power BI to uncover behavioral insights.


# Smart Fitness Tracker Data Analysis

## Overview
This project analyzes user data from a smart fitness tracker application to understand patterns in physical activity, sleep, and health metrics. The analysis combines Python for data preparation and exploratory analysis, SQL for querying and validating data, and Power BI for building interactive dashboards. The goal is to generate meaningful insights that can support product decisions and marketing strategies for a fitness app.

---

## Problem Statement
Fitness applications collect large amounts of user activity data, but without proper analysis it is difficult to extract meaningful insights. Understanding how users interact with the app—such as how active they are, how much they sleep, and how these behaviors relate to health metrics—is important for improving engagement and business strategy.

---

## Business Objective
The business objective is to analyze smart fitness tracker data to understand user behavior patterns (activity, sleep, calories, BMI) and help improve the app’s marketing strategy.

---

## Dataset
The dataset contains activity and health metrics collected from smart fitness tracker users. It includes multiple tables such as:

- Daily activity data (steps, calories burned, activity intensity)
- Sleep tracking data
- Heart rate data
- Hourly and minute-level activity data
- BMI and health-related metrics

The datasets were combined and analyzed to identify patterns in user behavior and engagement.

---

## Tools & Technologies
- **Python** – Data loading, cleaning, and exploratory data analysis  
- **Pandas, NumPy, Matplotlib, Seaborn** – Data manipulation and visualization  
- **MySQL Workbench** – Querying and validating data using SQL  
- **Power BI** – Building interactive dashboards and visual insights  
- **Gamma** – Creating presentation slides  
- **Jupyter Notebook / Google Colab** – Running Python analysis  

---

## Project Workflow

### 1. Data Loading
The dataset was imported into Python using Pandas for further processing and analysis.

### 2. Data Cleaning
Data preprocessing steps included:
- Removing duplicates
- Handling missing values
- Formatting date and time columns
- Verifying unique user IDs

### 3. Exploratory Data Analysis (EDA)
EDA was performed to understand trends and distributions such as:
- Activity level distribution
- Sleep duration patterns
- Calorie expenditure
- BMI distribution
- Correlation between steps, activity, and calories burned

### 4. SQL Analysis
The cleaned data was analyzed using SQL queries in MySQL Workbench to:
- Identify distinct users
- Calculate average activity metrics
- Aggregate daily activity statistics
- Validate insights obtained from Python analysis

### 5. Dashboard Development
Interactive dashboards were built in Power BI to visualize key insights including:
- User activity distribution
- Sleep pattern analysis
- Calories burned trends
- BMI distribution
- Daily and hourly activity insights

### 6. Reporting
Insights from the analysis were summarized in:
- A **project report**
- A **presentation created using Gamma**

These documents highlight the major findings and their potential business impact.

---

## Dashboard Highlights
The Power BI dashboards focus on:

- **User Activity Distribution** – Comparison of lightly active, fairly active, and very active minutes  
- **Sleep Duration Analysis** – Distribution of sleep hours across users  
- **Calories Burned Trends** – Relationship between steps and calories burned  
- **BMI Distribution** – Identifying healthy vs. overweight user segments  

---

## Key Results & Insights
Some of the major insights derived from the analysis include:

- Most users maintain **moderate activity levels**, with fewer users engaging in high-intensity activity.
- The majority of users sleep **6–8 hours**, which aligns with recommended sleep durations.
- Higher step counts show a **strong relationship with increased calorie burn**.
- BMI distribution indicates that most users fall within the **normal range**, with some users in the overweight category.

These insights can help fitness companies design **targeted marketing campaigns and personalized fitness recommendations**.

---

## How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/Strava_Fitness.git
cd fitness-tracker-data-analysis


2. Run Python Analysis

Open the Jupyter Notebook or Python scripts to perform data cleaning and EDA.

3. Run SQL Queries

Import the dataset into MySQL Workbench and execute the SQL scripts provided in the repository.

4. View the Dashboard

Open the Power BI (.pbix) file to explore the interactive dashboards.

5. View the Presentation

The project presentation created using Gamma summarizes the findings and insights.

Project Structure

Strava_Fitness
│
├── data/                # Raw datasets
├── notebooks/           # Python notebooks for data analysis
├── sql/                 # SQL queries used in MySQL Workbench
├── powerbi/             # Power BI dashboard (.pbix)
├── report/              # Project report
├── presentation/        # Gamma presentation
└── README.md

Conclusion

This project demonstrates an end-to-end data analysis workflow—from data cleaning and exploration to visualization and business insight generation. The analysis highlights how user activity data can be leveraged to better understand user behavior and support strategic decisions for fitness applications.
