

Amazon Sales Analysis 2025 📊
Overview
This project performs a comprehensive exploratory data analysis (EDA) on Amazon sales data from 2025. The analysis uncovers valuable insights into sales patterns, customer behavior, product performance, and regional trends through various statistical and visual techniques.

🎯 Project Objectives
Analyze sales patterns across different time dimensions (day, week, month)

Identify top-performing products and categories

Understand customer purchasing behavior and regional preferences

Examine payment method preferences across different locations

Evaluate order status distributions and their implications

📁 Dataset
The dataset (amazon_sales_data 2025.csv) contains 250 sales transactions with the following features:

Column	Description
Order ID	Unique order identifier
Date	Transaction date
Product	Product name
Category	Product category
Price	Unit price
Quantity	Quantity ordered
Total Sales	Total transaction value
Customer Name	Customer identifier
Customer Location	Geographic location
Payment Method	Method of payment
Status	Order status (Completed/Pending/Cancelled)
🛠️ Technologies Used
Python 3

Pandas - Data manipulation and analysis

NumPy - Numerical computations

Matplotlib - Data visualization

Seaborn - Statistical data visualization

Google Colab - Development environment

📊 Analysis Performed
1. Data Assessment & Cleaning
Checked for missing values (none found)

Verified data types and unique values

Confirmed no duplicate records

Converted date columns to appropriate formats

2. Feature Engineering
Extracted day names from dates

Created month name columns

Generated week name and day-of-month features

3. Sales Analysis
Temporal Analysis
Sales by Day of Week: Identified daily sales patterns

Sales by Month: Compared monthly performance

Sales by Day of Month: Analyzed granular daily fluctuations

Categorical Analysis
Sales by Category: Pie chart showing category distribution

Top Products: Ranked products by total sales

Top Customers: Identified highest-value customers

Geographic Analysis
Sales by Location: Compared regional performance

Location-Payment Heatmap: Visualized payment preferences by region

Payment Analysis
Sales by Payment Method: Ranked payment methods by total sales

Payment-Location Matrix: Cross-tabulated payment methods with locations

Order Status Analysis
Distribution of Completed, Pending, and Cancelled orders

Bar chart visualization of status counts

🔍 Key Findings
Top Products
Refrigerator: $78,000

Laptop: $58,400

Smartphone: $48,500

Washing Machine: $27,000

Smartwatch: $15,750

Top Customers
Olivia Wilson: $36,170

Jane Smith: $31,185

Emma Clark: $29,700

John Doe: $26,870

Emily Johnson: $23,475

Top Locations
Miami: $31,700

Denver: $29,785

Houston: $28,390

Dallas: $27,145

Seattle: $26,890

Payment Methods
PayPal: $69,645

Credit Card: $61,595

Gift Card: $47,955

Amazon Pay: $32,750

Debit Card: $31,900

Order Status Distribution
Completed: 88 orders (35.2%)

Pending: 85 orders (34.0%)

Cancelled: 77 orders (30.8%)

📈 Visualizations
The project includes multiple visualizations:

Bar plots for temporal sales analysis

Pie chart for category distribution

Heatmap for location-payment method relationships

Bar chart for order status distribution

🚀 Getting Started
Prerequisites
bash
pip install pandas numpy matplotlib seaborn
Running the Analysis
Clone this repository

Open the Jupyter notebook in Google Colab or locally

Update the data path to point to your dataset location

Run the cells sequentially

Google Colab
Click the badge below to open the notebook directly in Google Colab:

https://colab.research.google.com/assets/colab-badge.svg
