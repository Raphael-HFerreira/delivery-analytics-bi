# Business Intelligence Dashboard: Complete Project Analysis

## Context & Business

Project developed and led for a **major food delivery platform** (direct competitor to iFood), where I served as **Project Leader** in the conception and development of a strategic BI system. The organization faced opacity in business health indicators and struggled to make data-driven decisions on retention, revenue, and customer segmentation.

---

## Business Challenge

The company needed to consolidate 7 years of history (2018-2025) into a 360-degree view covering:

**Financial visibility:** Track R$ 558.60M in revenue in a segmented and temporal manner

**Critical retention:** Identify patterns in 1,143 monthly cancellations representing R$ 1.90M in lost revenue

**Customer intelligence:** Understand 1,728 active subscriptions by profile, category, location, and customer lifetime

**Health diagnosis:** Evaluate payment compliance, sales volume, NPS perception, and actual churn reasons

---

## Solution Developed

Architecture of **4 integrated analytical tabs** in a single Power BI dashboard:

### 1. Overview (Executive Layer)
- **Highlighted KPIs:** Revenue (R$ 5.39M), Churn Revenue (R$ 1.90M), Subscription Volume (1,728), Churn Rate (66.15%)
- **Temporal overlay series (2018-2025):** Evolution of subscriptions vs churn to detect critical periods
- **Category composition by revenue (treemap):** Pizzeria leads with 26% of revenue
- **Payment compliance (donut):** 89.35% of customers current on payments (R$ 1.54M healthy business)
- **Stacked waterfall:** Annual dynamics of active, blocked, and canceled subscriptions

### 2. Revenue (Economic Analysis)
- **Annual Recurring Revenue (ARR):** R$ 122.26M with 1,728 subscriptions
- **Average ticket by category:** Pizzeria and Cafeteria tied at R$ 36M
- **Gross revenue series (2020-2026):** Seasonal peak detection (May 2020 = R$ 0.5M)
- **Net new subscriptions per year:** Growth from 59 (2018) to 121 (2024) = +105%
- **Revenue by category (horizontal bar):** Distribution across 10 segments (Pizzeria R$ 145M to Sorveteria R$ 2.30M)

### 3. Churn (Retention Analysis)
- **Monthly Recurring Revenue Lost (MRRLost):** Time series 2020-2024 with diagnostic peaks
- **Churn count:** 1,143 cancellations growing from 6 (2020) to 310 (2024)
- **Tenure before churn:** 37.21% over 1 year, 24.28% between 6-12 months (segmentation for proactive retention)
- **Churn by category:** Restaurants (140) lead; Cafeteria (4) lowest churn
- **Churn reason breakdown:** Qualitative insights directing retention strategy
  * "Didn't produce results" (141 cases) = revalidate partnership model
  * "I'm closing" (100 cases) = macro/external factors
  * "Need to reduce costs" (97 cases) = repricing opportunity
- **Average days before churn:** 452.70 days = 15-month window for intervention

### 4. Customer Profile (Segmentation & Behavior)
- **Total customer revenue:** R$ 558.60M consolidated
- **Sales volume over time (series):** Peak 49K in 2019, stabilization at 8K in 2024
- **Average ticket by category:** Pizzeria R$ 36M, followed by Cafeteria and Varied
- **Rating score (NPS proxy):** 80.53% unrated (gap to explore), 18.81% rated 5
- **TOP 10 cities:** Manaus leads (298), Belo Horizonte (147), São Paulo (39)
- **Rating justification:** 4,034 customers "no response" vs 148 "excellent service" (survey opportunity)

---

## Generated Discoveries & Insights

### Insight 1: Churn Pattern by Lifecycle
**Finding:** 37.21% of churners had 1+ year tenure; 24.28% between 6-12 months. This suggests customers don't exit early but abandon after establishment attempts.

**Action:** Health-check program at months 3, 6, and 12 to intervene before point of no return.

---

### Insight 2: Economic Seasonality
**Finding:** Gross revenue peaked at R$ 0.5M in May 2020, with gradual decline post-2021. MRR Lost oscillates 2-10M with 2022 spike.

**Action:** Quarterly retention campaign planning aligned with historical decline periods.

---

### Insight 3: Category Concentration
**Finding:** Pizzeria dominates at 26% (R$ 145M). Restaurants generate 12% of churn (140 cases), disproportionate to revenue.

**Action:** Customized product for restaurants with adapted revenue model.

---

### Insight 4: Geographic-Economic Distribution
**Finding:** Manaus (298 top city), Belo Horizonte (147), and São Paulo (39) concentrate business. Presence across 15 distinct segments.

