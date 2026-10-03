# Flipkart-sales-dashboard-by-tableau-
The project uses Tableau to convert the uploaded Flipkart sales CSV data into interactive KPIs, charts, filters, clustering and time-series visualizations. Users can explore sales and profit by category, region, product, customer segment and date.
1. Project Title

Sales Performance Analysis Dashboard using Tableau

2. Objective

The main objective is to create an interactive Tableau dashboard for analyzing sales performance, profit, quantity, category-wise performance, regional performance, products, and time-based trends.

3. Project Description

The project uses Tableau to convert the uploaded Flipkart sales CSV data into interactive KPIs, charts, filters, clustering and time-series visualizations. Users can explore sales and profit by category, region, product, customer segment and date.

4. Dataset Details

Parameter

Completed Data

Dataset Name

flipkart_sales_enriched.csv

Source

User-provided CSV dataset

Number of Records

1,000

Date Range

12-Feb-2024 to 09-Feb-2025

Important Fields

Total Sales (INR), Profit (INR), Quantity Sold, Category, Region, Order Date, Product Name

Additional Fields

Order ID, Price (INR), Payment Method, Customer Rating, Month, Year, Discount %, Customer Segment

5. Tools & Technologies Used

Tableau Desktop / Tableau Public

CSV dataset

Data visualization and dashboarding

6. Tableau Worksheets / Charts

Visualization

Purpose / Fields

KPI Cards

Total Sales, Total Profit, Total Quantity, Profit Ratio, Orders

Line Chart

Sales trend over Order Date / Month

Bar Chart

Sales by Category

Regional Bar Chart

Sales by Region

Top Products Chart

Top 10 products by sales

Clustering Scatter Plot

Total Sales vs Profit, with clustering

Seasonal Sales Analysis

Monthly sales comparison

Moving Average

3-month moving average on sales trend

Forecast

Tableau forecast on historical sales

Interactive Filters

Year, Category, Region, Customer Segment

Dataset KPI Results

KPI

Value

Total Sales

₹75,213,112.74

Total Profit

₹15,042,622.55

Total Quantity

3,097

Total Orders / Records

1,000

Profit Ratio

20.00%

Average Sales per Record

₹75,213.11

Average Customer Rating

3.01

Average Discount

17.70%

Category-wise Sales

Category

Sales

Profit

Quantity

Orders

Electronics

₹17,307,173.07

₹3,461,434.61

673

217

Clothing

₹15,114,386.86

₹3,022,877.37

609

189

Books

₹14,785,759.65

₹2,957,151.93

653

209

Beauty

₹14,680,584.05

₹2,936,116.81

583

192

Home & Kitchen

₹13,325,209.11

₹2,665,041.82

579

193

Regional Sales

Region

Sales

Profit

Quantity

Orders

North

₹20,289,991.87

₹4,057,998.37

825

259

South

₹19,862,508.71

₹3,972,501.74

830

269

West

₹18,392,767.90

₹3,678,553.58

746

246

East

₹16,667,844.26

₹3,333,568.85

696

226

Top 10 Products by Sales

Rank

Product

Sales

Profit

Quantity

Orders

1

Educational Book

₹4,522,055.35

₹904,411.07

188

64

2

Laptop

₹4,132,783.72

₹826,556.74

156

48

3

Table Lamp

₹3,986,691.68

₹797,338.34

141

46

4

Headphones

₹3,722,765.27

₹744,553.05

135

44

5

Jeans

₹3,685,259.60

₹737,051.92

132

42

6

Smartwatch

₹3,680,177.80

₹736,035.56

137

47

7

Face Cream

₹3,646,816.97

₹729,363.39

124

38

8

Perfume

₹3,266,905.75

₹653,381.15

125

40

9

Fiction Novel

₹3,172,999.91

₹634,599.98

138

41

10

Jacket

₹3,161,049.05

₹632,209.81

121

38

Customer Segment Summary

Customer Segment

Sales

Profit

Quantity

Orders

Wholesale

₹25,732,035.67

₹5,146,407.13

1,026

330

Online

₹25,169,884.13

₹5,033,976.83

1,054

331

Retail

₹24,311,192.94

₹4,862,238.59

1,017

339

Monthly Sales Data

Year

Month

Sales

Profit

Quantity

2024

February

₹3,910,477.01

₹782,095.40

156

2024

March

₹6,508,879.04

₹1,301,775.81

263

2024

April

₹7,334,962.92

₹1,466,992.58

267

2024

May

₹6,706,004.97

₹1,341,200.99

278

2024

June

₹4,992,364.75

₹998,472.95

236

2024

July

₹7,637,324.95

₹1,527,464.99

309

2024

August

₹5,418,893.98

₹1,083,778.80

266

2024

September

₹6,264,222.31

₹1,252,844.46

270

2024

October

₹5,702,923.37

₹1,140,584.67

216

2024

November

₹5,578,535.08

₹1,115,707.02

252

2024

December

₹6,491,639.99

₹1,298,328.00

248

2025

January

₹7,160,788.17

₹1,432,157.63

267

2025

February

₹1,506,096.20

₹301,219.24

69

7. Calculated Fields

Calculated Field

Tableau Formula

Result

Total Sales

SUM([Total Sales (INR)])

₹75,213,112.74

Total Profit

SUM([Profit (INR)])

₹15,042,622.55

Profit Ratio

SUM([Profit (INR)]) / SUM([Total Sales (INR)])

20.00%

Average Sales

AVG([Total Sales (INR)])

₹75,213.11

Total Quantity

SUM([Quantity Sold])

3,097

Order Count

COUNTD([Order ID])

1,000

Clustering / High-Value Order Data

Measure

Value

Clustering variables

Total Sales (INR), Profit (INR), Quantity Sold

High Value definition

Total Sales (INR) >= ₹50,000

High Value orders

551

High Value Sales

₹63,785,282.34

High Value Profit

₹12,757,056.47

Important dataset limitation: there is no unique Customer ID field. Therefore, clustering should be described as purchasing/order segmentation rather than true individual-customer RFM segmentation.

8. Dashboard Screenshot

Customer Segmentation Dashboard



Sales Forecast Dashboard



9. Key Insights

1. Total sales are ₹75,213,112.74 and total profit is ₹15,042,622.55, resulting in a 20.00% profit ratio.

2. Electronics is the highest-sales category at ₹17,307,173.07, followed by Clothing at ₹15,114,386.86.

3. North records the highest regional sales at ₹20,289,991.87; South records the highest quantity sold at 830 units.

4. Educational Book is the top product by sales at ₹4,522,055.35, followed by Laptop at ₹4,132,783.72.

5. Wholesale has the highest segment sales at ₹25,732,035.67, while Online has the highest segment quantity at 1,054.
