# Diwali_Sales_Analysis
Diwali Sales Data Analysis
Overview
This project explores and analyzes Diwali Sales Data, providing valuable insights into customer behavior, sales trends, and product popularity. Using data manipulation, visualization techniques, and exploratory data analysis (EDA), this analysis uncovers key patterns based on customer demographics, purchasing behavior, and product categories.

Dataset
The dataset contains 15 columns, including user demographic information, purchase details, and product-related data. The dataset is used to analyze various factors like:

Gender, Age, Marital Status of customers
State, Zone in which customers are located
Occupation of customers
Product Category and Amount spent on products
Key Columns in the Dataset:
User_ID: Unique ID for each customer.
Cust_name: Name of the customer.
Product_ID: ID of the purchased product.
Gender: Gender of the customer.
Age Group: Age group of the customer.
Age: Exact age of the customer.
Marital_Status: Marital status of the customer (0: Single, 1: Married).
State: The state where the customer resides.
Zone: Geographical zone of the customer (Northern, Southern, etc.).
Occupation: Occupation of the customer.
Product_Category: Category of the purchased product (e.g., Food, Electronics, Healthcare).
Orders: Number of orders placed.
Amount: Total amount spent by the customer.
Status: This column was dropped due to missing data.
unnamed1: This column was dropped due to missing data.
Libraries Used
numpy: For numerical calculations.
pandas: For data manipulation and analysis.
matplotlib: For visualizations.
seaborn: For advanced visualizations.
csv: For reading and handling CSV files.
Steps Involved
Data Preprocessing:

Loaded the CSV file.
Handled missing values by dropping unnecessary columns (Status, unnamed1).
Dropped rows with null values in the Amount column.
Converted Amount to integer data type.
Data Cleaning:

Renamed columns for better readability (e.g., Marital_Status → Married).
Checked for missing values and handled them.
Exploratory Data Analysis (EDA):

Gender Analysis: Analyzed gender distribution and purchasing behavior by gender.
Age Analysis: Analyzed sales by age group and total amount spent per group.
State-wise Analysis: Investigated the top states by number of orders and total sales amount.
Marital Status: Analyzed how marital status correlates with purchasing power.
Occupation: Studied purchasing behavior across different occupations.
Product Category: Analyzed the most popular product categories and the total sales from them.
Visualizations:

Plotted bar charts and other visualizations to understand key patterns in the data.
Identified top-selling products, sales by gender, age group, and more.
Key Insights
Gender Insights: Females contribute to a higher percentage of total purchases compared to males.
Age Group Insights: The age group of 26-35 years is the most dominant in terms of both number of orders and total amount spent.
State-wise Insights: Uttar Pradesh, Maharashtra, and Karnataka have the highest number of orders and sales.
Marital Status: Married women have a significantly higher purchasing power.
Occupation Insights: Individuals working in IT, Healthcare, and Aviation sectors make the most purchases.
Top Product Categories: Food, Clothing, and Electronics dominate the sales in terms of total amount spent.
Conclusion
The analysis reveals several interesting trends, including a strong preference for specific age groups, genders, and product categories. Married women between the ages of 26-35 from Uttar Pradesh, Maharashtra, and Karnataka, working in IT, Healthcare, and Aviation, are the primary drivers of sales, especially in Food, Clothing, and Electronics categories.

Future Work
Further analysis could include:

Time-based analysis: Explore sales trends over time (before, during, and after Diwali).
Customer segmentation: Apply clustering techniques to segment customers based on their purchasing behavior.
Product Recommendation System: Build a recommendation engine to suggest products to customers based on their purchasing history.
Requirements
To run this analysis, the following Python libraries are required:

numpy
pandas
matplotlib
seaborn
