Road Accident Analysis Dashboard (2021–2022)
🧩 Project Overview

This project focuses on analyzing and visualizing road accident data for the years 2021 and 2022 to uncover key insights that can help improve road safety and understand accident trends. The analysis culminates in an interactive Power BI dashboard that highlights major KPIs, identifies patterns, and reveals correlations between accident factors such as severity, location, time, and vehicle type.

🎯 Objectives

The client aims to build a Road Accident Dashboard that provides actionable insights based on the following requirements:

Primary KPIs

Total Casualties resulting from all recorded accidents.

Casualty Percentage by Accident Severity (Fatal, Serious, Slight).

Maximum Casualties by Vehicle Type.

Secondary KPIs

Casualty Count by Vehicle Type.

Monthly Trend Analysis comparing casualties for the current year (2022) vs. previous year (2021).

Casualty Distribution by Road Type.

Casualty Distribution by Road Surface.

Relationship between Casualties by Area (Urban/Rural) and Day/Night conditions.

🧹 Data Cleaning

Converted column headers to filters for easy validation and error spotting.

Corrected inconsistent data entries, such as renaming “Fetal” to “Fatal” in the Accident Severity column.

Verified data integrity across all columns to ensure accurate aggregation and reporting.

⚙️ Data Processing

To prepare the dataset for analysis:

Extracted Month from Accident Date using:

=TEXT(B2,"MMM")


Extracted Year from Accident Date using:

=TEXT(B2,"YYYY")


Added computed columns to enable time-series comparison and yearly filtering in Power BI.

📊 Outcome

