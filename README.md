# 📊 Marketing Analytics — SQL, Python & Power BI

> **End-to-end marketing analytics project transforming customer, engagement, conversion and review data into actionable business insights.**

This project demonstrates a complete analytics workflow using **SQL, Python and Power BI**, from data preparation and customer-review enrichment to analytical modeling, interactive visualization and executive-level recommendations.

The final analysis evaluates **2025 marketing performance**, focusing on conversion efficiency, product performance, social-media engagement and customer experience.

---

## 🎯 Business Objective

The objective was to answer key marketing and customer-experience questions:

* How did conversion performance evolve during 2025?
* Which products generated the strongest conversion rates?
* How did marketing reach and engagement change compared with 2024?
* What does customer feedback reveal about satisfaction?
* Which areas should marketing teams prioritize for 2026?

The project was designed to move beyond descriptive reporting and translate the data into **business actions and priorities**.

---

## 🔄 Analytics Workflow

```text
Raw Marketing Data
        ↓
SQL Data Preparation
        ↓
Python Review Enrichment
        ↓
Analytical Dataset
        ↓
Power BI Data Model
        ↓
Interactive Dashboards
        ↓
2025 Performance Analysis
        ↓
Business Recommendations
```

### 1. SQL — Data Preparation & Transformation

SQL was used to prepare the analytical datasets and structure the data for reporting.

Key activities included:

* Data cleaning and preparation
* Customer and product data transformation
* Fact and dimension preparation
* Data enrichment through joins
* Aggregations required for marketing KPIs
* Preparation of datasets for Power BI

**File:** `MarketingData-Preparation.sql`

---

### 2. Python — Customer Review Enrichment

Python was used to enrich customer-review data with sentiment information.

The notebook performs review processing and creates an enriched dataset that can be analyzed alongside customer experience metrics.

**Files:**

* `customer_reviews_enrichment.ipynb`
* `customer_reviews_with_sentiment.csv`

This layer connects quantitative performance indicators with qualitative customer feedback.

---

### 3. Power BI — Data Modeling & Visualization

Power BI was used to transform the prepared datasets into an interactive marketing analytics dashboard.

The dashboard focuses on four major analytical areas:

* **Executive Performance**
* **Conversion Performance**
* **Product Performance**
* **Social Engagement**
* **Customer Feedback & Sentiment**

**File:** `MarketingAnalyticsDashboard.pbix`

---

# 📈 2025 Performance Results

## Executive Overview

2025 maintained relatively stable conversion performance despite a significant reduction in marketing reach.

| KPI             |         2025 |   YoY Change |
| --------------- | -----------: | -----------: |
| Conversion Rate |    **8.55%** | **+0.07 pp** |
| Views           |    **1.10M** |   **-63.2%** |
| Clicks          |    **67.6K** |   **-85.2%** |
| Average Rating  | **3.66 / 5** |    **-0.01** |

The key signal is that **conversion remained resilient while traffic contracted sharply**.

This suggests that the remaining audience continued to convert at a broadly similar annual rate, while the major weakness was the ability to generate and maintain reach.

---

## 📊 Conversion Performance

Annual conversion reached **8.55%**, compared with **8.48% in 2024**.

Monthly performance was highly seasonal:

* **September:** 15.15% — strongest month
* **July:** 2.94% — weakest month
* **December:** 12.82% — strong year-end recovery

March and September represented clear conversion peaks, while July highlighted a significant mid-year performance gap.

### Business implication

The priority is to identify what drove the strongest months and replicate those conditions during weaker periods.

---

## 🏆 Product Performance

A small group of products generated substantially higher conversion rates:

| Product        | Conversion |
| -------------- | ---------: |
| Hockey Stick   |  **20.8%** |
| Climbing Rope  |  **20.0%** |
| Surfboard      |  **18.9%** |
| Cycling Helmet |  **18.2%** |
| Baseball Glove |  **11.5%** |
| Dumbbells      |   **9.4%** |

