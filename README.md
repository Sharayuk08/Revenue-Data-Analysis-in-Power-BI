# Revenue Analysis Dashboard 

![Revenue Data Analysis in Power BI](https://github.com/Sharayuk08/Revenue-Data-Analysis-in-Power-BI/assets/161645228/0d8c77bc-01ef-4fee-938f-bfe86d1650d4)


## Project Overview:

This project focuses on addressing the challenges faced by a computer hardware business in a dynamically changing market. The Sales Director aimed to gain real-time insights into sales data to make informed decisions. To achieve this, a Power BI dashboard was developed, providing comprehensive and interactive visualizations of sales metrics.


## Objectives
- Integrate MySQL database with Power BI to extract, transform, and load (ETL) sales data.
- Perform data cleaning and wrangling to ensure data quality and consistency.
- Develop an interactive Power BI dashboard for real-time revenue insights.


## Data Integration and Preparation

**Database Analysis:** Analyzed the existing sales database to understand the structure and identify key metrics.

**ETL Operations:** Connected MySQL database with Power BI to extract raw sales data.

**Data Cleaning and Wrangling:** Performed data cleaning in Power Query to normalize currency, handle invalid values, and ensure data consistency. 
This process included:
- Removing duplicates
- Handling missing values
- Normalizing currency formats
- Ensuring consistency across different data fields

![Norm Sales amount](https://github.com/Sharayuk08/Data-Analysis-Projects/assets/161645228/eb0b35f3-c635-4d72-b977-320eb9e26c10)


## Dashboard Development

#### Revenue Trend Analysis: 
Created a line chart to display revenue trends over time, providing insights into sales performance across different periods.

#### Top 5 Products and Customers by Revenue: 
Developed bar charts to highlight the top-performing products and customers, helping to identify key revenue drivers.

#### Revenue by Region: 
Implemented a bar chart to break down revenue by region, enabling a geographical analysis of sales performance.

#### Sales Quantity by Region: 
Added a bar chart to visualize sales quantity by region, complementing the revenue analysis and providing a holistic view of sales distribution

![Entitre Dashboard](https://github.com/Sharayuk08/Data-Analysis-Projects/assets/161645228/ee2a7d9f-95df-4905-b89d-0dd36e86945a)

## Interactive Features of the Dashboard

### Interactive Filtering by Year, Month, Product, Customer, and Region
One of the powerful features of this Power BI dashboard is its ability to filter insights by year, month, individual product, individual customer, and region. These interactive functionalities allow users to click on specific years, months, products, customers, and regions to view detailed insights for those selections. 
Here's how they work:

#### 1. Year and Month Selection Filter: 
The dashboard includes selection panel (filter controls) that list available years (2017, 2018, 2019, 2020) and months. These are located at the top left of the dashboard for easy access.
- The Revenue Trend chart will display the revenue trend for the chosen year and month.
- The Top 5 Products by Revenue and Top 5 Customers by Revenue charts will show the top-performing products and customers for that timeframe.
- The Revenue by Region and Sales Quantity by Region charts will update to show the performance metrics for each region during the selected period.

![Year 2019](https://github.com/Sharayuk08/Data-Analysis-Projects/assets/161645228/ded4179e-81af-46ca-9b41-5e1d56a360f1)

![2018 month 1](https://github.com/Sharayuk08/Data-Analysis-Projects/assets/161645228/23944c05-c74f-4c64-b76a-af7fa060ceb7)

![2018 month 2](https://github.com/Sharayuk08/Data-Analysis-Projects/assets/161645228/e6cc5733-9924-48a2-b320-ffdfb2745fca)


#### 2. Product Selection: 
Users can select a specific product to filter the entire dashboard based on that product's data.
- The Revenue Trend chart will display the revenue trend for the selected product over time.
- The Top 5 Customers by Revenue chart will show the top customers for the selected product.
- The Revenue by Region and Sales Quantity by Region charts will update to show the performance metrics for the selected product in each region.

![Select product 1](https://github.com/Sharayuk08/Data-Analysis-Projects/assets/161645228/ab95bc18-d223-4d74-8a7c-fc85f68814be)

![Select product 2](https://github.com/Sharayuk08/Data-Analysis-Projects/assets/161645228/147648a9-49b5-4b66-976f-0b05168d6093)


#### 3. Customer Selection: 
Users can select a specific customer to filter the entire dashboard based on that customer's data.
- The Revenue Trend chart will display the revenue trend for the selected customer over time.
- The Top 5 Products by Revenue chart will show the top products purchased by the selected customer.
- The Revenue by Region and Sales Quantity by Region charts will update to show the performance metrics for the selected customer in each region.

![Select customer 1](https://github.com/Sharayuk08/Data-Analysis-Projects/assets/161645228/33adb8a2-79f8-4bc0-b197-d228b3b9c364)


#### 4. Region Selection: 
Users can select a specific region to filter the entire dashboard based on that region's data.
- The Revenue Trend chart will display the revenue trend for the selected region over time.
- The Top 5 Products by Revenue chart will show the top products sold in the selected region.
- The Top 5 Customers by Revenue chart will show the top customers in the selected region.
- The Sales Quantity/Revenue by Region chart will update to show the sales quantity metrics for the selected region

![Revenue by region 1](https://github.com/Sharayuk08/Data-Analysis-Projects/assets/161645228/02ae1ed3-dccb-4ce2-bf9d-4abff3237f8b)

![Sale qty by region  2](https://github.com/Sharayuk08/Data-Analysis-Projects/assets/161645228/c7dff756-8594-43b0-8bef-7aadb63a5c12)

![Sale qty by region 1](https://github.com/Sharayuk08/Data-Analysis-Projects/assets/161645228/11085dcd-3010-46dd-9545-7abbbb2c7dd8)


## Key Features of the Dashboard

#### Real-Time Insights: 
The dashboard provides up-to-date information on revenue metrics, ensuring the Sales Director can make timely decisions.

#### Comprehensive Visualizations:
Utilizes a variety of charts and graphs to present data in an easy-to-understand format.

#### Geographical Analysis:
Highlights regional performance, aiding in targeted marketing and sales strategies.

#### Performance Tracking:
Enables tracking of top products and customers

#### Detailed Product, Customer, and Region Insights:
Allows users to select individual products, customers, and regions and view detailed performance metrics, enhancing decision-making.


## Conclusion
The Power BI dashboard developed in this project offers a robust solution for the computer hardware business to monitor and analyze revenue performance in real-time.








