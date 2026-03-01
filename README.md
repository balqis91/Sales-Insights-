# Sales-Insights-
#  Superstore Sales Performance Analysis

##  Overview  
This project provides a detailed analysis of sales, profits, and customer segmentation for a **Superstore** using an interactive Power BI dashboard.  
The goal was to identify sales patterns, highlight profitability drivers, and present insights for strategic decision-making.  

The dashboard covers:  
-  Sales, Profit, and Cost Analysis  
-  Product Performance (Top 5 Products)  
-  Regional & State-Level Sales  
-  Monthly and Quarterly Trends  
-  Customer Segmentation by Order Volume & Revenue  

---

##  User Requirement  
The stakeholders requested a solution to:  
- Track **total sales, cost, and profit** performance.  
- Identify **top-selling products and categories**.  
- Understand **regional/state contributions** to sales.  
- Monitor **sales trends across months and quarters**.  
- Segment customers to assess their value and behavior.  
- Build a **data model** connecting Orders, Customers, Sales Teams, and Date dimensions.  

---

##  About the Dataset  
- **Source:** [Sample Superstore Dataset – Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final) 
- **Records:** 9,000+ sales transactions  
- **Columns include:**  

| Column         | Description |
|----------------|-------------|
| `Order ID`     | Unique transaction identifier |
| `Customer ID`  | Unique customer identifier |
| `Order Date`   | Date of purchase |
| `Ship Date`    | Shipping completion date |
| `Sales`        | Sales revenue (£) |
| `Quantity`     | Units purchased |
| `Discount`     | Discount applied |
| `Profit`       | Profit per transaction |
| `State`        | State location of customer |
| `Segment`      | Customer segment (Consumer, Corporate, Home Office) |

---

##  Data Cleaning & Preparation  
- Removed **null values** and corrected inconsistent state names.  
- Standardized `Date` formats for time-series analysis.  
- Created calculated fields:  
  - `Total Profit = Sales - Cost`  
  - `Average Sales per Order`  
- Linked tables:  
  - **Orders**, **Customers**, **Sales Teams**, and **Date** using relationships.  
- Filtered out invalid discounts and duplicate orders.  

---

##  Modelling & Visualization  

###  Data Model  
The model integrates multiple tables:  

<img width="1142" height="721" alt="image" src="https://github.com/user-attachments/assets/533be7c1-85d1-4f3d-8b05-a91be60bd806" />

###  Dashboard Preview  
Here is the interactive **Superstore Sales Dashboard**:  
<img width="1301" height="727" alt="image" src="https://github.com/user-attachments/assets/5303d5de-4f44-4953-9874-d20becfc26bd" />

<img width="1302" height="722" alt="image" src="https://github.com/user-attachments/assets/37a7e267-c9df-4bf7-a487-2588d0a208b7" />


###  Key Visuals  
- **KPIs:** Total Cost (£2.01M), Total Sales (£2.30M), Average Sales (£229.86), Total Profit (£286K), Orders (5,008), Customers (793).  
- **Pie Charts:** Sales by State & Quarterly Sales Distribution.  
- **Bar Charts:** Top 5 Products & Profit by Day.  
- **Line Chart:** Monthly Sales Trends.  
- **Table:** Customer Segmentation by Total Sales & Count.  

---

##  Findings  
- **Top State:** California led sales with **38% contribution**, followed by New York.  
- **Best-Selling Product:** *Canon imageCLASS 2200 Advanced Copier* contributed the highest revenue (£62K).  
- **Quarterly Trend:** Q4 recorded the highest sales (£875K).  
- **Customer Segments:**  
  - *Consumers* contributed the majority (£1.16M).  
  - *Corporate* customers contributed £706K.  
  - *Home Office* accounted for £429K.  
- **Profitability by Day:** Sundays and Wednesdays showed the highest profit margins.  

---

##  Conclusion  
The analysis highlights that **California and Consumer customers drive the majority of sales**, with Q4 being the peak quarter.  
To optimize business performance, management should:  
- Focus marketing campaigns in **California & New York**.  
- Stock up on **top-selling products** before Q4.  
- Offer targeted promotions on **low-profit days (Monday & Thursday)**.  
- Expand customer loyalty programs for the **Consumer segment**.  

---

##  Tools Used  
- **Power BI** – Dashboard creation & data modelling  
- **Excel** – Data cleaning and initial exploration  
- **DAX & Power Query** – Calculated measures and transformations  

---

 Created by [Balikisu Ajoke Oniyide]  
