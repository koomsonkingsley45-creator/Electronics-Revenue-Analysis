# Electronics-Revenue-Analysis
I developed this Python project to automate the analysis of global sales for electronics and accessories. I used Pandas to calculate revenue and quantities across different countries, using dates to identify key performance trends.

# Project Overview
This project focuses on analysing a global sales dataset for electronics and accessories. I used Python to process raw data containing unit prices, quantities sold, and revenue across different countries. The goal was to provide a clear picture of which product categories and regions are driving business growth.

# Objectives
Based on my Python analysis, the primary objectives were:
•	**Data Cleaning:** Managing date formats and ensuring numerical consistency across "Unit Price" and "Quantity" columns.
•	**Regional Analysis:** Comparing sales performance and revenue generation across different Countries.
•	**Product Segmentation:** Identifying trends between the Electronics and Accessories categories.
•	**Trend Identification:** Analysing revenue fluctuations over specific Dates to identify peak sales periods

# Methodology
I implemented the following steps in my Jupyter Notebook:
•	**Data Import:** Loaded the dataset using pandas to handle the large volume of sales records.
•	**Calculation Logic:** I used Python to automate the calculation of total Revenue by multiplying Unit Price and Quantity for every row.
•	**Filtering:** Grouped the data to compare the performance of high-value electronics against high-volume accessories.
•	**Visualization:** Created charts to display the distribution of sales across different global markets.

# Key Metrics & Findings
My analysis of the dataset revealed:
•	**Volume Leader:** Accessories accounted for the highest Quantity of items sold.
•	**Revenue Leader:** Electronics generated the most significant portion of total Revenue due to higher unit costs.
•	**Top Markets:** Identified specific Countries that outperformed others in terms of total units moved.
•	**Time Trends:** Sales spikes were clearly visible on specific Dates, suggesting seasonal demand for certain electronic goods.

**Visual Insights:** Some visuals are displayed below;
![Regional Sales and Revenue Analysis](https://github.com/user-attachments/assets/b90a5500-1e51-4de2-a08e-b6815ed7cfe5)
![Electronics vs Accessories Performance](https://github.com/user-attachments/assets/d79b4fcb-9457-48ba-bdf9-cfab4db8605f)

# Challenges Faced
•	**Date Standardization:** Converting the raw Date strings into Python datetime objects so they could be sorted chronologically.
•	**Data Integrity:** Identifying and correcting any mismatches where the quantity and revenue figures did not align correctly.

# Conclusion
This project demonstrates how Python can be used to manage complex sales data more efficiently than manual tools. By automating the revenue calculations and regional grouping, I provided a scalable way for a business to track its electronics and accessories inventory and sales performance.

# Recommendations
•	**Inventory Management:** Increase stock levels for Accessories in top-performing Countries to meet high quantity demands.
•	**Trgeted Marketing:** Focus high-value Electronics promotions around the peak Dates identified in the trend analysis.