These products represent potential candidates for:

* Paid campaign prioritization
* Seasonal promotions
* Merchandising
* Product-level experimentation

The analysis recommends testing whether the success of these high-converting products can be replicated across weaker-performing products.

---

## 📱 Social Engagement

Marketing reach contracted substantially during 2025.

| Metric       |          2025 |                YoY |
| ------------ | ------------: | -----------------: |
| Views        | **1,096,704** |         **-63.2%** |
| Clicks       |    **67,632** |         **-85.2%** |
| Likes        |     **4,342** |         **-94.1%** |
| Click / View |     **6.17%** |     15.37% in 2024 |

Monthly views declined from approximately **168K in January to 46K in September**, followed by a modest Q4 recovery.

The analysis therefore identifies **reach recovery and content-to-action efficiency** as major priorities.

---

## ⭐ Customer Feedback & Sentiment

Customer feedback remained generally positive, but the results indicate room for improvement.

### Rating

**Average rating: 3.66 / 5**

The target identified in the analysis is to move toward **4.0+**.

### Review distribution

* **5 stars:** 138
* **4 stars:** 154
* **3 stars:** 98
* **2 stars:** 60
* **1 star:** 27

### Sentiment

* Positive: **292**
* Negative: **81**
* Mixed Negative: **56**
* Mixed Positive: **41**
* Neutral: **7**

The analysis combines quantitative ratings with sentiment classification to identify customer-experience improvement opportunities.

---

# 💡 Key Business Recommendations

## 1. Rebuild Marketing Reach

* Diagnose the sustained decline in monthly views.
* Refresh content formats and distribution cadence.
* Strengthen calls-to-action and audience targeting.
* Use the Q4 recovery as a base for scaling.

## 2. Scale Conversion

* Replicate tactics from high-performing months such as March, September and December.
* Prioritize high-converting products such as Hockey Stick, Climbing Rope and Surfboard.
* Use seasonal offers around proven demand periods.
* Monitor product-level conversion regularly.

## 3. Improve Customer Experience

* Move the average rating from **3.66 toward 4.0+**.
* Investigate recurring negative and mixed-review themes.
* Track rating movement by product and month.

---

# 🛠️ Technology Stack

| Area               | Technology          |
| ------------------ | ------------------- |
| Data Preparation   | **SQL Server**      |
| Data Analysis      | **Python / Pandas** |
| Sentiment Analysis | **Python**          |
| Data Modeling      | **Power BI**        |
| Visualization      | **Power BI**        |
| Business Analysis  | **SQL + Power BI**  |
| Reporting          | **PowerPoint**      |

---

# 📁 Repository Structure

```text
Marketing-Analytics-Project-SQL-Python-PowerBI/
│
├── MarketingAnalyticsDashboard.pbix
├── MarketingData-Preparation.sql
├── customer_reviews_enrichment.ipynb
├── customer_reviews_with_sentiment.csv
├── images/
│   ├── Overview.png
│   ├── Conversion Details.png
│   ├── Social Media Details.png
│   └── Customer Reviews Details.png
│
├── Marketing_Analytics_2025_Presentation.pptx
└── README.md
```

---

# 📊 Dashboard & Presentation

The project includes an interactive **Power BI dashboard** and a dedicated **2025 Performance Review presentation** designed to communicate the findings to business stakeholders.

The presentation summarizes the transition from raw marketing data to performance insights, key findings and recommended 2026 actions.

---

# 🎓 Skills Demonstrated

This project demonstrates practical experience in:

* SQL data preparation
* Relational data analysis
* Data transformation
* Python / Pandas / NLTK
* Customer-review enrichment
* Sentiment analysis
* Power BI data modeling
* KPI development
* Interactive dashboard design
* Marketing funnel analysis
* Conversion analysis
* Product performance analysis
* Customer experience analytics
* Business storytelling
* Executive reporting
* Translating data into actionable recommendations

---

## 👤 Author

**Karima LACHHEB**

