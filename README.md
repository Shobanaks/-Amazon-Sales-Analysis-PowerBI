# 📊 Amazon Sales Analysis

## 📝 Project Overview
This project analyzes **Amazon sales performance** using **Power BI and Python**.  
The dataset has been cleaned, processed, and enhanced with additional calculated columns to uncover insights related to **profitability**, **shipping performance**, and **sales trends**.

### Key Calculations
- **Profit** — calculated for each transaction (`Sales - Cost`)  
- **Profit Margin** — `(Profit ÷ Sales) × 100`  
- **Days Took To Ship** — difference between **Ship Date** and **Order Date**

---

## 📘 Dataset Details

| Dataset | Description |
|----------|--------------|
| `Amazon_Sales_Rawdata.csv` | Original uncleaned data collected from Amazon sales |
| `Amazon_final_data.csv` | Cleaned and processed data used for visualization |
| `AmazonSalesData.pbix` | Power BI dashboard file (visualization) |

### 📏 Dataset Size
- **Rows:** ~1,000 (approx.)  
- **Columns:** 18 (after adding new calculated columns)

### 📋 Columns Overview

| Column Name | Description |
|--------------|-------------|
| `Order ID` | Unique ID for each order |
| `Order Date` | Date when the order was placed |
| `Ship Date` | Date when the order was shipped |
| `Ship Mode` | Type of shipping used (e.g., Standard, Express) |
| `Customer Name` | Name of the customer |
| `Segment` | Customer segment (Consumer, Corporate, Home Office) |
| `Country` | Country where the product was sold |
| `City` | City of the customer |
| `State` | State of the customer |
| `Postal Code` | Postal/ZIP code |
| `Region` | Sales region (e.g., East, West, Central) |
| `Category` | Product category (e.g., Furniture, Technology, Office Supplies) |
| `Sub-Category` | More specific product category |
| `Product Name` | Name of the product sold |
| `Sales` | Total sales amount |
| `Quantity` | Number of units sold |
| `Discount` | Discount applied on the product |
| `Profit` | Net profit earned from each sale |
| `Profit Margin` | Profitability percentage per order |
| `Days Took To Ship` | Time (in days) taken to ship an order |

---

## 📊 Key Insights
- Highest sales come from the **Technology** category with the best profit margins.  
- **Standard shipping** is most used but also has **longer delivery times**.  
- Certain regions show **low profit margins** due to higher discounts.  
- Profit and margin trends highlight **seasonal peaks** in sales performance.  

---

## 🧠 Tools Used
- **Microsoft Power BI** — visualization,modeling,
- **Python (Pandas, Matplotlib)** — Data cleaning,Data preprocessing.
---

## 🚀 Future Enhancements
- Added **forecast visuals** for yearly trends.  
- Create **interactive filters** by region and product category.  
---

## 👩‍💻 Author
**Shobana M**  
📧 Email: shobanamurugesan75@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/shobana-m-3542a933a)


