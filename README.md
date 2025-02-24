# 📊 **Online Retail Analysis**

## 📌 **Overview**
This project provides a comprehensive analysis of an online retail dataset sourced from UC Irvine’s Online Retail Data Repository. The dataset contains over **500,000 transactional records**, offering valuable insights into customer behavior, sales trends, and opportunities for data-driven business growth.

The goal is to identify purchasing patterns, customer segments, and factors contributing to customer churn while developing strategies to boost retention and revenue.

---

## 🔍 **Key Highlights**

### 🧹 **Data Cleaning & Preprocessing**
- Removed duplicates and handled missing values.
- Standardized date-time formats and ensured consistency in data columns.

### ⚙️ **Feature Engineering**
- Calculated **Total Sales** per transaction.
- Developed **Monthly Sales Trends** and categorized customers as **new** or **returning**.

---

## 📈 **Key Insights & Business Recommendations**

### 📅 **1) Monthly Sales Trends**
- 📊 **Year-End Sales Surge:**  
  Sales rise steadily from **September** and peak in **November**, likely due to holiday shopping events like **Black Friday** and **Cyber Monday**.

- 📉 **Low-Sales Periods:**  
  Notable sales dips in **February** and **April**, likely due to post-holiday slowdowns.

**💡 Recommendations:**  
- Launch promotions ahead of peak sales months (August–December).  
- Boost sales during slow months with loyalty programs and exclusive offers.  
- Improve forecasting to optimize inventory and resource allocation.

---

### 🌍 **2) Country-wise Sales Insights**
- The **UK** dominates sales with ~**9 million** in revenue.
- **Netherlands, EIRE, Germany, and France** contribute over **2 million** each.

**💡 Recommendations:**  
- Enhance service quality and marketing efforts in top-performing countries.  
- Expand into underperforming regions with localized campaigns and offers.

---

### 📦 **3) Product-wise Sales Insights**
- **Top Product:** `DOT` sold over **200,000 units**.  
- **High Sellers:** `22423` and `23843` sold nearly **175,000 units** each.  
- **Moderate Sellers:** Products like `85123A` and `47566` underperform.

**💡 Recommendations:**  
- Prioritize inventory for best-selling products.  
- Bundle low-performing products with high-selling ones.  
- Re-evaluate pricing and marketing for underperforming products.

---

### 📊 **4) RFM Score Analysis**

### 🔑 **What is RFM?**
- **Recency (R):** Measures how recently a customer made a purchase. Recent buyers are more likely to purchase again.
- **Frequency (F):** Measures how often a customer makes purchases. Frequent buyers are considered more loyal.
- **Monetary (M):** Measures how much money a customer has spent overall. High spenders are considered more valuable.

### 🎯 **Why Use RFM Analysis?**
- Identifies high-value customers and potential churn risks.
- Helps develop personalized marketing strategies.
- Enables businesses to improve customer retention and increase revenue.

- **Top Customers (RFM Score = 12):**  
  High-value customers who purchase **frequently**, **recently**, and spend significantly.

- **At-Risk Customers (RFM Score = 3):**  
  Infrequent buyers with long purchase gaps and low spending.

**💡 Recommendations:**  
- 🎯 Offer exclusive rewards to high-value customers.  
- 🔁 Re-engage low-value customers with personalized offers.  
- 📈 Upsell to moderately engaged customers with targeted promotions.

---

### 🔄 **5) Churn Analysis (Recency-Focused Insight)**
- **Churn Definition:**  
  Customers who haven’t purchased for over **90 days** are classified as churned. This 90 days threshold is my limit. Companies can choose their own threshold.

- **Findings:**  
  - Identified **1,449 churned customers**.  
  - Most customers stop purchasing after **50 days**.

**💡 Recommendations:**  
- Launch **re-engagement campaigns** for churned customers.  
- Offer loyalty rewards for customers nearing the churn threshold.  
- Set up **predictive alerts** for customers approaching 90 days without purchases.

---

## 🚀 **Why This Analysis Matters for Businesses**
- 🔍 **Recency Focus:** Helps identify at-risk customers based on recent activity.
- 🔁 **Churn Reduction:** Develops proactive strategies to minimize customer attrition.
- 🎯 **Targeted Marketing:** Tailors campaigns based on customer purchase behavior.
- 🌍 **Market Expansion:** Identifies underperforming regions for business growth.

---

## 🛠️ **Technologies Used**
- **Python Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Machine Learning Techniques:** Clustering, Predictive Modeling  
- **Visualization Tools:** Matplotlib, Seaborn  

---

## 📬 **Conclusion**
This analysis helps businesses maximize revenue, improve customer retention, and optimize marketing strategies. By focusing on **recency** and proactively addressing **churn**, companies can boost long-term growth and increase **Customer Lifetime Value (CLV)**.
