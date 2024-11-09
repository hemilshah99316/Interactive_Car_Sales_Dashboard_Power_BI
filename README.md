# 🚗Interactive Car Sales Dashboard

## 📊 Overview
This project showcases an interactive **Car Sales Dashboard** created in **Power BI**. The dashboard allows users to explore and analyze car sales data with various filters and visualizations, offering insights into sales trends, budget performance, and profitability across different regions, categories, and customer segments.

The data was cleaned and transformed using **Power Query Editor** in Power BI to ensure accuracy and relevance of the visualizations.

## ✨ Key Features
- **🔍 Filters and Slicers**: 
  - Filter data by **Country**, **City**, **Region**, **Ship Mode**, and **Year** to analyze specific sales data.
- **📈 Sales by Segment and Category**:
  - **Current Year Sales by Segment**: A chart showing sales distribution across various customer segments.
  - **Current Year Sales by Category**: A chart that breaks down sales by product category.
  - **Current Year Sales by Month**: A monthly trend chart illustrating seasonal variations in sales.
- **📊 KPIs**: Aggregate key performance indicators (KPIs) for quick insights, including:
  - **Total Sales** 💵
  - **Budget vs. Sales Comparison** 💼
  - **Total Profit** 💸
- **📁 Data Source**: Cleaned and engineered dataset with details like sales, discounts, and profits for individual orders.

## 🗂️ Sample Data Structure
The dataset includes the following columns:

| 🆔 Row ID | 📦 Order ID | 📅 Order Date | 🚚 Ship Date | 🚢 Ship Mode | 👤 Customer ID | 🧑 Customer Name | 👥 Segment | 🌎 Country/Region | 🏙️ City | 🏛️ State/Province | 📮 Postal Code | 🌐 Region | 🛒 Product ID | 🏷️ Category | 📄 Sub-Category | 💲 Sales | 🔢 Quantity | 🎟️ Discount | 💰 Profit |
|-----------|-------------|---------------|--------------|--------------|----------------|------------------|------------|-------------------|----------|-------------------|---------------|-----------|---------------|-------------|----------------|---------|------------|-------------|----------|
| 1         | US-2019-103800 | 03/01/2019 | 07/01/2019 | Standard Class | DP-13000 | Darren Powers | Replacement | United States | Houston | Texas | 77095 | Central | OFF-PA-10000174 | Third Party | Paper | 16.45 | 2 | 0.2 | 5.55 |
| 2         | US-2019-112326 | 04/01/2019 | 08/01/2019 | Standard Class | PO-19195 | Phillina Ober | Other | United States | Naperville | Illinois | 60540 | Central | OFF-BI-10004094 | Third Party | Binders | 3.54 | 2 | 0.8 | -5.49 |
| 3         | US-2019-112326 | 04/01/2019 | 08/01/2019 | Standard Class | PO-19195 | Phillina Ober | Other | United States | Naperville | Illinois | 60540 | Central | OFF-LA-10003223 | Third Party | Labels | 11.78 | 3 | 0.2 | 4.27 |
| ...       | ...         | ...           | ...          | ...          | ...            | ...              | ...        | ...               | ...       | ...               | ...           | ...       | ...           | ...         | ...            | ...     | ...        | ...         | ...      |

## 📊 Visualizations
The dashboard includes the following visualizations:
1. **Current Year Sales by Segment** 🧑‍🤝‍🧑: Helps identify top-performing customer segments.
2. **Current Year Sales by Category** 🏷️: Provides insights into popular product categories.
3. **Current Year Sales by Month** 📅: Displays monthly sales trends to reveal seasonal patterns.

## 📈 Insights
- **Sales Performance by Region and Segment** 🌍: Highlights the top-performing regions and customer segments.
- **Category Analysis** 🏷️: Identifies high-selling product categories.
- **Monthly Trends** 📆: Highlights peak sales months for seasonal planning and forecasting.

## 🛠️ Technologies Used
- **💻 Power BI**: For data cleaning, transformation, and visualization.
- **🛠️ Power Query Editor**: Used for data cleaning and transformation.
- **📐 DAX Measures**: Custom calculations for KPIs and metrics.

## 📥 How to Download and Run the Power BI File
To download and open the Car Sales Dashboard `.pbix` file, follow these steps:

1. **Download the `.pbix` File**:
   - Go to the [GitHub repository](https://github.com/hemilshah99316/Interactive_Car_Sales_Dashboard_Power_BI).
   - Click on the **CarSalesDashboard.pbix** file in the repository.
   - Select **Download** to save the `.pbix` file to your local system.

2. **Open in Power BI**:
   - Make sure **Power BI Desktop** is installed on your computer. You can download it from the [Power BI website](https://powerbi.microsoft.com/desktop/).
   - Open Power BI Desktop, then go to **File > Open** and select the downloaded `.pbix` file to load the dashboard.

3. **Explore the Dashboard**:
   - Use the slicers (filters) on the dashboard to interact with and analyze the data.
   - Hover over charts to see detailed insights, such as sales figures, profit margins, and trends across different segments.
