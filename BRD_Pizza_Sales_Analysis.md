# 🍕 Slices, Sales & Strategy  
## Business Requirements Document (BRD)

---

## 1. Project Overview
The Pizza Sales Analysis project aims to analyze transactional sales data from a pizza store to uncover business insights related to revenue performance, customer preferences, and operational trends. The analysis supports data-driven decision-making for sales, marketing, staffing, and inventory management.

---

## 2. Business Objectives
- Measure overall sales performance using key KPIs.
- Identify best-selling and least-selling pizzas.
- Analyze customer purchasing patterns by time and category.
- Support inventory, staffing, and promotional planning.

---

## 3. Stakeholders
- Restaurant Management
- Sales & Marketing Team
- Operations & Inventory Team
- Data Analytics Team

---

## 4. Data Source & Description
**Dataset:** `pizza_sales.csv`

**Key Fields:**
- `order_id` – Unique identifier for each order
- `pizza_id` – Unique identifier for each pizza
- `pizza_name` – Name of the pizza
- `quantity` – Number of pizzas sold
- `total_price` – Revenue per transaction
- `date`, `time` – Order timestamp
- `pizza_category` – Category of pizza
- `pizza_size` – Size of pizza

---

## 5. Key Performance Indicators (KPIs)
- **Total Revenue** = Sum of `total_price`
- **Total Pizzas Sold** = Sum of `quantity`
- **Total Orders** = Count of unique `order_id`
- **Average Order Value (AOV)** = Total Revenue ÷ Total Orders
- **Average Pizzas per Order** = Total Pizzas Sold ÷ Total Orders

---

## 6. Analysis Requirements
- Sales distribution by pizza category and size.
- Daily and hourly sales trends.
- Monthly sales trend analysis.
- Identification of top and bottom performing pizzas.
- Ingredient-level analysis (optional future enhancement).

---

## 7. Visualization Requirements
- Bar charts for category and size-based analysis.
- Line/bar charts for daily, hourly, and monthly trends.
- Donut charts for percentage contribution.
- Heatmaps for category vs size analysis.

---

## 8. Business Questions Answered
- What is the total revenue generated?
- Which pizzas and categories perform best?
- What days and hours have peak sales?
- How can staffing and inventory be optimized?
- Which pizzas should be promoted or reconsidered?

---

## 9. Deliverables
- Jupyter Notebook with full analysis.
- Visual dashboards and charts.
- Business Requirements Document (BRD).
- Actionable insights and recommendations.

---

## 10. Success Criteria
- Clear identification of sales trends.
- Accurate KPI calculation.
- Actionable recommendations for management.
- Easy-to-understand visualizations for stakeholders.
