
# Sales Data Analysis Dashboard

This project showcases a comprehensive Tableau dashboard that analyzes sales data, providing valuable insights into revenue, profit margins, customer behavior, and market performance. The analysis is based on multiple datasets, and the visualizations enable data-driven decision-making for business growth.

## Project Overview

The dashboard is designed to deliver a holistic view of sales data by integrating different datasets such as customers, markets, products, transactions, and date-based information. The data has been cleaned and processed in Tableau using data sourced from a MySQL database through a MySQL connector.

## Datasets Used

The project uses the following five datasets:
1. **Customers**: Information about customers, including customer names and sales data.
2. **Date**: Contains date-related information to track sales trends across different years and months.
3. **Markets**: Details of various markets or regions where sales occurred, such as Delhi NCR, Mumbai, and Ahmedabad.
4. **Products**: Information about products sold, including product names and sales quantities.
5. **Transactions**: The core dataset containing details of individual sales transactions, revenue, and profit amounts. This dataset is joined with all other datasets to derive meaningful insights.

## Data Preparation and Cleaning

The data cleaning and preparation steps were performed in Tableau, with data being loaded from a MySQL database using the MySQL ODBC connector. The datasets were in the form of a `.sql` dump file, which was imported into MySQL. Here’s a brief overview of the data preparation process:
- The `.sql` dump file was downloaded and imported into the MySQL server.
- Necessary data cleaning and transformation were carried out, including removing null values, standardizing field formats, and aggregating data.
- The datasets were joined on relevant keys to ensure consistency across all visualizations.

## Dashboard Details

The Tableau dashboard comprises two main sheets, each providing specific analytical views:

### 1. Dashboard 1: Sales and Profit Analysis
- **Total Revenue and Profit**: Displays the total revenue and profit for the selected period, giving a snapshot of the overall business performance.
- **Revenue by Market**: Bar chart showing revenue generated across different markets.
- **Profit Margin by Market**: A view that compares profit margins across regions, helping to identify the most profitable markets.
- **Profit Trend**: A combination chart that tracks monthly revenue and profit margin percentage.
- **Customer Table**: Displays customer-specific sales data, profit margins, and rankings.
- **Sales Channel Distribution (Pie Chart)**: Visualizes the proportion of revenue from different sales channels, such as E-Commerce vs. Brick & Mortar.

### 2. Dashboard 2: Sales Quantity and Product Performance
- **Total Revenue and Sales Quantity**: Presents the total revenue and the number of units sold.
- **Revenue by Year**: A line chart that shows how revenue has evolved over different years, providing long-term trend analysis.
- **Top Customers**: Highlights top-performing customers based on sales revenue.
- **Top Products**: Lists the top products by sales amount, identifying key revenue drivers.
- **Revenue by Market (with Sales Quantity)**: Compares revenue and sales quantity across different regions for a detailed market analysis.

## Features and Interactivity

- **Filters and Selections**: Users can filter data based on year, month, market, and other dimensions to dynamically explore different views.
- **Interlinked Visualizations**: Clicking on a specific region, product, or customer highlights related data across other charts in the dashboard.
- **Drill-Down Capabilities**: The dashboard enables users to drill down into details by selecting a specific time period or market for more granular insights.

## How to Use the Dashboard

1. **Navigate Through Different Time Periods**: Use the year and month filters to analyze sales trends over time.
2. **Compare Market Performance**: Examine the "Revenue by Market" and "Profit Margin by Market" sections to understand which regions contribute most to the revenue and profit.
3. **Identify Top Customers and Products**: Explore the "Top Customers" and "Top Products" sections to find high-value customers and best-selling products.
4. **Analyze Sales Channels**: Use the pie chart to visualize the distribution of revenue across different sales channels.

## Getting Started

To replicate this dashboard or perform further analysis:
1. **Import the Data**: Download the provided `.sql` dump file and import it into a MySQL database server.
2. **Connect Tableau to MySQL**: Use the MySQL ODBC connector to connect Tableau to the MySQL server and load the datasets.
3. **Data Preparation in Tableau**: Perform any required data cleaning, transformation, and join operations within Tableau.
4. **Build the Dashboard**: Create individual sheets for different analyses, and then combine them into a dashboard.

## Prerequisites

- **Software Requirements**:
  - Tableau Desktop
  - MySQL Server
  - MySQL ODBC Connector

## Installation

1. **Download the `.sql` file**: [Link to `.sql` file] (to be added).
2. **Import into MySQL**:
   ```bash
   mysql -u username -p database_name < /path/to/db_dump.sql
   mysql -u username -p database_name < /path/to/db_dump_version_2.sql
   ```
3. **Set Up Tableau Connection**:
   - Open Tableau, choose "MySQL" from the data connection options, and provide the server details.
4. **Load the Data and Start Building the Dashboard**.

## Key Insights

- **High Revenue Markets**: Regions like Delhi NCR, Mumbai, and Ahmedabad show the highest revenue.
- **Profitability Differences**: Profit margins vary significantly between markets, with Bhubaneswar having a relatively higher margin.
- **Customer and Product Contributions**: Specific customers and products account for a large portion of the total sales.
- **Sales Trends Over Time**: There is noticeable seasonality in the sales data, which can be observed in the revenue trends over the months.

## Contributing

Feel free to submit issues, suggestions, or pull requests for enhancing the dashboard.