**Action:** Regional go-to-market strategy; vertical expansion in low-penetration cities.

---

### Insight 5: Healthy Payment Compliance
**Finding:** 89.35% of customers current on payments (R$ 1.54M); only 10.65% delinquent. Robust credit model.

**Action:** Foundation for aggressive commercial strategy; low credit risk.

---

## Measured Impact

### Financial
- R$ 1.90M churn traceability = ability to prioritize retention by ROI
- Identification of seasonal MRRLost peaks = cash flow planning 15 months ahead
- R$ 122.26M ARR with confident projections

### Operational
- 1,143 cancellations diagnosis with structured reasons = data-driven product roadmap
- Category + geographic segmentation = 50+ personas for targeted go-to-market
- Insight time reduction (3 weeks in SQL ad-hoc to 2 clicks in Power BI)

### Strategic
- ARR (R$ 122.26M) and average ticket (R$ 176.52) visibility = confident growth projections
- Health monitoring (compliance, NPS, churn) = KPIs CEOs use today for strategic decisions
- Dashboard in production with monthly updates

### Legacy
- Dashboard used by company CEOs today for strategic decisions
- Proven impact on resource allocation and initiative prioritization
- Foundation for future BI program evolution

---

## Technical Architecture

### Tools & Stack
- **Power BI Desktop** with optimized tabular model
- **Data sources:** Multiple consolidated sources (SQL, CRM, financial)
- **DAX:** Complex calculations (MRRLost, weighted churn rate, category-level average ticket)
- **Dynamic filters:** Date, Category, State, Establishment (granular drill-down)

### Data Modeling
- **Fact tables:** Subscriptions, Churn, Sales, NPS
- **Dimensions:** Time (7 years), Category (10 types), Location (15 segments), Customer
- **Relationships:** Star schema for performance
- **Granularity:** Customer-Transaction-Month for maximum flexibility

### Validation & Quality
- Reconciliation with audited financial data
- Complete history 2018-2025 (7 years consistency)
- Monthly updates with 48-hour SLA

---

## Demonstrated Competencies

### Hard Skills (Technical)

✓ **Power BI (Advanced):** 4 integrated tabs, 20+ visualizations, dynamic filters, bookmarks  
✓ **DAX (Intermediate/Advanced):** MRRLost, Churn Rate, weighted Average Ticket calculations  
✓ **SQL (Intermediate):** Consolidation of 7 years across multiple tables (JOINs, GROUP BY, Window Functions)  
✓ **Data Modeling:** Snowflake schema, correct 1:N relationships, appropriate granularity  
✓ **Data Visualization:** Visualization selection for maximum insight (time series, treemap, waterfall, donut)  

### Soft Skills (Analytical)

✓ **Business Analysis:** Translation of business problems into analytical solutions  
✓ **Project Leadership:** End-to-end project execution; C-level stakeholder coordination  
✓ **Storytelling:** Narrative converting data into executive decisions  
✓ **SaaS Expertise:** Deep knowledge of ARR, MRRLost, Churn Rate, Customer Lifetime Value  
✓ **Critical Thinking:** Decomposition of churn across multiple dimensions (reason, category, lifetime)  

### Methodology

✓ **Lean Six Sigma Green Belt:** Implicit DMAIC (Define → Measure → Analyze → Improve → Control)  
✓ **Data-Driven Decision Making:** Every action supported by structured insights  
✓ **Continuous Improvement:** Dashboard in constant refinement with user feedback  

---

## Why This Project is Relevant

This dashboard exemplifies work any B2B SaaS, marketplace, or subscription company needs:

1. **Real scale:** Not simulated. 7 years, R$ 558M, 1,728 active customers.
2. **C-level impact:** CEOs use it today. Not an archived project.
3. **Multidimensional:** Finance, operations, product, retention in single source of truth.
4. **Scientific method:** Each insight has causal diagnosis and action plan.
5. **Transferable:** Structure applicable to any subscription or marketplace model.

---

## Applicability for Cork & Dublin Positions

For **Data Analyst** or **BI Analyst** roles:
- Demonstrates ability to consolidate complex data into actionable insights
- Shows fluency in modern stack (Power BI, DAX, SQL)
- Evidences understanding of SaaS/marketplace business models

For **Analytics Engineer** roles:
- Robust, well-structured data modeling
- Reliable data pipelines (7 years with 48-hour SLA)
- Performance and scalability focus

For **Senior Analyst** roles:
- Project leadership from conception
- Stakeholder management (C-level)
- Data-to-strategy transformation

---

**Developed by:** Rapha Dantas  
**Date:** July 2026  
**Status:** In production, used by CEOs for strategic decisions
