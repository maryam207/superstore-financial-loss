# Superstore Financial Loss & Profitability Analysis Dashboard

An interactive Business Intelligence dashboard built in **Looker Studio** to analyze financial performance, uncover the root causes of profit losses, and evaluate discount impact using the global Superstore dataset.

---

## 📊 Project Overview
In many retail businesses, high sales volumes can mask underlying profit drains. This project focuses on a deep-dive financial analysis of the Superstore dataset to identify loss-making categories, sub-categories, and the exact tipping points where discounts turn profitable sales into severe financial loss.

---

## 🎯 Key Metrics & KPIs
The dashboard tracks 5 core financial KPIs designed using robust aggregations:
* **Total Sales**: Overall revenue generated.
* **Total Profit / Loss**: Net financial return.
* **Profit Margin**: Efficiency of profit generation relative to sales.
* **Total Orders**: Volume of transactions processed.
* **Average Discount**: Mean discount rate applied across orders.

---

## 🔍 Key Insights & Findings
1. **The Discount Tipping Point**: Analysis reveals that discounts exceeding **3%** heavily correlate with negative returns, with aggressive discounting (30% to 60%+) driving the heaviest financial losses.
2. **Category Performance Bottlenecks**: While *Technology* leads in strong margins, specific *Furniture* and *Office Supplies* sub-categories suffer from chronic negative returns due to high discounting practices.
3. **Ascending Loss Tracking**: Implemented specialized calculated sorting logic (`Profit * -1`) to ensure loss-making items consistently appear at the top of analytical tables without distorting the true positive/negative monetary values displayed.

---

## 🛠️ Tools & Technologies Used
* **Data Visualization & BI**: Looker Studio
* **Data Preparation & Manipulation**: SQL / Spreadsheets
* **Design System**: Modern corporate UI layout (Structured 3-Tier hierarchy, conditional formatting for instant loss identification in red, and a cohesive blue/gray palette).

---

## 🔗 Live Interactive Dashboard
You can explore and interact with the live Looker Studio dashboard here:
👉 (https://datastudio.google.com/s/hyESkPveKdo)
---

## 📁 Repository Contents
* `Superstore_Project_Overview.pdf` — Summary report and visual breakdown.
* Screenshots of the active Looker Studio layout.
