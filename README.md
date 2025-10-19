📊 Project: Panic Attack Data Analysis using Snowflake and Power BI
🧠 Project Overview

The Panic Attack Data Analysis project demonstrates how to extract, transform, and visualize healthcare data using Snowflake as the data source and Power BI for analysis. The dataset contains information about panic attack symptoms, triggers, patient demographics, and lifestyle factors.

This project focuses on analyzing how various symptoms and habits correlate with the frequency and severity of panic attacks. It provides interactive visuals and calculated insights for better understanding behavioral and medical trends.

🚀 Objectives

Extract data from Snowflake into Power BI using secure connections.

Perform data cleaning and structure adjustments in Power Query.

Create DAX-based analytical measures for panic severity and frequency.

Develop interactive Power BI dashboards for clinical and behavioral insight.

🧩 Data Pipeline & Tools
Stage	Tool	Description
Data Source	Snowflake	Patient and symptom data retrieved via SQL queries
Transformation	Power Query	Handled missing values and column adjustments
Modeling	Power BI	Defined relationships and DAX calculations
Visualization	Power BI Desktop	Created multi-page interactive dashboards
🧮 Key Analysis Components

Data Understanding using Snowflake SQL

Queried datasets to review data structure and column integrity.

Verified consistency between medical history, symptoms, and panic metrics.

Transformations in Power Query

Combined relevant tables and adjusted column data types.

Managed missing values and renamed columns for clarity.

Added derived columns for report use (e.g., Age Group segmentation).

DAX Calculations

Panic Score (HML): Assigned High, Medium, or Low values using IF and SWITCH logic.

COUNTROWS, FILTER, DIVIDE: Used to compute ratios and KPIs for dashboard visuals.

Age Group Column: Categorized patients into Adolescent, Adult, and Senior groups for analysis.

📈 Dashboard Insights

Symptom Analysis

![My Project Screenshot](https://i.postimg.cc/XN3NWMDL/Panic-Attack-Data-Analysis-page-0002.jpg).

Visual breakdown of patients experiencing Dizziness, Trembling, Sweating, Shortness of Breath, and Chest Pain.

Over half of patients reported multiple symptoms together, indicating cross-symptom patterns.


Lifestyle Analysis

![My Project Screenshot](https://i.postimg.cc/8P6Zm3TG/Panic-Attack-Data-Analysis-page-0003.jpg).

Visuals showing how Sleep Hours and Drinks per Week correlate with Panic Attack Frequency.

Lower sleep duration generally corresponded with higher panic scores.

Trigger and Medical History
![my Project Screenshot](https://i.postimg.cc/MK2FNxPj/Panic-Attack-Data-Analysis-page-0004.jpg)
Compared triggers such as Caffeine, Phobia, and PTSD across gender and age.

Displayed impact of prior Anxiety and Depression conditions on panic attack severity.

Age Group Analysis

Compared averages of Sleep Hours, Panic Score, and Panic Attack Frequency across age groups.

Clear distinctions appeared between adolescents and adults in frequency patterns.

🧰 Technical Components

Snowflake SQL for querying and data extraction.

Power Query for structural edits and loading data models.

Power BI DAX for calculated measures and analytical modeling.

Dashboards: Multi-page visuals with slicers and filters for gender, trigger, and medical history.
