# Shipping Delay Analysis in Logistics

## Project Overview
This project analyzes shipping delays in logistics operations using the DataCo Supply Chain dataset.

The goal is to identify key factors that contribute to late deliveries and provide actionable recommendations.

## Dataset
Source: Kaggle – DataCo Supply Chain  
- ~180,000 rows  
- 50+ columns  

Key variables:
- Shipping Mode  
- Order Region  
- Days for Shipment (Scheduled)  
- Days for Shipping (Real)  
- Category Name  

## Methodology
- Data cleaning (missing values, duplicates)
- Feature engineering:
  - shipping_delay = real - scheduled
  - is_late
- Exploratory Data Analysis (EDA)
- Comparative analysis by region, shipping mode, and category

## Key Findings
- Over 57% of deliveries are late
- Second Class shipping has the highest delay
- Some regions show consistently higher delays
- Delay is influenced by both shipping mode and region
  
## Hypotheses
- Certain shipping modes are associated with higher late-delivery risk.
- Some regions may have structural logistics bottlenecks.
- Product categories with higher handling complexity may face greater delays.
- The gap between scheduled and actual shipping time is influenced by both region and shipping mode.
  
## Recommendations
- Improve performance of slower shipping modes
- Focus on high-delay regions
- Optimize scheduling vs actual delivery time
- Apply category-specific strategies

## Tools Used
- Python (Pandas, Matplotlib)
- Jupyter Notebook
- PowerPoint

## Author
Tran Thi Cam Tien
