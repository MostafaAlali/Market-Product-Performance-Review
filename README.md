# 📦 UK E-Commerce Sales & Product Performance Analytics

An end-to-end data analytics project uncovering transactional trends, seasonal demand, and operational efficiency for a major UK-based online retailer.

---

## 📖 Project Background

This analysis decodes the sales dynamics of a UK e-commerce platform between December 2010 and December 2011. The company faced challenges in identifying peak activity windows, understanding geographical revenue concentration, and managing inventory for high-demand products.

By processing thousands of transactional records, this project identifies high-performing periods (like the Q4 holiday surge), optimizes logistical timing by analyzing hourly/daily order density, and provides a data-driven foundation for inventory planning and international market expansion.

---

## 🛠️ Technical Stack

- **Language:** Python 3.x  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Tools:** Jupyter Notebook, Git  

---

## 🔬 Data Structure & ETL

The dataset represents a flat-file transactional structure containing over **541,000 records** before cleaning.

---

## 📊 Executive Summary & Visual Insights

### Monthly Revenue & Average Order Value (AOV) Trend

- November recorded the highest total revenue, followed by October and September, confirming strong seasonal demand ahead of the holiday period.  
- December recorded the highest AOV despite fewer transactions, suggesting larger basket sizes and higher-value purchases during the holiday shopping window.
<p align="center">
  <img src="[your-image-url-1](https://github.com/MostafaAlali/Market-Product-Performance-Review/blob/main/images/Monthly%20Revenue%20.png)" width="45%" />
  <img src="[your-image-url-2](https://github.com/MostafaAlali/Market-Product-Performance-Review/blob/main/images/Average%20Order%20Value%20.png)" width="45%" />
</p>

---
### Revenue by Day & Time Period

- The **Afternoon period** consistently produced the highest revenue across all weekdays.  
- **Tuesday** and **Thursday** dominated peak performance windows.

### Month-over-Month (MoM) Sales Growth Analysis

- Sales momentum steadily increased toward Q4, peaking in November with **1.45M total sales** and **2,753 orders**, driven by Black Friday campaigns and holiday purchasing behavior.  
- January showed a drop in total sales (-13.6%) and orders (-30.2%) but a higher AOV (+23.9%).  
- February and April were weaker months, with sales declines of -24.3% and -25.3% respectively.  
- May experienced strong recovery (+43.6% MoM sales), supported by rising orders (+35%).  
- September and October continued the upward trend, preparing for the peak holiday season.  

**Key Takeaway:** Seasonal campaigns and holiday timing have a major impact on revenue and order volume.

---

### Top Revenue & Most Frequently Ordered Products

Products such as **REGENCY CAKESTAND 3 TIER** and **PAPER CRAFT, LITTLE BIRDIE** significantly outperform others, acting as primary revenue anchors.

Several high-frequency products appear across both top-revenue and top-order segments, confirming their strategic importance for inventory prioritization.

---

## 💡 Recommendations

- **Inventory Resilience:** Ensure maximum stock levels for top 10 products (e.g., Regency Cakestand) starting from August to prepare for the September-November surge.  
- **Temporal Incentives:** Introduce "Flash Sales" or limited-time offers during the Sunday and Early Morning windows to balance server load and stimulate demand during low-activity periods.  
- **Q2 Growth Strategy:** Since April is a historically weak month, implement aggressive "Spring Marketing" campaigns or loyalty-point boosters to bridge the revenue gap before the mid-year recovery.  
- **Market Localization:** While the UK is the core market, the top 3 international markets (Germany, France, EIRE) should be targeted with localized shipping incentives to grow the order count beyond the current sub-1000 thresholds.  

---

**Author:** Mostafa Alali
