# Plant Co. Global Performance & Profitability Analysis

## 📊 Project Overview
This Business Intelligence project provides a deep-dive analysis of "Plant Co.," a global distributor. The goal was to move beyond static reporting and create a dynamic diagnostic tool that identifies **where** revenue is leaking and **which** products are driving sustainable growth.

The final solution tracks **$13.00M in Sales**, **$5.15M in Gross Profit**, and over **555K units** sold, with full Year-over-Year (YoY) comparative capabilities.

### 🔗 https://app.powerbi.com/groups/me/reports/38cce928-5b00-4581-b8b2-e30e524a5363/2c6676f9bcc9aa0591d1?experience=power-bi

---

## 🚀 Key Business Insights

### 1. Performance Variance (YTD vs. PYTD)
* **Sales Trend:** Despite a total sales volume of $13.00M, the company saw a **$512K decline** compared to the previous year.
* **Monthly Volatility:** Using the Waterfall analysis, we identified that **February** and **April** were the primary drivers of this decline, whereas **June** showed a significant recovery spike.
* **Quantity vs. Value:** Interestingly, while Sales and Profit were down, **Quantity sold increased by 17.05K units**, suggesting a decrease in average unit price or a shift toward lower-margin products.

### 2. Profitability & Account Segmentation
* **The GP% Sweet Spot:** The majority of accounts maintain a healthy **39.62% Gross Profit margin**.
* **Diagnostic Scatter Plot:** By plotting GP% against Quantity, I identified several "High Volume, Low Margin" accounts. These represent a strategic risk where the cost of service may be outweighing the profit generated.
* **Regional Laggards:** **China** and **France** were identified as the bottom-performing countries in terms of YTD vs. PYTD variance, requiring immediate regional sales intervention.

---

## 🛠️ Technical Stack & Features

* **Power BI / DAX:** * Developed complex Time Intelligence measures (YTD, PYTD, YoY Variance).
    * Implemented dynamic "Metric Switching" using parameters to toggle between Sales, Quantity, and Gross Profit across the entire report.
* **Data Modeling:** * Star Schema architecture with centralized Fact tables and optimized Dimension tables (Calendar, Product, Geography).
* **Advanced Visualizations:**
    * **Waterfall Charts:** Used to visualize the "bridge" between last year's performance and this year's.
    * **Treemaps:** Utilized for "Bottom 10" analysis to quickly highlight underperforming regions.
    * **Scatter Plots:** Implemented for multi-dimensional profitability segmentation.

---

## 📈 Dashboard Architecture

| Feature | Description |
| :--- | :--- |
| **Executive Summary** | High-level KPIs for Sales, Quantity, GP, and GP%. |
| **Waterfall Analysis** | Monthly breakdown of performance gains and losses. |
| **Product Segmentation** | Breakdown by Product Type (Indoor, Landscape, Outdoor). |
| **Geographic Analysis** | Treemap identifying the bottom 10 countries by performance variance. |

---

## 💡 Recommendations
1.  **Price Optimization:** Investigate the "Quantity Up / Sales Down" paradox in China to determine if aggressive discounting is eroding the bottom line.
2.  **Product Shift:** Focus marketing efforts on the **Landscape** category, which showed the most resilience during low-performing months.
3.  **Operational Review:** Review the supply chain costs for the bottom-performing accounts identified in the scatter plot to improve overall GP%.

---

## 📂 How to Use
1. Clone this repository.
2. Open the `.pbix` file in **Power BI Desktop**.
3. Use the **Year Slider** and **Metric Slicer** to explore different performance years and data types.

---
**Author:** [Your Name]  
**Tools:** Power BI, DAX, Power Query, Excel
