# 🍕 Pizza Sales Analysis Dashboard

An interactive Pizza Sales Analysis Dashboard built with Microsoft
Power BI to analyze sales performance, customer ordering patterns,
pizza categories, sizes, and best/worst-selling products.

The dashboard converts raw pizza order data into business-focused
insights using KPIs, interactive filters, and visual analysis.

📊 Dashboard Preview

Home Dashboard



Best & Worst Sellers



Note: Add the two dashboard screenshots to an images folder in
your GitHub repository using the filenames shown above.

🎯 Project Objectives

The main objectives of this project were to:

Analyze overall pizza sales performance.

Track revenue, total orders, and pizzas sold.

Identify the best and worst-selling pizzas.

Understand sales by pizza category and size.

Analyze order patterns by day and month.

Identify busy days and ordering periods.

Build an interactive dashboard for business reporting.

🗂️ Dataset

The project uses a pizza sales dataset containing 48,620 order-line
records and 12 columns.

Main Columns

Column                Description

pizza_id            Unique ID for each pizza order line
order_id            Order identifier
pizza_name_id       Pizza product identifier
quantity            Number of pizzas sold
order_date          Date of the order
order_time          Time of the order
unit_price          Price of one pizza
total_price         Total price for the order line
pizza_size          Size of the pizza
pizza_category      Pizza category
pizza_ingredients   Ingredients used
pizza_name          Pizza name

🛠️ Tools & Technologies

Microsoft Power BI

DAX

Power Query

Data Visualization

Data Analysis

CSV Dataset

📌 Key KPIs

The dashboard provides the following major KPIs:

💰 Total Revenue: $817.86K

🍕 Total Pizzas Sold: 49,574

📦 Total Orders: 21.35K

💵 Average Order Value: $38.31

🍕 Average Pizzas per Order: 2.32

🔎 Dashboard Analysis

1. Sales Overview

The Home page provides a high-level view of:

Total revenue

Total pizzas sold

Average pizzas per order

Average order value

Total orders

Monthly order trends

Orders by day of the week

Pizza size distribution

Pizza category performance

2. Best & Worst Sellers

The second dashboard page focuses on product-level performance.

It compares pizzas based on:

Total revenue

Quantity sold

Number of orders

This makes it easier to identify products that perform strongly or
require further investigation.

📈 Key Insights

Best-Selling Products

Based on the analysis:

The Thai Chicken Pizza generated the highest revenue at
approximately $43.43K.

The Classic Deluxe Pizza had the highest quantity sold at
2,453 pizzas.

The Classic Deluxe Pizza also had the highest number of orders
at approximately 2,329.

Category Performance

The Classic category had the highest quantity sold with 14,888
pizzas.

Revenue contribution by category was approximately:

Classic --- 26.91%

Supreme --- 25.46%

Chicken --- 23.96%

Veggie --- 23.68%

Pizza Size

Large pizzas represented the largest share of quantity sold at
approximately 38.24%.

Busiest Days

Order volume was highest on:

Friday

Thursday

Saturday

Friday recorded approximately 3,538 orders.

Monthly Trend

July recorded the highest number of orders with approximately
1,935 orders.

📊 Dashboard Pages

Page 1 --- Home

The Home dashboard contains:

KPI cards

Monthly order trend

Orders by day

Pizza size analysis

Pizza category analysis

Category and monthly observations

Interactive category filters

Page 2 --- Best & Worst Seller

The Best & Worst Seller dashboard contains:

Top 5 pizzas by revenue

Top 5 pizzas by quantity

Top 5 pizzas by total orders

Bottom 5 pizzas by revenue

Bottom 5 pizzas by quantity

Bottom 5 pizzas by total orders

Interactive date filtering

🎛️ Interactive Features

The Power BI report includes interactive controls such as:

📅 Date range filter

🍗 Chicken category filter

🍕 Classic category filter

👑 Supreme category filter

🥦 Veggie category filter

Navigation between dashboard pages

Interactive charts and KPI cards

🧮 Example DAX Measures

Some of the measures used in the dashboard include:

Total Revenue = SUM(pizza_sales[total_price])

Total Pizza Sold = SUM(pizza_sales[quantity])

Total Orders = DISTINCTCOUNT(pizza_sales[order_id])

Average Order Value =
DIVIDE(
    [Total Revenue],
    [Total Orders]
)

Average Pizzas Per Order =
DIVIDE(
    [Total Pizza Sold],
    [Total Orders]
)

🔄 Project Workflow

Raw Pizza Sales Data
        ↓
Data Cleaning & Transformation
        ↓
Power Query
        ↓
Data Modeling
        ↓
DAX Measures
        ↓
Interactive Power BI Visualizations
        ↓
Business Insights

💡 Business Questions Answered

This dashboard helps answer questions such as:

How much revenue was generated?

How many pizzas were sold?

How many orders were placed?

What is the average order value?

Which pizza generates the most revenue?

Which pizza sells the highest quantity?

Which pizzas have the lowest performance?

Which pizza category performs best?

Which pizza size is most popular?

Which days have the highest order volume?

Which months generate the most orders?

📁 Repository Structure

Pizza-Sales-Analysis/
│
├── README.md
├── pizza_sales.csv
├── Pizza_Sales_Report.pbix
│
└── images/
    ├── pizza-sales-home.png
    └── pizza-sales-best-worst.png

🚀 How to Use

Clone or download this repository.

Open Pizza_Sales_Report.pbix using Microsoft Power BI Desktop.

Make sure the dataset path is correctly configured.

Refresh the data if required.

Use the filters and dashboard navigation to explore the analysis.

📚 What I Learned

Through this project, I practiced:

Data cleaning and transformation

Creating calculated measures using DAX

KPI development

Data modeling in Power BI

Interactive dashboard design

Business-oriented data analysis

Identifying sales trends and patterns

Presenting analytical findings visually

👨‍💻 Author

Abhishek T

Data Analyst | Business Intelligence | Machine Learning

GitHub: Abhishek T
