#  Restaurant Market Strategy Analysis: Pricing, Demand & Expansion Insights

---

## 🚀 Project Overview

This project analyzes restaurant market data to identify the key factors that drive **customer satisfaction, demand, and business success**.

The goal is to transform raw data into **actionable strategies** for launching or scaling a restaurant in a competitive market.

> **Business Question:**  
> If I were opening a restaurant, what location, pricing, and strategy should I choose to maximize success?

---

##  Business Objective

To provide **data-driven recommendations** for:

-  Optimal location selection  
-  Effective pricing strategy  
-  High-performing cuisine choices  
-  Impact of online ordering  

**Target Users:**
- Restaurant owners  
- Investors  
- Food business strategists  

> The objective is not just analysis, but enabling **better business decisions**.

---

## 📂 Dataset Description

The dataset contains restaurant-level information, including:

- `restaurant_name` – Name of the restaurant  
- `restaurant_type` – Type (Casual Dining, Cafe, etc.)  
- `rating` – Average rating (out of 5)  
- `num_ratings` – Number of customer votes  
- `cost_for_two` – Approximate cost for two people  
- `online_order` – Availability of online ordering  
- `table_booking` – Table booking availability  
- `cuisines` – Type of cuisines served  
- `area` – Location of the restaurant  
- `address` – Detailed address  

---

##  Data Cleaning & Preparation

Key steps performed:

- Removed duplicates and invalid entries  
- Converted rating, cost, and votes into numeric format  
- Handled missing values using **median-based imputation** to avoid distortion from outliers  

###  Feature Engineering

- `cost_per_person` → Derived from cost for two  
- `rating_category` → Segmented into High / Medium / Low  
- Encoded categorical variables (online order, booking)  

---

##  Exploratory Data Analysis (EDA)

The analysis focuses on uncovering **decision-relevant patterns**, not just trends.

### Key Questions Explored:

- Does higher pricing lead to better ratings?  
- Do online-enabled restaurants perform better?  
- Which areas are oversaturated vs high-potential?  
- Which cuisines consistently perform well?  

### Key Observation:

Mid-priced restaurants consistently outperform both low and high-priced segments in terms of customer ratings.

---

##  SQL Analysis

SQL was used to simulate real-world business queries and extract deeper insights:

- Market performance by area  
- Pricing strategy analysis  
- Customer behavior (online vs offline)  
- Top restaurants per area  
- Overpriced restaurant identification  
- Restaurant type performance  
- Rating distribution  
- High-demand areas  

> These queries were designed to support **strategic decision-making**.

---

##  Key Insights

-  **Mid-range pricing (200–500 per person)** consistently delivers the highest customer satisfaction  
-  Restaurants offering **online ordering** perform better on average  
-  **High-density areas** increase competition and reduce differentiation  
-  Some cuisines achieve high ratings despite low presence, indicating **untapped opportunities**  

---

## 🧠 Business Recommendations

Based on the analysis:

- 📍 Choose locations with **moderate competition and strong demand**  
- 💰 Focus on a **mid-range pricing strategy**  
- 📦 Enable **online ordering from day one**  
- 🍜 Select cuisines based on **performance, not just popularity**  

> These recommendations are directly derived from data patterns across pricing, demand, and customer behavior.

---

## 📊 Dashboard (Power BI)

An interactive Power BI dashboard was developed to convert analysis into a **decision-support tool**.

### 🔍 It enables users to:

- Identify high-performing locations  
- Evaluate pricing strategies  
- Analyze customer behavior  
- Explore cuisine demand dynamically  

---

## 📸 Dashboard Preview

![Dashboard](Dashboard_Image.png)

---

##  Tools & Technologies

- **Python** (Pandas, NumPy, Matplotlib, Seaborn)  
- **SQL (SQLite)**  
- **Power BI**  

---

##  Limitations

- Dataset may not reflect real-time market dynamics  
- External factors (brand value, service quality) are not included  
- Ratings may contain bias or inconsistencies  

---

##  Conclusion

This project demonstrates how raw data can be transformed into **actionable business strategy**.

By combining Python, SQL, and Power BI, it showcases a complete workflow for solving **real-world business problems**.

> The focus is not just analysis — but **decision-making**:  
> where to invest, how to price, and how to compete.

---

## 👤 Author

**Zohair Baloch**  
Aspiring Data Analyst | SQL | Python | Power BI  

---

## ⭐ If you found this useful

Consider giving it a ⭐ or connecting for collaboration.
