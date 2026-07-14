# NovaMed Solutions Sales Performance Dashboard

A comprehensive Power BI dashboard developed to analyze pharmaceutical sales performance, customer demographics, product profitability, and regional revenue distribution, enabling NovaMed Solutions to make informed strategic and operational decisions.

---

## ⚙️ Project Type

- ✅ Dashboard / Data Visualization
- ✅ Exploratory Data Analysis (EDA)
- ✅ Business Intelligence
- ✅ Data Cleaning & Transformation
- ✅ End-to-End Analytics Project

---

# Table of Contents

1. Project Overview
2. Objectives
3. Project Scope & Tools
4. Repository Structure
5. Data Workflow
6. Analysis & Metrics
7. Key Insights
8. Recommendations
9. Assumptions & Limitations
10. Future Enhancements
11. Deliverables
12. Author

---

# 1. Project Overview

## Context

NovaMed Solutions is a healthcare organization that distributes pharmaceutical products across multiple international markets. As sales volumes increased, management required an integrated reporting solution capable of monitoring revenue, profitability, customer behavior, drug performance, and regional sales performance from a single interactive dashboard. 

## Problem Statement

The business lacked a centralized reporting system capable of answering critical questions regarding monthly sales trends, customer demographics, product performance, regional revenue distribution, and profitability. Leadership needed actionable insights to optimize product strategy, customer acquisition, and regional expansion while maintaining strong financial performance.

## Approach

Operational sales data was cleaned, transformed, and modeled in Power BI. Interactive dashboards were designed using KPIs, slicers, charts, maps, and drill-down capabilities to analyze sales, customer demographics, geographical performance, and product profitability.

## Outcome

An executive Power BI dashboard providing a centralized view of company performance across products, customers, regions, and sales trends, enabling faster and more informed business decisions.

---

# 2. Objectives

### Primary Objective

Develop an interactive Power BI dashboard that provides a comprehensive view of NovaMed Solutions' sales performance and customer analytics.

### Secondary Objectives

- Monitor monthly revenue and profit trends.
- Identify top-performing and underperforming pharmaceutical products.
- Analyze customer purchasing behavior.
- Evaluate geographical sales performance.
- Understand customer demographics.
- Support strategic sales and marketing decisions.

---

# 3. Project Scope & Tools

## Scope

| Dimension | Details |
|------------|---------|
| **In Scope** | Revenue analysis, profit analysis, customer performance, product performance, demographics, geographical analysis, monthly trends |
| **Out of Scope** | Predictive forecasting, supply chain optimization, inventory management, clinical analysis |
| **Time Period** | Business dataset supplied for the project |
| **Granularity** | Transaction-level pharmaceutical sales records aggregated into KPIs |

---

## Tools & Technologies

| Category | Tool |
|------------|------|
| Data Source | Excel / CSV |
| Data Cleaning | Power Query |
| Data Modeling | Power BI |
| Analysis | DAX Measures |
| Visualization | Power BI |
| Version Control | Git & GitHub |
| Documentation | Markdown |

---

# 4. Repository Structure

```
NovaMed-Sales-Dashboard/

│

├── data/
│   ├── raw/
│   └── cleaned/

├── dashboard/
│   └── NovaMed Dashboard.pbix

├── visuals/
│   ├── Dashboard 1.png
│   ├── Dashboard 2.png
│   ├── Monthly Trends.png
│   ├── Product Performance.png
│   ├── Customer Analysis.png
│   └── Geographic Analysis.png

├── presentation/
│   └── NovaMed Presentation.pdf

└── README.md
```

---

# 5. Data Workflow

```
Business Dataset
        ↓
Power Query Cleaning
        ↓
Data Transformation
        ↓
Power BI Data Model
        ↓
DAX Measures & KPIs
        ↓
Interactive Dashboard
        ↓
Business Insights & Recommendations
```

### Source

Operational pharmaceutical sales data containing customer, product, sales, revenue, and geographical information.

### Ingestion

Imported into Power BI through Power Query.

### Cleaning

- Removed duplicate records
- Standardized data formats
- Corrected missing values
- Validated customer attributes
- Created calculated fields

### Transformation

Created business KPIs including:

- Revenue
- Profit
- Profit Margin
- Quantity Sold
- Average Revenue per Customer
- Customer Contribution
- Country Revenue
- Product Ranking

### Analysis

Business performance was analyzed using:

- Trend analysis
- Customer segmentation
- Product ranking
- Geographic analysis
- Profitability analysis
- KPI monitoring

### Output

Interactive Power BI dashboard and executive presentation.

---

# 6. Analysis & Metrics

## Analytical Approach

The dashboard was designed to evaluate NovaMed's overall commercial performance by examining product profitability, customer behavior, regional performance, and sales trends using interactive business intelligence techniques.

---

## Key Metrics

| Metric | Definition | Business Value |
|---------|------------|----------------|
| Revenue | Total sales generated | Measures business growth |
| Profit | Revenue after costs | Measures financial success |
| Profit Margin | Percentage profit earned | Evaluates operational efficiency |
| Quantity Sold | Total drug units sold | Measures sales volume |
| Average Revenue per Customer | Revenue generated per customer | Evaluates customer value |
| Country Revenue | Revenue generated by each country | Identifies strongest markets |
| Product Profitability | Profit generated by each drug | Supports product strategy |
| Customer Contribution | Revenue contribution by customer groups | Guides customer retention |

