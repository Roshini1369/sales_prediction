# sales_prediction
Retail Sales Data Analysis and Visualization
Objective:
The objective of this project is to perform Exploratory Data Analysis (EDA) on a retail sales dataset by:
Merging transaction-level sales data with product-level menu data.
Understanding key patterns in customer purchases and sales performance.
Identifying top-selling products, sales trends, and potential areas of improvement.
Preparing the data for potential predictive modeling tasks in the future.

Datasets Used:
Sales Dataset (sales_df):
Contains information about retail transactions, including:
Transaction ID
Date
Customer ID
Gender
Age
Product Category
Quantity
Price per Unit
Total Amount
Menu Dataset (menu_df):
Contains detailed nutritional and categorical information about available products:
Category
Item

Serving Size
Nutritional Values (Calories, Fat, Sodium, etc.)

Key Steps:
Data Merging:
Merged the sales and menu datasets based on product names (Item column).
Ensured proper matching and handled missing values appropriately.

Data Cleaning:
Checked for missing values and data types.
Selected only relevant numeric features for analysis where needed.
Exploratory Data Analysis (EDA):
Monthly Sales Trends: Visualized total sales over time to detect seasonality or trends.

Top 10 Products: Identified the best-performing products by total sales.
Sales Distribution: Analyzed sales across different product categories.
Correlation Heatmap: Examined the relationships between numeric variables such as quantity sold, unit price, and total amount.

Insights Gained:
High-performing product categories.
Peak sales periods (monthly trends).
Strong correlations between quantity, price, and total sales.

Tools and Libraries Used:
Python
Pandas (data manipulation)
Matplotlib and Seaborn (data visualization)

Future Scope:
Building predictive models to forecast future sales.
Customer segmentation based on buying patterns.
Recommendation systems to suggest products based on customer demographics.

✨ Summary:
This project successfully provided deep insights into the retail sales data through careful analysis and visualization, setting the foundation for more advanced analytics tasks such as predictive modeling and business strategy optimization
