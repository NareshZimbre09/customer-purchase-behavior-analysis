# Customer Purchase Behaviour Analysis
## Using Exploratory Data Analytics and Visualisation Techniques

**MCA Semester IV Major Project | Chandigarh University, CDOE | Session: 2024–2026**

---

## Project Overview
This project analyses customer purchase behaviour using Exploratory Data Analysis (EDA) 
on the Online Retail II dataset (UCI ML Repository). The pipeline identifies buying 
patterns, seasonal trends, RFM customer segments, and business insights from 
541,910 real-world retail transactions.

---

## Key Findings
- Total Revenue: £8,887,226.89 across 4,338 customers
- Champions (29.2% of customers) generate 76.8% of total revenue
- November is peak sales month — holiday season drives 2x average revenue
- UK accounts for 88.9% of all transactions
- 4 customer segments identified: Champion, Loyal, At-Risk, Lost

---

## Dataset
- **Source:** UCI Machine Learning Repository
- **URL:** https://archive.ics.uci.edu/dataset/502/online+retail+ii
- **Records:** 541,910 raw → 392,693 clean
- **Period:** December 2009 – December 2011

---

## Tools & Technologies
| Tool | Purpose |
|------|---------|
| Python 3.13 | Primary programming language |
| pandas | Data cleaning and analysis |
| matplotlib | Chart generation |
| seaborn | Heatmap visualization |
| Jupyter Notebook | Development environment |
| Anaconda | Package management |

---

## Project Structure

CustomerPurchaseProject/
├── notebooks/
│   └── customer_purchase_analysis.ipynb
├── visuals/
│   ├── chart1_top_products.png
│   ├── chart2_top_customers.png
│   ├── chart3_sales_by_country.png
│   ├── chart4_monthly_sales.png
│   ├── chart5_orders_by_day.png
│   ├── chart6_order_distribution.png
│   ├── chart7_rfm_segments.png
│   ├── chart8_heatmap.png
│   ├── chart9_scatter.png
│   └── chart10_segment_revenue.png

---

## How to Run
1. Install Anaconda from https://anaconda.com/download
2. Download the dataset from the UCI URL above
3. Place dataset in the `data/` folder
4. Open Jupyter Notebook and run `customer_purchase_analysis.ipynb`
5. All charts will be saved automatically to the `visuals/` folder

---

## RFM Segmentation Results
| Segment | Customers | Revenue | % of Revenue |
|---------|-----------|---------|-------------|
| Champion | 1,267 | £6,827,254 | 76.8% |
| Loyal | 1,276 | £1,369,352 | 15.4% |
| At-Risk | 989 | £512,070 | 5.8% |
| Lost | 806 | £178,551 | 2.0% |

---

## Student Details
- **Student Name:** Naresh Ambadas Zimbre
- **Enrollment No:** O24MCA111043
- **University:** Chandigarh University, CDOE
- **Programme:** Master of Computer Applications (MCA) Semester IV
- **Session:** 2024–2026
