# 📊 Brazilian E-Commerce Analytics (Olist Store)

This project provides a comprehensive analysis of the **Olist E-commerce** dataset (100k+ orders). It transforms raw data into a strategic tool for monitoring sales, logistics, and customer satisfaction.

🔗 **[Live Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZGRkMzBmYzQtZWYxMC00ODU3LWE0MWYtMDRjYTEyYTJlNWVlIiwidCI6ImVhZjYyNGM4LWEwYzQtNDE5NS04N2QyLTQ0M2U1ZDc1MTZjZCIsImMiOjh9)**

---

## 🚀 Key Features & Insights

### 1. Seller Performance & Operational Excellence
Monitoring seller efficiency using custom KPIs and visual alerts.
* **Top Sellers:** Identified top performers by revenue (up to **R$ 163K**).
* **Delivery Bottlenecks:** Used conditional formatting to highlight sellers with extreme delays (up to **190 days**).
* **Visuals:** Integrated **Data Bars** and **Icons** for instant performance evaluation.

![Seller Performance](./image_458078.png)

---

### 2. Advanced AI Analytics
Using Power BI's machine learning capabilities to drive decisions.
* **Key Influencers:** Discovered that delivery times over **32 days** are the primary reason for a **1.93** drop in review scores.
* **RFM Segmentation:** Classified the customer base, revealing that **89.79%** fall into the "Others" category, highlighting a massive opportunity for retention strategies.
* **Decomposition Tree:** Drilled down into the **R$ 6.52M** total revenue by Quarter and Category.

![Advanced Analytics](./image_50bf02.png)

---

### 3. Market Basket Analysis
Understanding purchasing behavior through product associations.
* Analyzed **Order Density** to see which categories (like `agro_industry_and_commerce`) frequently appear in multi-item orders.

![Basket Analysis](./image_506221.png)

---

## 🛠️ Technical Implementation
* **DAX Formulas:** Developed for RFM scoring, dynamic dates, and custom aggregations.
* **Conditional Formatting:** Built custom logic for color gradients (Red to Green) based on review scores.
* **Navigation:** Built a seamless user experience using a custom **Navigator Bar** and **Reset Filters** buttons.

---

## 📂 Data Source
The analysis is based on the [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) on Kaggle.
