# Business-Sales-Dashboard
### Power Query • Data Cleaning • Data Modeling • DAX • Power BI Dashboard

# 1. Project Overview

This project focuses on analyzing global sales data across multiple years, countries, and product categories. The goal of this analysis is to understand overall business performance, identify high‑value customers and top‑selling products, evaluate profit trends, and uncover patterns that can help improve decision‑making. Using Power BI, the data was cleaned, modeled, enriched with DAX calculations, and visualized through an interactive dashboard to provide actionable insights for sales, operations, and strategic planning.
This project presents a full end-to-end Data Analysis & Business Intelligence workflow using Power BI, including data cleaning, data modeling, DAX calculations, and insights visualization.

# 2. Data Cleaning & Preparation

- Handling **null values**
- Detecting and removing **duplicates**
- Correcting **data types** and ensuring validation
- Performed **Query Optimization** on the Order Details table and extracted:
        - Products table
        - Customers table
- Created a **Calendar Table** and linked it to the model
- Added **custom calculated columns** such as:
        - Days between order date and shipped date
        - Sales clustering column based on order amount (Small, Normal, Large, Very Large)

# 3. Data Modeling

A structured **star-schema** model was built to ensure clean analysis and efficient DAX performance:

- Created Products and Customers dimension tables from the optimized queries
- Established proper relationships with **the Fact Orders table**
- Added a fully linked **Calendar Table** for accurate time‑intelligence calculations
- Ensured referential integrity and optimized table structure

# 4. DAX Measures

**Key measures created:**

- Total Sales
- Total Quantity
- Profit
- Profit Margin (%)
- Net Profit
- Average Shipping Days
- Number Of Orders
- **Calculated column** Sales by Order size(Small, Normal, Large, Very Large)
These metrics were used to build a comprehensive and interactive dashboard.

# 3. Dashboard Overview

The **Power BI dashboard** contains:

- **Sales and profit** performance by country
- Year-over-year trend analysis
- Category- and product-level breakdowns
- Sales clustering visuals
- Bookmarks to switch between years and countries

![P1](Dashboard 1.png)
![P2](Dashboard 2.png)

# 4. Key Insights

- **Total Sales:** 1.45M
- **Total Quantity Sold:** 51K
- **Total Customers:** 91
- **Total Net Profit:** 94.79K
- **Profit Margin:** 6.54%
- **Average Shipping Days:** 8 days
- **Beverages** is the top-performing category in both sales and profit.
- Most orders fall under **Normal** Orders **(100–700$)** with **~56%** of total orders.
- The **USA** leads all countries in total sales.
- **Dairy Products** perform strongly in certain markets like **Austria** and **Germany**.
- **Top-selling products** include:
            - Côte de Blaye
            - Thüringer Rostbratwurst
            - Raclette Courdavault
- **France** Highest Profit Margin: **8.65%**
- **1996:** Best Profit Year; Top Company: Aux joyeux ecclésiastiques; Top Category: Beverages
- **1997:** Highest Sales Year; Top Sales Company: Plutzer lebensmittelgroßmärkte AG; Top Profit Company: Aux joyeux ecclésiastiques; Top Category: Dairy Products
- **1998:** 
            - All profits were negative, indicating financial loss despite good sales
            - **Possible causes:** high discounts, increased shipping cost, or pricing issues
- Strong upward growth from **1996** to **1997**
- Significant decline in late **1998**, especially in **profit**
- **Normal Orders** dominate the market; Very Large Orders contribute moderately **(17.5%)**
- **Beverages** consistently lead in revenue, customers, and order volume
- **Final Summary**
- **Best Year (Sales):** 1997
- **Best Year (Profit):** 1996
- **Top Country:** USA
- **Top Category:** Beverages
- **Top Company (Overall):** Aux joyeux ecclésiastiques
- **Worst Performing Year (Profit):** 1998 due to negative profit

# 5. Tools & Technologies Used

- **Power BI**
- **Power Query**
- **DAX**
- **Data Modeling**
- **Dashboard Design**

# **Summary**

This project demonstrates a complete analytics workflow:
From raw data → cleaning → modeling → DAX → business insights → dashboard.
It provides strong decision-making support and highlights key business trends.
