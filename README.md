1. Title

Sales Performance Dashboard Using Power BI

2. Objective

The objective of this project is to design and develop an interactive sales dashboard using Microsoft Power BI that provides a clear visualization of overall sales performance. The dashboard aims to help decision-makers analyze sales trends, identify high-performing regions and product categories, and understand customer purchasing behavior.

3. Tools Used

Microsoft Power BI – for data visualization and dashboard creation

Microsoft Excel / CSV dataset – for storing and managing raw sales data

DAX (Data Analysis Expressions) – for creating calculated measures and KPIs

Power Query Editor – for data cleaning and transformation

4. Dataset Description

The dataset contains 5,901 records and includes detailed sales transaction data with the following attributes:

Field Name	Description
Category	Type of product sold (e.g., Furniture, Technology, Office Supplies)
City	City where the order was placed
Country	Country of the customer (primarily United States)
Customer ID	Unique identifier for each customer
Customer Name	Name of the customer placing the order
Order Date	Date on which the order was placed
ID	Unique order transaction identifier
Ind1 / Ind2	Index or reference columns used for internal analysis

The dataset also includes details about ship mode, segment, profit, and payment method, enabling a comprehensive analysis of the sales process.

5. Methodology

Data Collection and Loading:
The dataset was imported into Power BI from an Excel/CSV source.

Data Cleaning and Preparation:
Missing values were handled, data types were formatted, and unnecessary columns were removed using Power Query Editor.

Data Modeling:
Relationships were established between key fields such as Customer ID, Category, and Order Date. Calculated columns and measures were created to compute Total Sales, Total Orders, and Profit.

Dashboard Design:
Various visualizations were created to represent the data effectively:

Donut charts for segment-wise and payment mode-wise sales

Line chart for monthly sales trends (2019 vs. 2020)

Map for state-wise sales and profit distribution

Bar charts for category-wise and sub-category-wise sales

Card visuals for KPIs (Sales, Orders, Profit)

Slicers for region-based filtering (Central, East, South, West)

Insight Extraction:
Patterns and performance metrics were analyzed based on the visuals to draw meaningful business insights.

6. Dashboard Components
a. Key Performance Indicators (KPIs)

Total Sales: 450.23K

Total Orders: 6,251

Total Profit: 53.40K

b. Sales by Segment

Consumer – 50%

Corporate – 31%

Home Office – 18%

c. Sales by Payment Mode

Cash on Delivery – 44%

Card Payment – 25%

Online Payment – 31%

d. Sales by Ship Mode

Standard Class – 0.11M

First Class – 0.03M

Second Class – 0.02M

Same Day – 0.01M

e. Monthly Sales Trend

A comparative line chart for 2019 and 2020 shows a clear rise in sales towards the year-end, reflecting increased festive demand.

f. Sales by Category and Subcategory

Categories:

Office Supplies – 0.19M

Technology – 0.14M

Furniture – 0.12M

Subcategories:

Phones – 60K

Chairs – 56K

Binders – 53K

g. Regional and Geographic Analysis

A map visualization highlights that states such as California, New York, and Texas generate the highest sales and profit margins.

7. Insights

Consumer segment contributes the highest sales volume.

Standard Class shipping is the most preferred mode.

Office Supplies category generates the highest revenue.

Cash on Delivery is the most frequently used payment method.

Monthly trends show increased sales during Q4, indicating seasonal purchasing patterns.

8. Result

The dashboard successfully visualizes sales performance from multiple perspectives—regional, temporal, categorical, and customer-based. It provides a dynamic interface for exploring data and supports real-time decision-making through interactive filtering and KPIs.

9. Conclusion

The Sales Dashboard serves as a valuable analytical tool for understanding business performance. It enables managers to monitor sales trends, identify growth opportunities, and enhance operational strategies. By integrating diverse metrics into a single visual platform, this Power BI project demonstrates how data visualization can transform raw data into actionable business intelligence.
