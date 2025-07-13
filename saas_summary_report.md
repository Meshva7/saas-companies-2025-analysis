# 📊 SaaS Companies 2025: Data Analysis Summary Report

## 🧭 Executive Summary
This project analyzes a curated list of the top 100 SaaS companies in 2025 using a data-driven approach. With the help of Python and Power BI, the project uncovers growth trends, sector dominance, valuation patterns, and investment insights within the SaaS ecosystem.

## 📁 Dataset Overview
- Source: Kaggle Dataset – *Top 100 SaaS Companies 2025*
- Total records: 100 companies
- Key variables:
  - `Company`, `Year Founded`, `HQ Location`, `Industry`, `Funding($M)`, `ARR ($B)`, `Valuation ($B)`, `Child Company`, `Employees`, `Investors`, `Product`, `G2 Rating`

## 🧹 Data Cleaning (Python)
Performed using `pandas`:
- Removed nulls and duplicates
- Standardized financial fields
- Converted string-based metrics (e.g., "$1.2B", "25%") to numerical values
- Claculate the number of outliers for each numeric column

## 📊 Exploratory Data Analysis
Visualizations using `matplotlib` and `seaborn`:
- Top 10 investors by total funding
- Scatterplots
- Histogram 
- Heatmap: Correlation between numerical metrics

## 📌 Power BI Dashboard
Interactive visuals showing:
- KPI cards
- Top 5 companies by valuation & ARR
- Top 10 industries by valuation
- Pie chart of funding stages by valuation
- Founding Trends of SaaS Companies Over the Years
- Geo Map: HQ Distribution via tool tip
- Most active investors in SAAS
- Matrix Details
- Impact of G2 Ratings on Company Performance

## 📍 Key Insights
1. **Valuation Leaders**: AI, Fintech, and Cloud Infra are the top-valued sectors.
2. **Growth Outliers**: Some companies show >150% growth but are < $1B valuation — early-stage disruptors.
3. **Geographic Trends**: 65% of top SaaS companies are US-based; Silicon Valley leads.
4. **Revenue vs Valuation**: Several companies have high valuations with low revenue, implying future expectations & investor confidence.
5. **Top Performers**: A few outliers (e.g., Company X, Y) are leaders in both revenue and valuation.

## 💼 Business Recommendations
- **Invest in Emerging Sectors**: AI, ML, Fintech and Vertical SaaS have the fastest growth.
- **Focus on Scalable Revenue Models**: Companies with recurring revenue streams tend to have higher valuations even at lower revenue points.
- **Watch Undervalued High-Growth Startups**: Early-stage firms with high YoY growth can offer strong ROI potential.
- **Geographic Focus**: Consider expansion or investments in the US, especially California and New York.

## 🧾 Conclusion
This end-to-end analysis bridges raw data to insights for strategic decision-making in the SaaS domain. It reflects how data analysis and business intelligence tools can unlock value in competitive markets.

---

📌 *Prepared by Meshva Patel*  
LinkedIn: [linkedin.com/in/meshva-patel](https://linkedin.com/in/meshva-patel)  

