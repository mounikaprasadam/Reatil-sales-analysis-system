Retail-sales-analysis-system
Project Overview:

This project performs exploratory data analysis (EDA) and sales forecasting for a retail dataset. It leverages Python libraries such as Pandas, Matplotlib, Seaborn, and Facebook Prophet to analyze sales trends and predict future sales.

Features:

Data Loading & Cleaning: Reads and processes sales and store information datasets.
Exploratory Data Analysis (EDA): Identifies sales trends by month, day, and store type.
Feature Engineering: Extracts useful features such as year, month, and day from the date column.
Sales Forecasting: Uses Facebook Prophet to predict future sales, considering holiday effects.

Dataset

The project uses two datasets:
sales.csv: Contains daily sales data for various stores.(zip file as size is large)
Sales_analysis_stores.csv: Includes store-related information such as type and promotions.

Results & Insights

Sales exhibit seasonal trends and are affected by promotions and holidays.
Certain store types generate consistently higher sales.
Facebook Prophet effectively captures trends and makes reasonable future sales predictions.

Plots and Subplots Used in the Analysis:

Heatmaps (Missing Data Visualization)
Histograms (Data Distribution Analysis)
Correlation Heatmap
Line Plot: Average Sales Per Month
Line Plot: Average Customers Per Month
Line Plot: Average Sales Per Day of the Month
Line Plot: Sales and Customers Based on Day of the Week
Line Plot: Average Sales by Store Type Over Time
Bar Plot: Impact of Promotions on Sales & Customers
Violin Plot: Impact of Promotions on Sales & Customers
Holiday Impact on Sales (Before, During & After Holidays)
Sales Trends Around Holidays Over Time

Following Data was predicted using prophet with a well defined function:
1- Projected Sales in 2016 and 2017 by Year 
2- Projected Sales 2016 and 2017 month wise 
3- Projected Sales 2016 and 2017 month wise with Promotion Involved
4- Top 10 Stores
5- Bottom 10 stores
