# Maven-Roasters-Sales-Analysis
Coffee shop sales analysis using Power BI: KPIs, trends, and product performance for Maven Roasters.
# Maven Roasters Sales Analysis (Power BI)

## Project Overview
This project analyzes transaction data for **Maven Roasters**, a fictitious coffee shop with three locations in New York City:
- Astoria
- Hell’s Kitchen
- Lower Manhattan

The goal is to understand sales trends, customer behavior, peak hours, and product performance using **Power BI**.

---

## Data Model
A **Star Schema** was created to improve performance and clarity.

**Fact Table**
- Transactions (Sales, Quantity, Date, Time, Store, Product)

**Dimension Tables**
- Date
- Time
- Store
- Product

![Star Schema](data_model/star_schema.png)

---

## Key Questions Answered
- How do sales trend over time?
- Which days and times are busiest?
- Do sales patterns differ by store?
- Which products drive the most revenue?

---

## Store-Level Insights & Recommendations

### Astoria
**Finding:**  
Sales peak between **7–10 AM**, especially on **Mondays, Thursdays, and Fridays**. **June** recorded the highest sales.

**Recommendation:**  
Increase staffing during morning peak hours and introduce loyalty or morning promotions on key weekdays.

---

### Hell’s Kitchen
**Finding:**  
Strong sales from **6–10 AM**, with Fridays and Tuesdays performing best.

**Recommendation:**  
Run “Morning Rush” promotions and strengthen marketing on Tuesdays and Fridays.

---

### Lower Manhattan
**Finding:**  
Peak sales at **10 AM**, with **Monday** as the busiest day. June performed best.

**Recommendation:**  
Focus on Monday promotions and introduce evening discounts after **6 PM** to balance daily sales.

---

### Overall Performance
**Finding:**  
Fridays generate the most sales. June is the strongest month, while January–February are weaker.

**Recommendation:**  
Allocate more staff on Fridays, run seasonal promotions in Jan–Feb, and launch new products in June.

---

## Tools Used
- Power BI (Data Modeling, Power Query, DAX, Visualizations)
- GitHub (Project Documentation)

---

## Dashboard Preview
![IMAGE alt](images/overview_page.png)
![IMAGE alt](https://github.com/abdulrahman238/Maven-Roasters-Sales-Analysis/blob/37eb8a2f0fbac88feb023380e4411e1076e08e50/lcation%20analysis.png))
![IMAGE alt](images/product_analysis.png)
