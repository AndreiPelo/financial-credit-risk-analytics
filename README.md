# Executive Risk Briefing: German Credit Portfolio Analysis

## 1. Project Objective
This analysis evaluates a credit portfolio consisting of 1,000 corporate and individual borrower records across 11 engineered financial and demographic features. The core goal is to isolate credit concentration risks, identify high-exposure demographic clusters, and establish statistical guardrails to optimize capital allocation for commercial lending operations.

---

## 2. Key Findings & Business Insights

### 📊 Capital Exposure Drivers (Duration vs. Credit Value)
Exploratory Data Analysis (EDA) revealed an extensive, strong positive linear correlation ($r = 0.625$) between loan repayment terms and total credit value. 
* **Business Implication:** Capital risk scales dynamically with time. Larger credit requests are structurally bound to extended durations (40–72 months) to keep monthly payment installments within borrower cash-flow limits, heavily compounding long-term default exposure for the institution.
* **Contrast:** Conversely, borrower age demonstrated zero linear relationship ($r = 0.033$) with loan size, showing that credit appetite remains uniform across age groups.

### 👥 High-Risk Demographic Concentrations
Cross-tabulation and statistical profiling isolated a critical pocket of capital concentration within specific generational brackets:
* **The Core Volume Driver:** The **Middle-Aged (30–50) cohort** represents the bank’s largest commercial footprint, commanding the highest volume of both *Medium-Exposure* ($1,500–$4,000) and *High-Exposure* (> $4,000) financing agreements. This highlights a pool of established, high-income professionals capable of absorbing significant credit overhead.
* **The Collateral Anomaly:** Borrowers categorized as **"Housing-Free"** (individuals living rent-free with family or relatives) display an elevated median loan amount approaching **$4,000**—nearly double the median loan size of traditional homeowners and renters ($2,200). 

### 🚗 Product Portfolio Allocations
* **Volume & Extreme Risk:** Financing for **Cars** and **Business ventures** represents the primary operational use of credit lines. The `Car` portfolio features a dense cluster of high-value outliers stretching up to **$15,000–$18,424**, representing localized pockets of intense loss exposure.
* **The Statistical Skew:** While **Vacation/Others** displays the highest overall median loan value (~$7,000), data profiling confirmed a sample size of only 12 records. This indicates an isolated, low-frequency product segment heavily skewed by a few luxury financing requests rather than an expansive corporate trend.
* **Low-Risk Baseline:** Consumer lines for **Domestic Appliances** remain structurally compressed around a narrow, highly predictable corridor (~$1,000), offering steady, low-risk interest income.