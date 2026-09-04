DecodeLabs Project 2 — Exploratory Data Analysis

📊 Project Overview

This project was completed as part of the DecodeLabs Internship Program.

The objective of this project was to perform Exploratory Data Analysis (EDA) on an e-commerce dataset to identify patterns, trends, distributions, relationships, and potential outliers.

The analysis was performed using Python and Pandas, with Matplotlib used for data visualization.

🎯 Objectives

- Explore and understand the dataset
- Perform data quality checks
- Calculate descriptive statistics
- Analyze sales trends over time
- Examine categorical variables
- Identify relationships between numerical variables
- Detect and investigate potential outliers
- Summarize the key findings from the analysis

🛠️ Tools & Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Microsoft Excel

📁 Dataset

The dataset contains 1,200 e-commerce orders and 14 original columns, including:

- Order ID
- Date
- Customer ID
- Product
- Quantity
- Unit Price
- Shipping Address
- Payment Method
- Order Status
- Tracking Number
- Items in Cart
- Coupon Code
- Referral Source
- Total Price

Additional time-based features such as Year and Month were created during the analysis.

🔍 Data Cleaning

The following data-quality checks were performed:

- Checked for duplicate rows
- Checked data types
- Checked missing values
- Examined categorical variables
- Verified tracking-number uniqueness
- Handled missing coupon codes by replacing them with "No Coupon"
- Verified that "TotalPrice" matched "Quantity × UnitPrice"

No duplicate rows were identified.

📈 Analysis Performed

Descriptive Statistics

The analysis calculated:

- Count
- Mean
- Median
- Minimum
- Maximum
- Standard deviation
- Quartiles

These statistics were examined for Quantity, Unit Price, Items in Cart, and Total Price.

Time-Based Analysis

Orders and revenue were analyzed by:

- Year
- Month

This helped identify periods with higher and lower order activity and revenue.

Categorical Analysis

The project analyzed:

- Payment methods
- Order status
- Coupon usage
- Referral sources

Correlation Analysis

Relationships between numerical variables were examined using a correlation matrix.

The strongest relationship with Total Price was observed for Unit Price, followed by Quantity.

Outlier Detection

The Interquartile Range (IQR) method was used to identify potential outliers in the numerical variables.

Eight potential outliers were identified in Total Price.

Further investigation showed that these orders were associated with high quantities and high unit prices. The values were consistent with the underlying calculation of Total Price and did not appear to be obvious data-entry errors.

💡 Key Findings

- The dataset contains 1,200 orders.
- 2023 recorded the highest number of orders among the years represented.
- June had the highest monthly order volume.
- July and December recorded the lowest monthly order volume, with 87 orders each.
- Online was the most frequently used payment method.
- "FREESHIP" was the most-used coupon.
- Instagram was the leading referral source.
- Total Price showed a positive relationship with Unit Price and Quantity.
- Eight Total Price observations were identified as potential IQR outliers.
- The identified high-value orders were supported by their corresponding quantities and unit prices.

📊 Visualizations

The analysis includes visualizations showing:

- Numerical variable distributions
- Revenue by year
- Monthly order trends
- Monthly revenue trends
- Payment method distribution
- Total Price outliers

📝 Conclusion

The exploratory data analysis provided useful insights into the patterns, distributions, trends, relationships, and outliers within the e-commerce dataset.

The analysis demonstrated how descriptive statistics, visualization, correlation analysis, trend analysis, and outlier detection can be used to transform raw transactional data into meaningful business insights.

👨‍💻 Author

Francis Oluwadamilola Ayodele

Data Analytics / Data Engineering Student

DecodeLabs Internship — Project 2
