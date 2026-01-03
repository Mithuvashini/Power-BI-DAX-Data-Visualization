# 📊 Power BI – DAX & Data Visualization  
## E-Commerce Sales Analysis

This project analyzes e-commerce sales data using **Power BI**, focusing on **data modeling, DAX calculations, and insight-driven visualizations**.  
The objective is to evaluate **sales performance, profitability, targets, and regional trends** using industry-standard BI practices.

---

## 📁 Datasets Used

- **List of Orders.csv**  
  Contains order-level information such as Order ID, Order Date, City, State, and Category.

- **Order Details.csv**  
  Contains transactional details including Amount, Quantity, Profit, Category, and Sub-Category.

- **Sales Target.csv**  
  Contains sales targets by Category and Segment.

---

## 🔗 Data Modeling

- Relationships created before visualization
- Proper keys used between:
  - `List of Orders` ↔ `Order Details`
  - `Sales Target` ↔ `Order Details`
- Verified filter flow and aggregation accuracy

---

## 🧮 Calculated Columns (DAX)

### 1️⃣ Category Type  
**Table:** Order Details  
Combines Category and Sub-Category into a single field.

### 2️⃣ Revenue per Order
**Table:** Order Details
Calculates revenue at the row level.

### 3️⃣ Sales Category
**Table:** Order Details
Classifies orders as Above or Below Average based on Amount.

---

## 🧮 Calculated Measures (DAX)

### 1️⃣ Order Count
Counts total number of orders.

### 2️⃣ Average Profit – Delhi
Calculates average profit for orders placed in Delhi.

### 3️⃣ Year-to-Date (YTD) Sales
Calculates cumulative sales over time.

---

## 📊 Data Visualization – E-Commerce Sales Analysis (Power BI)

## 1. Sales Target Achievement by Category
**Visualization:** Clustered Column Chart  

**Objective:**  
Compare actual sales against predefined sales targets across different product categories.

**Insight Delivered:**  
- Quickly identifies overperforming and underperforming categories  
- Highlights gaps between targets and actuals for performance evaluation  

---

## 2. Maximum Profit Margin by Sub-Category
**Visualization:** Donut Chart  

**Objective:**  
Analyze the maximum profit margin achieved within each product sub-category.

**Insight Delivered:**  
- Identifies high-margin sub-categories  
- Helps prioritize profitable product lines over high-volume but low-margin items  

---

## 3. Monthly Sales Trend
**Visualization:** Line Chart  

**Objective:**  
Track sales performance over time on a monthly basis.

**Insight Delivered:**  
- Reveals seasonality and sales growth patterns  
- Helps detect anomalies, spikes, or declining trends  

---

## 4. Comparison of Profit and Quantity by Sub-Category
**Visualization:** Scatter Chart  

**Objective:**  
Analyze the relationship between profit and quantity sold for each sub-category.

**Insight Delivered:**  
- Identifies high-volume, low-profit products  
- Highlights sub-categories that balance volume and profitability  

---

## 5. Total Sales Amount vs Sales Target
**Visualization:** Card & Multi-Row Card  

**Objective:**  
- Display total sales amount and overall sales target for quick comparison  
- Show minimum target values for each customer segment

**Insight Delivered:**  
- Instant KPI snapshot for decision-makers  
- Segment-level target benchmarking  

---

## 6. Sales Performance Matrix
**Visualization:** Matrix  

**Objective:**  
Compare actual sales and sales targets across categories and months.

**Insight Delivered:**  
- Detailed cross-dimensional performance analysis  
- Enables trend comparison across time and product categories  

---

## 7. Geographic Sales Analysis
**Visualization:** Map Chart  

**Objective:**  
Visualize total sales distribution by city.

**Insight Delivered:**  
- Identifies high and low performing regions  
- Supports regional sales strategy and market expansion decisions  

---

## 8. Sales Distribution by Sub-Category
**Visualization:** Treemap  

**Objective:**  
Represent the proportion of total sales contributed by each sub-category.

**Insight Delivered:**  
- Highlights dominant and niche product segments  
- Helps in inventory and marketing prioritization  

---

## 9. Order Count Analysis by State
**Visualization:** Funnel Chart  

**Objective:**  
Analyze the distribution of order counts across different states.

**Insight Delivered:**  
- Identifies states with high and low order volumes  
- Useful for logistics planning and regional performance assessment  

---

## 🛠 Tools & Techniques Used
- Power BI Desktop  
- DAX for calculated measures  
- Data modeling and relationships  
- Interactive and performance-focused visual design  

---

## 📌 Key Takeaway
These visualizations collectively provide a **clear, multi-dimensional view of sales performance**, enabling data-driven decisions around profitability, targets, geography, and product strategy.



