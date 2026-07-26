#  Apple Global Sales Performance & Customer Behavior Dashboard

## Executive Summary
This project provides an end-to-end multi-page Power BI analysis of **$18.04M in revenue** generated across **47 countries**. Using granular transactional data, this dashboard evaluates global market performance, product category dominance, customer demographics, sales channel effectiveness, and ecosystem switching trends (e.g., Android-to-iPhone conversions).

The goal of this analysis is to identify key drivers of revenue, understand regional consumer behavior, and uncover high-growth opportunities for marketing and inventory optimization.

---

##  Key Executive KPIs
* **Total Revenue:** **$18.04M**
* **Total Units Sold:** **23K units**
* **Average Selling Price (ASP):** **$775.06**
* **Global Reach:** **47 Countries Served**

---

##  Key Insights & Analysis Across 4 Dashboard Views

### 1. Executive Sales Overview
* **Global Footprint:** Revenue is heavily concentrated in key international markets, led by **Hong Kong**, followed by **Netherlands, Mexico, Canada, and Turkey**.
* **Quarterly Stability:** Quarterly revenue trends remain consistent throughout Q1–Q4, with **Mac** and **iPhone** maintaining steady baseline leadership across all quarters.

### 2. Customer Behavior & Market Insights
* **Even Segment Distribution:** Revenue is balanced almost evenly across customer segments:
  * **Education:** **$4.64M (25.70%)**
  * **Government:** **$4.49M (24.91%)**
  * **Business:** **$4.46M (24.71%)**
  * **Individual:** **$4.45M (24.68%)**
* **Demographic Breakdown:** Revenue is consistent across age groups (18–24, 25–34, 35–44, 45–54, 55+), though product preferences vary—Mac and iPhone lead across all demographics while wearables (Apple Watch, AirPods) act as supplementary drivers.

### 3. Sales Strategy & Channel Performance
* **Channel Dominance:** **Carrier Stores** and **Online (Apple.com)** drive the highest sales volume, closely followed by direct **Apple Store** physical locations.
* **Discounting Impact:** Discounting increases total unit volume sold, but exhibits mixed impact on total top-line revenue depending on the product tier.
* **Channel Flow:** Decomposing channel revenue reveals strong B2B and Corporate sales flows into European markets (e.g., Switzerland, Germany, Belgium).

### 4. Product & Ecosystem Insights
* **Hardware Mix:** **Mac** and **iPhone** drive the largest share of overall hardware revenue, followed by **iPad**, **Apple Watch**, **AirPods**, and **Accessories**.
* **Ecosystem Switching:** Analysis of iPhone buyers reveals that while existing iOS upgrades make up the vast majority of purchases, **Android switchers (~5.17%)** represent a steady pipeline of new users entering the Apple ecosystem.

---

##  Strategic Business Recommendations

1. **Optimize Channel Incentives:** Strengthen partnerships with **Carrier Stores** and direct-to-consumer digital channels (**Apple.com**), as they capture the largest revenue volume.
2. **Target Android Switcher Conversions:** Capitalize on the ~5% Android-to-iPhone migration rate with targeted trade-in campaigns and onboarding incentives in high-performing markets like Hong Kong and the Netherlands.
3. **Refine Segment Packaging:** Tailor product bundles specifically for **Education** and **Government** channels (which account for over 50% of revenue combined), offering hardware + software packages to lock in long-term enterprise value.

---

##  Tools & Technologies
* **Power BI Desktop:** Multi-page dashboard development, Decomposition Trees, Donut Charts, Geo-Maps, and interactive slicers.
* **DAX (Data Analysis Expressions):** Calculated KPIs, Average Selling Price (ASP), revenue segmentation, and time-intelligence metrics.
* **SQL:** Initial data extraction, cleaning, and customer segment transformation.

---

##  Repository Structure

── data/                  # SQL scripts & raw datasets (demographics, sales, channels)
── dashboards/            # Power BI (.pbix) report file and interactive exports
── screenshots/           # High-resolution dashboard page screenshots
── README.md              # Project documentation
