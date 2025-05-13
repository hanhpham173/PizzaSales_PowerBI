# 🍕 Pizza Sales Dashboard – Power BI Project

## 📊 Overview
This Power BI project showcases an interactive **Pizza Sales Dashboard** designed to monitor and analyze key metrics in a pizza retail business. The dashboard enables users to:

- Track sales performance  
- Identify top-selling pizzas and peak sales times  
- Understand customer preferences  
- Support data-driven decisions for growth and optimization

---

## 🎯 Project Objective
To build a dynamic and user-friendly Power BI dashboard that delivers actionable insights into pizza sales, helping businesses make informed decisions, optimize operations, and enhance customer satisfaction.

---

## 🔄 Process

### 1. Data Preparation
- Imported raw transactional data into Power BI  
- Cleaned and transformed data using **Power Query Editor**  
- Built relationships across multiple tables  
- Created custom columns and DAX measures

### 2. KPI Calculation (DAX)
- Total Revenue  
- Total Orders  
- Average Order Value (AOV)  
- Top-Selling Pizzas and Categories  
- YTD / MTD Metrics  
- YoY / WoW Growth Comparisons

### 3. Visualization Creation
- KPI Cards  
- Bar & Column Charts  
- Pie & Donut Charts  
- Time-Based Trend Lines  
- Heatmaps (hour vs. day performance)  
- Detailed Transaction Table

### 4. Dashboard Design
- Clean, user-friendly layout  
- Interactive slicers (Date, Category, Size, Order Type)  
- Filter pane and custom tooltips for interactivity

---

## 🗃️ Data Modeling

![Data Model Screenshot](https://github.com/hanhpham173/PizzaSales_PowerBI/blob/5222375d99debd4003bcff3c8add4b81d171e559/model.JPG)

### Tables Included
- **Orders**: Order ID, Date, Pizza ID, Quantity, Total Price  
- **Pizza**: Pizza ID, Name, Category, Size, Unit Price  
- **Date**: Calendar table for time intelligence  
- *(Optional)* **Customers**: For segmentation and personalization

---

## 📈 Dashboard Highlights

### 🔢 Key Metrics
- **Total Revenue**: `$834.75K`  
- **Total Orders**: `21,350`  
- **Average Order Value**: `$39.12`

### 📊 Top Performers
- **Top Category**: Classic  
- **Top Pizza**: The Classic Deluxe  
- **Top Size**: Large (L)

### 📅 Time Analysis
- **Monthly Trends**: Seasonal patterns observed  
- **Weekly Performance**: Sales peak on Fridays and weekends  
- **Hourly Heatmap**: Lunch (12–2 PM) and dinner (6–9 PM) are busiest

### 🧭 Dashboard Pages Overview

The Power BI report consists of five key dashboard pages:

1. **Sales Overview**

![Dashboard Screenshot](https://github.com/hanhpham173/PizzaSales_PowerBI/blob/5222375d99debd4003bcff3c8add4b81d171e559/sc1.JPG)  

   - Total Sales, Orders, and AOV summary
   - Sales breakdown by hour range, weekday, month, and quarter
   - Visual insights into customer order behaviors and peak periods


2. **Product Sales Overview**

![Dashboard Screenshot](https://github.com/hanhpham173/PizzaSales_PowerBI/blob/5222375d99debd4003bcff3c8add4b81d171e559/sc2.JPG)

   - Total sales distribution by Category (Classic, Chicken, Veggie, Supreme)
   - Sales by Pizza Size (L, M, S, etc.)
   - Highlights most popular pizza size, best seller, and top category


3. **Product Performance**

![Dashboard Screenshot](https://github.com/hanhpham173/PizzaSales_PowerBI/blob/5222375d99debd4003bcff3c8add4b81d171e559/sc3.JPG)

   - Best and worst performing pizzas by revenue and quantity
   - Pie charts highlighting quantity share of top and bottom pizzas
   - Useful for product rationalization and inventory planning

4. **Product Insights**

![Dashboard Screenshot](https://github.com/hanhpham173/PizzaSales_PowerBI/blob/5222375d99debd4003bcff3c8add4b81d171e559/sc4.JPG)

   - Sales trends by price across different categories
   - Correlation between ingredients and sales performance
   - Word cloud showing most frequently used and popular ingredients


5. **Customer Insights**

![Dashboard Screenshot](https://github.com/hanhpham173/PizzaSales_PowerBI/blob/5222375d99debd4003bcff3c8add4b81d171e559/sc5.JPG)

   - Multi-item vs. Single-item order comparisons
   - Avg. pizzas per order, time between orders, and customer frequency
   - Weekly ordering patterns for both multi- and single-item orders
     

---

## 💡 Key Insights

- Classic pizzas dominate revenue share  
- Large pizzas are the most preferred size  
- Sales peak during lunch and evening hours  
- Weekends outperform weekdays significantly  
- A small group of products accounts for most of the revenue (Pareto trend)

---

## 📌 Business Recommendations

1. **Promote Best Sellers**  
   Run targeted campaigns on top pizzas like *The Classic Deluxe*.

2. **Boost AOV (Average Order Value)**  
   Offer upselling combos and size upgrades during checkout.

3. **Optimize Staffing & Inventory**  
   Allocate more staff and stock during high-traffic hours.

4. **Drive Off-Peak Sales**  
   Launch midweek discounts or loyalty rewards for Mondays–Wednesdays.

5. **Menu Optimization**  
   Phase out underperforming pizzas to streamline the menu.

6. **Segmented Marketing**  
   Use order history to deliver personalized promotions (e.g., Veggie lovers).

7. **Bundle Strategy**  
   Combine popular items with slower-moving products.

8. **Seasonal Campaigns**  
   Roll out limited-time offers during holidays or special events.

---

## ✅ Conclusion
This project demonstrates core skills in:

- ✅ Data Preparation & Modeling  
- ✅ KPI Calculation using DAX  
- ✅ Dashboard UI/UX Design  
- ✅ Business Intelligence Analysis

The final product delivers a highly interactive and visually engaging dashboard that helps pizza retailers enhance sales, improve efficiency, and make smarter decisions.

---

## 🛠️ Tools Used
- Power BI Desktop  
- Power Query Editor  
- DAX (Data Analysis Expressions)  
- Sample Pizza Sales Dataset (CSV / SQL)

---