---

## Methods Used

- KPI Analysis
- Trend Analysis
- Customer Segmentation
- Product Ranking
- Geographic Analysis
- Comparative Analysis
- Interactive Filtering
- DAX Calculations

---

# 7. Key Insights

## 1. Revenue and Profit Remain Highly Stable

Revenue and profit move together consistently throughout the year, indicating a predictable cost structure. Revenue peaks in January before experiencing bi-monthly fluctuations, with another strong period beginning in July and remaining stable through year-end. :contentReference[oaicite:2]{index=2}

---

## 2. Top Drugs Drive Company Revenue

Doxycycline, Ergocalciferol, and Lisinopril generated approximately **$3.5 million** each, making them the strongest-performing products. Conversely, Warfarin, Montelukast, Amoxicillin, Prednisone, and Metformin underperformed significantly and warrant further investigation. :contentReference[oaicite:3]{index=3}

---

## 3. Preferred Customers Generate the Highest Revenue

Preferred Customers contributed approximately **$23 million**, outperforming New Customers and Frequent Buyers. However, over 80% of buyers belong to the Seller category, indicating an opportunity to diversify the customer base and strengthen User engagement. :contentReference[oaicite:4]{index=4}

---

## 4. Canada Dominates Regional Revenue

Canada generated **$32 million** in revenue—more than double any other country—followed by Australia at **$15 million**. This highlights both the strength of these markets and the company's reliance on only a few regions for growth. :contentReference[oaicite:5]{index=5}

---

## 5. Customer Demographics Reveal Distinct Spending Patterns

Although the average customer age is approximately 50 years, the highest-spending customers differ by region. Customers aged **18–24** generate the most revenue in the UK and Germany, while **25–34-year-olds** dominate spending in Australia. Older age groups contribute most revenue across several other countries. :contentReference[oaicite:6]{index=6}

---

## 6. Strong Financial Performance with Growth Opportunities

NovaMed maintains an exceptionally high profit margin, diversified top-performing products, high average revenue per customer, and a loyal customer base. However, dependence on seasonal peaks, Canada, and Australia introduces business risk that can be mitigated through regional expansion and new customer acquisition. :contentReference[oaicite:7]{index=7}

---

# 8. Recommendations

| Priority | Recommendation | Based On | Suggested Owner |
|----------|---------------|----------|-----------------|
| High | Increase inventory levels for top-performing drugs during peak sales periods | Product Performance | Operations |
| High | Expand sales and marketing efforts in Europe and the United States | Geographic Analysis | Sales |
| High | Develop strategies to convert New Customers and Frequent Buyers into Preferred Customers | Customer Analysis | Marketing |
| High | Reduce dependence on Canada by strengthening lower-performing regions | Country Performance | Executive Team |
| Medium | Investigate demand and pricing for underperforming drugs | Product Analysis | Product Management |
| Medium | Launch age-targeted marketing campaigns based on regional demographics | Customer Demographics | Marketing |
| Medium | Implement promotions to reduce seasonal sales fluctuations | Monthly Trends | Sales |
| Low | Improve customer acquisition strategies to reduce reliance on repeat buyers | Customer Growth | Marketing |

---

# 9. Assumptions & Limitations

## Assumptions

- Sales data accurately reflects business operations.
- Customer demographic information is complete.
- Revenue and cost calculations are accurate.
- Product sales records are free from major reporting errors.

## Limitations

- Analysis is limited to the available dataset.
- External economic and healthcare policy changes were not considered.
- Inventory management was outside project scope.
- Forecasting and predictive analytics were not included.
- Customer satisfaction metrics were unavailable.

---

# 10. Future Enhancements

- Integrate live ERP and CRM systems.
- Develop sales forecasting models.
- Build inventory optimization dashboards.
- Add customer lifetime value analysis.
- Include market basket analysis for cross-selling opportunities.
- Publish dashboards through Power BI Service with scheduled refresh.

---

# 11. Deliverables

| Deliverable | Description |
|-------------|-------------|
| Power BI Dashboard | Interactive executive dashboard |
| Power BI File (.pbix) | Complete Power BI solution |
| Business Presentation | Executive presentation summarizing findings |
| README | Project documentation |
| Dashboard Screenshots | Portfolio visuals |

---

# 12. Author

## Ini Tom

**Aspiring Data Scientist | Business Intelligence Analyst | Data Analyst**

- 🔗 LinkedIn: *(Add your LinkedIn profile)*
- 💼 GitHub: *(Add your GitHub profile)*
- 🌐 Portfolio: *(Optional)*

---

## Business Impact

This Power BI project transformed pharmaceutical sales data into a comprehensive business intelligence solution that enables NovaMed Solutions to monitor revenue, profitability, customer behavior, regional performance, and product success. The dashboard provides executives with actionable insights to improve marketing effectiveness, optimize product strategy, diversify regional revenue, and support sustainable business growth. :contentReference[oaicite:8]{index=8}
