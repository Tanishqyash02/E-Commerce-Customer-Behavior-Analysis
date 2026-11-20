# 🛒 E-Commerce Sales & Customer Behavior Analysis (SQL Project)

This project explores an E-Commerce dataset using advanced SQL queries to extract insights about customer behavior, sales trends, time patterns, and funnel conversion performance. All analysis was performed using **MySQL Workbench**.

---

## 📂 Dataset

- Source: [Kaggle - E-Commerce Behavior Data](https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store)
- File: `2019-Oct.csv`
- Size: 2M+ rows, includes timestamp, user_id, product, category, and event type

---

## 📊 Key Analysis Areas

### 1. 📁 Exploratory Data Analysis (EDA)
- Verified schema and missing values
- Removed corrupted timestamps (year 2106)
- Checked min/max dates, event types

### 2. 🧑‍💻 Customer Behavior
- Total unique users, purchasers, and repeat buyers
- Engagement rate per session
- Insights into user types and behavior patterns

### 3. 💰 Sales & Product Analysis
- Top-selling products by purchase count
- Revenue by brand and category
- Average Order Value (AOV)
- Top spending users

### 4. 📅 Time-Based Analysis
- Sales trends by hour, weekday, and month
- Peak sales periods identified

### 5. 🔁 Funnel Analysis
- Views: ~1,016,814  
- Cart: ~14,762 (1.45% of views)  
- Purchase: ~17,000 (1.67% of views)
- Insight: Most users purchase directly without using the cart — likely due to mobile behavior

---

## 📎 Project Structure

ecommerce-sql-project/
├── queries/
│   ├── 1.INITIAL DATA EXPLORATION (EDA).sql
│   ├── 2.CUSTOMER BEHAVIOR ANALYSIS.sql
│   ├── 3.SALES AND PRODUCT ANALYSIS.sql
│   ├── 4.TIME ANALYSIS.sql
│   └── 5.CONVERSION FUNNEL ANALYSIS.sql
├── data/
├── README.md
├── LICENSE
└── .gitignore

---

## 🔍 Key Analysis Performed

### 📊 1. Initial Data Exploration (EDA)
- Checked date ranges, event types, user IDs, and data quality
- Identified the presence of future-dated rows (e.g., year 2106)
- Determined active time range in dataset

### 👥 2. Customer Behavior Analysis
- Tracked repeat users and single-visit users
- Identified purchase patterns across users
- Segmented behavior by event types (view, cart, purchase)

### 💸 3. Sales and Product Analysis
- Found top-selling products
- Analyzed sales by category and product type
- Identified products with high cart abandonment

### ⏰ 4. Time-Based Analysis
- Analyzed sales and activity by hour, day, and month
- Found peak user activity and conversion hours

### 🔁 5. Funnel Conversion Analysis
- Calculated view-to-cart, cart-to-purchase, and view-to-purchase rates
- Visualized drop-offs in the sales funnel

---

## 📈 Insights

- 🔍 Over **1 million views**, but only **~17K purchases**
- 📉 **View-to-purchase conversion rate:** ~1.67%
- 🛍️ Majority of purchases **bypassed the cart step**
- 🕖 Most purchases occurred during **evening hours**
- 🛒 High cart abandonment rate for certain product types
  
---

## 🔧 Tools Used

- **SQL (MySQL Workbench)**
- Git & GitHub for version control
- Excel (for initial data checks)

---

## 📁 Dataset Info

- Format: `.csv`
- Rows: ~1.1 million
- Fields: `event_time`, `event_type`, `product_id`, `category_id`, `user_id`, etc.
- Source: Sample E-Commerce behavior data

  ---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

Thanks to online communities, mentors, and open datasets that support hands-on learning in data analytics.

---

## 💼 About Me

I'm an aspiring **Data Analyst** passionate about turning data into actionable insights.  
Connect with me on [LinkedIn](www.linkedin.com/in/tanishq-sharma-005367451) for collaboration, feedback, or opportunities.

---


