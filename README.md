# Myntra-Product-analysis

## Overview  
This project analyzes Myntra product data using **Excel** and **Power BI** to uncover key trends and insights. The dataset consists of various attributes such as category, gender, size, discount price, original price, ratings, and reviews. The goal was to clean and standardize the data for effective analysis and visualization.

## Data Cleaning & Preparation (Excel)  
To make the dataset **analysis-ready**, the following transformations were applied:
- **Standardization** of key fields such as category, gender, and size.
- **Discount Percentage Calculation:** Extracted values from inconsistently formatted data (e.g., "100off," "Rs. 100 off," "20%") using `LEFT` and `RIGHT` formulas.
- **Size Range Standardization:** Unified multiple size columns into a single **size range** column.
- **Handling Missing Data:** Reviews and ratings were set to 0 where unavailable.
- **Rating Labeling:** Categorized ratings into:
  - 0-1 → Terrible
  - 1-2 → Bad
  - 2-3 → Okay
  - 3-4 → Good
  - 4-4.5 → Very Good
  - 4.5-5 → Awesome  
  *(This helped in raw data understanding but was excluded from Power BI visualizations to maintain a numeric focus.)*

## Visualization & Insights (Power BI)  
The dashboard titled **"Myntra Product Analysis"** features:
- **Interactive Slicers** for filtering by gender, category, and individual category.
- **Key Metrics Cards** displaying:
  - Average Discount
  - Average Price
  - Average Rating
- **Graphs & Tables**:
  - Average Price by Category
  - Top 10 Individual Categories by Rating
  - Category-wise Size Range Availability  
  - Average Rating & Discount Percentage by Category
  - Average Reviews by Individual Category  
- **Insights Summary Page** titled **"Fashion by the Numbers: Smart Picks & Hot Drops"** presenting key observations.
- **Q&A Bar** for exploring trends with pre-defined queries.

## Check out the project:
- Power BI Workspace: [https://app.powerbi.com/groups/me/reports/f6f629a6-74c7-43d7-a24b-a2830fc745af/563cec3cbbfa279f8a3d?experience=power-bi]
- Web Link: [https://app.powerbi.com/view?r=eyJrIjoiMWQzZWFjN2EtODM5OS00MWUxLWI4ZTUtMGY1N2Y2YzI1NGQzIiwidCI6ImQyNWI2NTIxLTViZTYtNDAxNC04NDNmLTU4NDRmNDE5YWY3MyJ9&pageName=563cec3cbbfa279f8a3d]
- QR Code: [https://drive.google.com/file/d/1BN_O_py-iEnyiiWptDH9SJg_Jc3P44tj/view?usp=sharing] (link to QR code image)

## Conclusion  
This project provides a **data-driven perspective** on Myntra’s product offerings, helping consumers and analysts make informed decisions. The combination of **Excel data preparation** and **Power BI visualizations** ensures comprehensive analysis.


