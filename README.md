📄 Agriculture Dataset – README 📌 Project Description

This repository contains the ICRISAT District-Level Agriculture Dataset along with the work done for data cleaning, SQL analysis, and Power BI visualizations. The dataset includes information about crop area, production, and yield for various Indian states and districts across multiple years and seasons.

📁 Dataset Details

The dataset includes:

State & District details

Year and Season

Crop Area (in 1000 hectares)

Crop Production (in 1000 tons)

Crop Yield (kg per hectare)

Crops include: Rice, Wheat, Maize, Sorghum, Finger Millet, Pearl Millet, Groundnut, Sunflower, Soyabean, Sugarcane, Cotton, Fruits, Vegetables, etc.

🛠 Tools Used

Python – Data cleaning & EDA

MySQL – Query-based analysis

Power BI – Visualizations

Jupyter Notebook – Code execution

🔍 Work Done ✔ 1. Data Cleaning (Python)

Loaded dataset using Pandas

Verified there were no missing values

Checked data types

Cleaned & prepared for SQL insertion

✔ 2. SQL Analysis

Created table: Cultivation_data Performed queries such as:

State-wise crop production

District-level yield analysis

Season-wise comparison

Top crop-producing states

Example query:

SELECT State_Name, SUM(WHEAT_PRODUCTION) FROM Cultivation_data GROUP BY State_Name;

✔ 3. Power BI Visualizations

Built dashboards using SQL query output:

State-wise crop production map

Yearly crop trend charts

Area vs Production comparison

Top-producing districts table

Slicers for Year, State, Crop

📌 Summary

This repository gives a full workflow: Dataset → Cleaning → SQL Querying → Power BI Visualization Useful for analytics, academic projects, dashboards, and agriculture insights.
