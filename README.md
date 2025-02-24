# 📊 **Online Retail Analysis**

## 📌 **Overview**
This project offers a detailed analysis of an online retail dataset sourced from UC Irvine’s Online Retail Data Repository. The dataset contains over **500,000 transactional records**, providing actionable insights into customer behavior, sales trends, and data-driven strategies for improving business outcomes.

The analysis identifies key factors driving customer purchases, highlights potential churn risks, and offers business strategies to maximize revenue and retention.

---

## 🔍 **Key Highlights**

### 🧹 **Data Cleaning & Preprocessing**
- Handled missing values and removed duplicates to ensure data accuracy.
- Standardized date-time formats and maintained consistency across categorical and numerical variables.

### ⚙️ **Feature Engineering**
- Calculated **Total Sales** for each transaction.
- Generated **Monthly Sales Trends** for time-series analysis.
- Classified customers as **new** or **returning** based on their purchase history.

---

## 📊 **RFM Analysis (Recency, Frequency, Monetary)**

### 🔑 **What is RFM?**
- **Recency (R):** Measures how recently a customer made a purchase. Recent buyers are more likely to purchase again.
- **Frequency (F):** Measures how often a customer buys within a set period. Frequent buyers are typically more loyal.
- **Monetary (M):** Measures how much a customer has spent overall. High spenders are considered more valuable.

### 🎯 **Why Use RFM Analysis?**
- Identifies high-value customers and those at risk of churn.
- Supports personalized marketing strategies.
- Improves customer retention and boosts overall revenue.

---

## 📈 **Key Insights & Business Recommendations**

### 📅 **1) Monthly Sales Trends**
- 📊 **Year-End Sales Peak:**  
  A steady rise in sales begins in **September** and peaks in **November** due to holiday shopping events like **Black Friday** and **Cyber Monday**.

- 📉 **Low-Sales Periods:**  
  Sales dip in **February** and **April**, likely due to post-holiday slowdowns.

**💡 Recommendations:**  
- Initiate promotional campaigns ahead of peak sales months (August–December).  
- Improve sales during slow months using loyalty programs and exclusive discounts.  
- Utilize predictive models to optimize inventory and resource allocation.

---

### 🌍 **2) Country-wise Sales Insights**
- The **UK** dominates with sales totaling around **9 million**.
- **Netherlands, EIRE, Germany, and France** each contribute over **2 million** in sales.

**💡 Recommendations:**  
- Enhance customer service and marketing in top-performing markets.  
- Expand in underperforming regions with localized offers and targeted promotions.  
- Diversify market reach to minimize dependence on top regions.

---

### 📦 **3) Product-wise Sales Insights**
- **Top Product:**  
  - `DOT`: **DOTCOM POSTAGE** – Over **200,000 units sold** (primary revenue driver).
- **High Sellers:**  
  - `22423`: **REGENCY CAKESTAND 3 TIER**  
  - `23843`: **PAPER CRAFT, LITTLE BIRDIE** (Both sold around **175,000 units** each).
- **Moderate Performers:**  
  - `85123A`: **WHITE HANGING HEART T-LIGHT HOLDER**  
  - `47566`: **PARTY BUNTING** (Both sold slightly over **100,000 units**).

**💡 Recommendations:**  
- Prioritize inventory for top-selling products.  
- Bundle lower-performing products with best-sellers to boost sales.  
- Re-evaluate pricing, marketing, or redesign underperforming products to increase revenue.

---

### 📊 **4) RFM Score Analysis**
- **Top Customers (RFM Score = 12):**  
  High-value customers who purchased recently, frequently, and spent significantly.

- **At-Risk Customers (RFM Score = 3):**  
  Infrequent buyers with low spending and long periods since their last purchase.

**💡 Recommendations:**  
- 🎯 Reward high-value customers with exclusive loyalty programs or early access to new products.  
- 🔁 Re-engage low-value customers using personalized offers and follow-up communications.  
- 📈 Upsell to moderately engaged customers through targeted promotions and loyalty incentives.

---

### 🔄 **5) Churn Analysis**
- **Churn Definition:**  
  Customers who haven’t purchased for over **90 days** are classified as churned. This **90-day threshold** serves as the limit in this analysis, though businesses can define their own thresholds based on their industry and business model.

- **Findings:**  
  - Identified **1,449 churned customers**.  
  - Most customers stop purchasing after **50 days** since their last transaction.

**💡 Recommendations:**  
- Run **re-engagement campaigns** targeting churned customers.  
- Offer loyalty rewards for customers approaching the churn threshold.  
- Collect feedback from churned customers to understand and address the reasons behind their inactivity.

---

## 🚀 **Why This Analysis Matters for Businesses**
- 🔍 Identifies at-risk customers using **recency** to enable proactive interventions.  
- 🔁 Helps reduce churn through re-engagement campaigns and targeted marketing.  
- 🎯 Supports better allocation of marketing efforts by focusing on high-value customers.  
- 🌍 Highlights market expansion opportunities by targeting underperforming regions.  
- 💰 Maximizes customer lifetime value (CLV) through data-driven strategies.

---

## 🛠️ **Technologies Used**
- **Python Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Machine Learning Techniques:** Clustering, Predictive Modeling  
- **Visualization Tools:** Matplotlib, Seaborn  

---

## 📬 **Conclusion**
This analysis provides actionable insights for boosting revenue, improving customer retention, and optimizing marketing efforts. Focusing on **recency** and effectively managing **churn** allows businesses to enhance customer engagement, increase revenue, and sustain long-term growth.

**📑 NOTE:** Refer to the accompanying notebook for a more detailed breakdown of the analysis and additional visualizations.
