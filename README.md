UPI Transactions Analysis – Power BI Project
**📌 Project Overview**
This project focuses on analyzing UPI (Unified Payments Interface) transactions to gain insights into user behavior, transaction patterns, and demographic trends. The analysis was conducted using Power BI, with a strong emphasis on data cleaning, transformation, modeling, and visualization.

The final dashboard provides an interactive view of:

Transaction volumes and trends

Customer segmentation by age groups

Payment mode preferences

Regional & demographic insights

Time-based filtering and drilldowns

**🔧 Tools & Technologies**
Power BI Desktop – Data visualization & dashboarding

Power Query – Data transformation and cleaning

DAX (Data Analysis Expressions) – Custom calculations and measures

Excel – Source data

**📂 Data Preparation**
Data Loading

Imported Excel dataset into Power BI.

Connected to Power Query for cleaning and transformation.

Data Cleaning & Transformation

Removed null/duplicate values.

Changed data types (e.g., Date, Currency, Category).

Standardized column formatting.

Data Modeling

Fact table: UPI Transactions

Dimensions: Customer demographics, Age groups, Payment modes

Created relationships between fact and dimension fields.

**📊 Key Features & Visuals**
Slicers & Filters

Customer Name, Gender, and Age Group slicers

Applied synced slicers across pages for consistency

DAX Calculated Columns

Created Age Groups segmentation using nested IF conditions

Age Groups = 
IF('UPI Transactions'[Customer Age] <= 25, "A1",
IF('UPI Transactions'[Customer Age] <= 35, "A2",
"A3"))
Visualizations

Line Chart – Transaction trend over time

Matrix Table – Customer details with transaction amounts (conditional formatting applied)

KPI Cards – Key metrics for quick insights

Bookmark Navigator – Toggle between multiple views

**🎯 Insights**
Younger customers (≤25 years) dominated transaction counts.

A clear upward trend in UPI adoption was observed across all age groups.

Payment mode distribution showed strong preference for UPI over other digital methods.

Regional and demographic analysis highlighted targeted opportunities for fintech adoption.

**🚀 Outcomes**

Built a fully interactive Power BI dashboard for UPI transactions.

Enhanced decision-making capability through visual segmentation and drilldown features.

Demonstrated ability to use Power Query, DAX, slicers, and bookmarks effectively in real-world scenarios
