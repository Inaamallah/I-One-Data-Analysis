# I-ONE Call Center Performance Dashboard

A comprehensive Excel-based data visualization project designed to track, analyze, and optimize call center operations. This dashboard provides actionable insights into representative performance, customer satisfaction, and call volume trends.

## 📊 Dashboard Preview

![Dashboard Overview](image_b230cf.png)

## 🎯 Project Overview
This project transforms raw call logs into a visual narrative. By leveraging **Pivot Tables** and **Excel Formulas**, the dashboard allows managers to monitor high-level KPIs and drill down into specific representative performance using interactive slicers.

### Key Objectives:
* Track call volume trends across months and days of the week.
* Monitor financial impact through total purchase amounts.
* Evaluate customer satisfaction via average ratings and "Happy Customer" counts.
* Analyze demographic distribution across three major cities: Cincinnati, Cleveland, and Columbus.


## 🚀 Key Features

### 1. KPI Scorecards
* **Total Calls:** 1,000 recorded interactions.
* **Total Revenue:** $96,623 in purchases generated.
* **Total Duration:** 89,850 minutes of talk time.
* **Avg Rating:** 3.89/5.0 aggregate satisfaction score.
* **Happy Customers:** Count of customers providing high-tier ratings.

### 2. Time-Series Analysis
* **Monthly Calls:** Line chart identifying peak seasons (notably March and October).
* **Weekly Calls:** Bar chart highlighting the busiest days, with Saturday and Wednesday showing the highest traffic.

### 3. Demographic & Regional Insights
* **Gender Distribution:** Stacked bar chart comparing Male vs. Female callers across different cities.
* **Rating Distribution:** Histogram showing the frequency of satisfaction scores from 1 to 5.

### 4. Interactive Filtering
* **Representative Slicer:** Allows the user to filter the entire dashboard by specific staff members (R01–R05) to evaluate individual performance.


## 🛠️ Tech Stack & Tools
* **Microsoft Excel:** Core platform for data storage and visualization.
* **Pivot Tables & Pivot Charts:** Used for dynamic data aggregation.
* **Power Query (Optional/Recommended):** For data cleaning and transformation.
* **Slicers:** For interactive user experience.


## 📂 Data Structure
The analysis is based on a primary dataset containing the following fields:
* **Call ID:** Unique identifier for each call.
* **Customer ID:** Linked to a demographic table (Gender, Age, City).
* **Duration:** Call length in minutes.
* **Representative:** The agent handling the call (R01-R05).
* **Purchase Amount:** Value of sales made during the call.
* **Satisfaction Rating:** Customer feedback score (1-5).
* **Temporal Data:** Date of call, Day of week, and Fiscal Year.


## 📖 How to Use
1.  **Download** the `.xlsx` file from this repository.
2.  **Open** the file in Microsoft Excel (2016 or later recommended).
3.  **Navigate** to the `Dashboard` tab to view the visualizations.
4.  **Interact** with the "Representative" slicer on the right to filter data.
5.  To update with your own data, paste new logs into the `Data` sheet and click **Data > Refresh All**.


## 💡 Insights Derived
* **Peak Volume:** Call volume spikes significantly in March and October, suggesting a need for increased staffing during these periods.
* **Regional Performance:** Cleveland shows the highest volume of callers compared to Cincinnati and Columbus.
* **Customer Sentiment:** Most ratings fall in the 4-star range, indicating generally high satisfaction but room for improvement to reach 5-star excellence.
