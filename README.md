# Employee Satisfaction & Workplace Analysis.
Analyzed HR survey data to identify key drivers of employee satisfaction, burnout risk and workplace fairness across Nordic countries, and built an interactive Power BI dashboard to support data-driven HR decision-making.

## Table of Contents
1. [Project Overview](#1-project-overview)
2. [Objectives](#2-objectives)
3. [Executive Summary](#3-executive-Summary)
4. [Tools & Technologies](#4-tools--technologies)
5. [Repository Structure](#5-repository-structure)
6. [Data Workflow](#6-data-workflow)
7. [Key Metrics](#7-key-metrics)
8. [Key Insights](#8-key-insights)
9. [Recommendations](#9-recommendations)
10. [Assumptions & Limitations](#10-assumptions--limitations)
11. [Author](#11-author)

## 1. Project Overview
Organizations often struggle to understand what truly drives employee satisfaction and where risks like burnout or disengagement are emerging. This project explores HR survey data to uncover patterns in employee wellbeing, performance, and career progression across departments and regions.

The dataset was sourced from Kaggle and extended with Nordic country data to create a more realistic and regionally relevant analysis. The focus was on identifying key drivers such as work-life balance, overtime, compensation, and promotion patterns, and understanding how these factors vary across roles and locations.

The final output is a 4-page interactive Power BI dashboard that enables HR teams to monitor employee experience, detect risk areas early, and make more informed workforce decisions.

## 2. Objectives
- Identify the key drivers of employee satisfaction and burnout risk.
- Analyze the impact of overtime on work-life and employee wellbeing.
- Evaluate promotion patterns and fairness across departments and genders.
- Compare workforce trends across Nordic countries.

## 3. Executive Summary

<img width="2250" height="1255" alt="1" src="https://github.com/user-attachments/assets/292a16c7-88b5-4963-8376-e008a9422c9f" />

- The data provides a high-level view of employee satisfaction, engagement, and burnout risk across departments and Nordic countries. Overall engagement is stable (3.1), with a relatively low but meaningful burnout rate of 19.2%, indicating that while most employees are doing well, there is a notable at-risk group that requires attention.
  
- Burnout risk is not evenly distributed. While 80.8% of employees fall into the low-risk category, a smaller segment (approximately 4%) is classified as high-risk, which can have a disproportionate impact on productivity and retention if not addressed early.
  
- Department-level analysis shows that engagement scores are relatively consistent across teams, but headcount differences highlight where HR efforts may have the greatest impact.
  
- On Country level comparisons reveal slight variations in burnout risk, suggesting that local workplace conditions may influence employee wellbeing.

Overall, the dashboard enables HR teams to quickly identify risk areas, compare regions, and take proactive action to improve employee experience.



## 4. Tools & Technologies

| Category        | Tools Used                       |
| --------------- | ---------------------------------- |
| Data Storage    | CSV files (Kaggle dataset)         |
| Data Processing | Power BI (Power Query)             |
| Analysis        | Power BI (DAX) |
| Visualization   | Power BI                           |
| Version Control | Git / GitHub                       |
| Documentation   | Markdown                           |


## 5. Repository Structure

```
Employee Satisfaction & Workplace Analysis/
│
├── data/
│   ├── raw/
│   ├── processed/
│
├── visuals/
│   └── dashboard screenshots/
│
├── pbix/
│   └── Industry Financials Dashboard.pbix
│   
└── README.md

```

## 6. Data Workflow

```
Source
- HR employee dataset from Kaggle, extended with Nordic country data.
        ↓
Ingestion
- Imported into Power BI using Power Query.
        ↓
Cleaning
- Handled missing values
- Standardized categorical variables
- Ensured consistency across added country data
        ↓
Transformation
- Created calculated metrics (burnout categories, engagement index)
- Grouped variables (training hours, salary ranges)
- Structured data for multi-dimensional analysis 
        ↓
Analysis 
- Trend and segmentation analysis
- Department, role, and country comparisons
- Behavioral analysis (overtime vs burnout)  
        ↓
Output
- Interactive Power BI dashboard (Multi-pages)  

```

## 7. Key Metrics

| Metric                  | Definition                           | Why It Matters                             |
| ----------------------- | ------------------------------------ | ------------------------------------------ |
| Engagement Index        | Average employee engagement score    | Measures overall workforce sentiment       |
| Burnout Rate            | % of employees in high-risk category | Identifies retention and performance risks |
| Overtime Hours          | Average extra working hours          | Key driver of burnout                      |
| Promotion Rate          | % of employees promoted              | Indicates career growth and fairness       |
| Work-Life Balance Score | Employee rating of balance           | Strong predictor of satisfaction           |


## 8. Key Insights

#### **Financial Performance**
<img width="2247" height="1270" alt="2" src="https://github.com/user-attachments/assets/d9086657-cada-48b7-acb5-3b0f444c3097" />

**Profit Recovery Driven by Structural Cost Efficiency**

**Pattern:** Revenue and operating expenses declined during COVID-19, but in the post-COVID period, profit grew at a faster rate than both, with a visibly widening gap between revenue and costs.

**Interpretation:** The divergence between revenue and operating expenses indicates that companies improved cost structures during the crisis reducing or optimizing expenses and maintained this efficiency during recovery.

**Impact:** Profit growth is being driven by structural efficiency rather than top-line expansion. This suggests more resilient and scalable operations, positioning companies to sustain profitability even under future economic pressure.

**Post-COVID Strengthening of Financial Structure**

**Pattern:** Assets, liabilities, and equity declined during the COVID-19 period, followed by a strong recovery, with equity growing at a more stable pace relative to liabilities.

**Interpretation:** During the crisis, companies adjusted balance sheets by limiting growth and preserving capital. In the recovery phase, equity accumulation outpaced reliance on debt, indicating a shift toward stronger internal financing.

**Impact:** The post-COVID period reflects a structurally stronger financial position, with improved balance sheet resilience and reduced dependence on leverage, lowering overall financial risk.

---
#### **COVID-19 Shock and Fast Recovery**
<img width="2220" height="1260" alt="3" src="https://github.com/user-attachments/assets/6a523833-8ed5-4c00-8288-a819bad089be" />

**Pattern:** Revenue, EBIT, and Net Profit dropped clearly in 2020, then bounced back quickly and even exceeded pre-COVID levels by 2021–2022.

**Interpretation:** All key metrics falling at the same time shows how widespread the impact was. But the quick rebound suggests companies adapted fast and were supported during the crisis.

**Impact:** The downturn didn’t last long. Most companies recovered quickly and returned to growth, which points to a strong and resilient business environment.

---
#### **Financial Stability Varies Significantly Across Industries**
<img width="2255" height="1262" alt="4" src="https://github.com/user-attachments/assets/1de72872-1cc3-4ac9-a98b-d3de1244427e" />

**Pattern:** 
- **Revenue:** Wholesale trade (~17M) and mining (~13M) generate the highest revenues, followed by manufacturing (~8M). However, manufacturing also carries high liabilities relative to its size.
- **Profitability Efficiency:** Real estate and mining hold the largest asset bases, while sectors such as education and other services operate with low assets, equity, and margins.
- **Financial Stability:** Real estate achieves the highest net margins and holds strong equity levels (>15M), despite not being the top revenue generator. Smaller or niche categories also show disproportionately high margins.

**Interpretation:**
- High-revenue industries are often capital-intensive and require significant ongoing investment, leading to higher financial obligations and risk exposure.
- Profitability is driven more by business model efficiency than by revenue scale. Asset-based sectors like real estate benefit from stable income streams and lower operating costs.
- Capital-intensive industries build financial buffers through assets, while service-based sectors operate with limited reserves and higher vulnerability to shocks.
  
**Impact:**
- Revenue alone is not a reliable indicator of financial health. High-revenue sectors like manufacturing may face tighter margins and higher risk, requiring closer monitoring of leverage and cost structure.
- High-margin sectors represent more sustainable values. Investors and decision-makers should prioritize efficiency metrics (e.g., margins, returns) over revenue size when assessing performance.
- Financial resilience is uneven across industries. Asset-heavy sectors are better positioned to absorb economic shocks, while smaller service sectors may require external support during downturns.

---

## 9. Recommendations

| Priority | Recommendation                                                      | Based On                                                           | Suggested Owner      |
| -------- | ------------------------------------------------------------------- | ------------------------------------------------------------------ | -------------------- |
| High     | Reduce excessive overtime across teams to prevent burnout           | *“Overtime Impact on Work-Life Balance & Burnout Risk”*            | HR / Team Leads      |
| High     | Identify and support employees in high burnout risk category (~4%)  | *“Burnout Risk Distribution”*                                      | HR                   |
| High     | Focus burnout prevention efforts on IT and Engineering roles        | *“Burnout Hotspots by Department and Role”*                        | HR / Tech Leadership |
| Medium   | Review promotion fairness across departments and genders            | *“Promotions & Promoted Last Year (%) by Department and Gender”*   | HR                   |
| Medium   | Align training programs with promotion outcomes                     | *“Promoted Last Year (%) by Training Hours”*                       | HR                   |
| Medium   | Monitor salary ranges to ensure fair compensation across job levels | *“Monthly Income Distribution by Job Level”*                       | HR / Finance         |
| Low      | Track regional differences in burnout and satisfaction trends       | *“Burnout Risk by Country”* & *“Rating Distribution by Countries”* | HR                   |


## 10. Assumptions & Limitations

### Assumptions
- Survey responses accurately reflect employee sentiment.
- Added Nordic data represents realistic distributions.
- Engagement and burnout scores are consistently measured.
  
### Limitations
- Synthetic/modified dataset may not reflect real company behavior.
- No time-series data .
- Cannot establish causation, only correlation.
- External factors (policy changes, global markets) not fully included

## 11. Author

**Florence Braut**
- 🔗 linkedin.com/in/Florence B
- 💼 Portfolio:https://hef-b.github.io/
- 📧 dainsights@proton.me

