# 🌍 Airbnb Global Insights Dashboard

This project presents an interactive Power BI dashboard built using Airbnb listing data (~332,000 rows) from multiple global cities. It enables users to explore patterns in revenue, pricing, occupancy trends, and room-type distribution to support short-term rental decision-making and market research.

## 📊 Project Overview

The goal of this project is to turn raw Airbnb listing data into actionable insights through a clean, well-structured Power BI dashboard. It provides a global view of how Airbnb properties perform across different cities and room types.

## 🔧 Tools & Technologies

- **Power BI** – for interactive dashboard development and data visualization  
- **Power Query** – for data cleaning and transformation  
- **DAX (Data Analysis Expressions)** – for calculated columns, KPIs, and aggregations  
- **Airbnb Open Data** – ~332K listings including price, location, room type, reviews, ratings, etc.

## 📈 Key Features

- **City-level performance breakdown**: Visualizes revenue and listing trends across top cities  
- **Interactive filters**: Slicers for city, price range, and room type  
- **KPIs**:  
  - Total Listings: `332K`  
  - Estimated Revenue: `$85.07B`  
  - Average Price: `$1.29K`  
  - Average Rating: `4.73`  
- **Custom visualizations**:
  - Revenue trends by city  
  - Average price comparison  
  - Room-type distribution pie chart  
  - Global map of listings  

## 🧹 Data Cleaning & Transformation

Performed using Power Query:
- Removed duplicates and irrelevant columns  
- Converted price to numeric and handled null values  
- Extracted city and region from location data  
- Standardized column types and cleaned textual fields

## 📁 Project Structure

```plaintext
📦 Airbnb-Global-Dashboard
├── 📊 Airbnb_Global_Insights.pbix        # Power BI file
├── 📄 README.md                          # Project overview (this file)
├── 📂 dataset/                           # Cleaned data used in the dashboard
│   └── airbnb_data_cleaned.csv
