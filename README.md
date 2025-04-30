# 🍕 Pizza Sales Analytics 📊

A data analysis project using **SQL** and **Excel** to uncover actionable insights from a pizza store's sales data. This project helps identify performance metrics, customer behavior, and time-based trends to support strategic business decisions.

---

## 🚀 Features

- 🔍 Analyze total revenue, daily/monthly sales trends
- 🍕 Find top 5 best-selling pizzas by quantity and revenue
- 📅 Identify peak order hours and days
- 📦 Category-wise performance breakdown (e.g., Classic, Veggie, Meat)
- 📈 Cumulative revenue tracking using SQL window functions
- 📊 Excel dashboards and charts for visual insights

---

## 🧰 Tech Stack

- 💾 SQL (PostgreSQL / MySQL)
- 📊 Microsoft Excel
- 📁 CSV for data handling

---

## 📂 Folder Structure


``` Pizza-Sales-Analytics/ 
│ ├── data/
│ ├── orders.csv 
│ ├── order_details.csv 
│ ├── pizzas.csv 
│ └── pizza_types.csv 
│ ├── docs/ 
│ ├── Questions.pdf # List of business questions to answer 
│ └── SQL Queries.docx # Well-documented SQL solutions 
```

---

## 📌 SQL Insights Summary

### 🔹 **Basic Insights**
- ✅ **Total Orders Placed:** 4,860  
- 💰 **Total Revenue:** \$817,860.05  
- 💎 **Highest Priced Pizza:** `The Barbecue Chicken Pizza` – \$35.95  
- 📏 **Most Common Size Ordered:** Medium  
- 🔝 **Top 5 Most Ordered Pizza Types:**
  1. Classic Deluxe  
  2. Pepperoni  
  3. Hawaiian  
  4. BBQ Chicken  
  5. Cheese  

---

### 🔸 **Intermediate Insights**
- 🍕 **Most Ordered Category:** `Classic` – highest quantity across all orders  
- ⏰ **Order Distribution by Hour:** Peak hours are **12 PM – 2 PM** and **6 PM – 8 PM**  
- 🧾 **Category-wise Distribution:**
  - Classic: 35%  
  - Veggie: 25%  
  - Chicken: 22%  
  - Supreme: 18%  
- 📅 **Average Pizzas Ordered Per Day:** ~98 pizzas  
- 💵 **Top 3 Pizza Types by Revenue:**
  1. The Barbecue Chicken Pizza  
  2. Classic Deluxe  
  3. Chicken Supreme  

---

### 🔺 **Advanced Insights**
- 📊 **Revenue % by Pizza Type:**
  - Top 5 types contribute ~48% of total revenue  
- 📈 **Cumulative Revenue Trend:** Consistent growth with spikes on weekends; sharp rise during holidays  
- 🏆 **Top 3 Revenue Generators per Category:**
  - **Classic:** Classic Deluxe, Pepperoni Feast, Cheese Overload  
  - **Chicken:** Barbecue Chicken, Chicken Supreme, Spicy Chicken  
  - **Veggie:** Veggie Lovers, Margherita, Green Wave  
  - **Supreme:** Supreme Max, All Meat Supreme, House Special  

---


## 🧠 Learnings

- Efficient SQL query structuring using `JOIN`, `GROUP BY`, `CASE`
- Date and time extraction with `EXTRACT()` and `DATE_TRUNC()`
- Use of `RANK()` and `SUM() OVER()` for advanced analytics
- Data storytelling through Excel visualizations

---

## 📎 Dataset Source

- [From Internet]

---

## 🙌 Acknowledgements

- Thanks to the open-source community and Kaggle contributors.
- Inspired by real-world BI analyst case studies.

---

## 📬 Contact

Feel free to reach out!

📧 riteshpal333@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/ritesh-pal-8b7082225/)

---

⭐ **Star this repo if you found it useful!**
