# Data Analyst Portfolio — Nguyen Dinh

Applied Mathematics student at UC Riverside (Class of 2027) building a career in data analytics. This repo contains seven end-to-end analysis projects covering A/B testing, hypothesis testing, customer segmentation, time-series analysis, and website performance — using real-world datasets ranging from 200 to 18,000+ rows.

📍 Santa Ana, CA | 📧 23ndinh@gmail.com | 🔗 [LinkedIn](https://www.linkedin.com/in/nguyen-dinh-199216292/)

---

## Skills Demonstrated

**Excel:** XLOOKUP, VLOOKUP, IF, SUM, AVERAGE, COUNTIF, MONTH, WEEKDAY, LEFT, pivot tables, two-sample t-test (Data Analysis ToolPak), line charts, conditional formatting

**Statistics:** Hypothesis testing, p-value interpretation, Type I/II errors, sample size calculation, minimum detectable effect, confidence intervals, distribution analysis

**Analytical thinking:** Feature engineering, customer segmentation, business recommendation writing, identifying confounding factors

---

## Projects

### 1. Warby Parker A/B Test Analysis
**Question:** Should Warby Parker switch to a new landing page design?
**Dataset:** 1,700+ user satisfaction ratings (test vs. control)
**Method:** Two-sample t-test assuming unequal variances
**Finding:** P-value of 0.149 > 0.05 — failed to reject null hypothesis at 95% confidence.
**Recommendation:** Do not switch the landing page. Documented Type II error risk and suggested follow-up tests with larger sample size and pre-registered hypothesis.
📁 [Milestone-AB-Testing-Warby-Parker Nguyen Dinh.xlsx](./Milestone-AB-Testing-Warby-Parker%20Nguyen%20Dinh.xlsx)

---

### 2. H&M Email A/B Test
**Question:** Does an urgency-based email subject line lift open rates?
**Dataset:** Email send/open data, two groups
**Method:** Sample size calculator, pivot table aggregation, significance calculator
**Finding:** Test group achieved 19% open rate vs. 18% control — statistically significant at 98% confidence.
**Recommendation:** Adopt the new subject line. Identified 5 confounding factors (selection bias, send time, device type, audience overlap, novelty effect) for the team to control in future tests.
📁 [Milestone-AB-Testing-H^0M Nguyen Dinh.xlsx](./Milestone-AB-Testing-H%5E0M%20Nguyen%20Dinh.xlsx)

---

### 3. BART Ridership Analysis (2021)
**Question:** How can BART optimize service across weekdays vs. weekends and downtown vs. outlying stations?
**Dataset:** 18,250 rows of San Francisco BART ridership data (2021)
**Method:** Feature engineering with MONTH, WEEKDAY, LEFT, IF formulas; proportional analysis
**Findings:**
- 82.5% of all trips occur on weekdays
- 79% of trips end on a Yellow Line station
- 28.2% of all ridership flows through 4 downtown SF stations (EM, MT, PL, CC)

**Recommendation:** Concentrate service investment on weekday peak hours and Yellow Line capacity; downtown stations need disproportionate operational support relative to their station count.
📁 [Milestone-BART-Ridership-Analysis Nguyen Dinh.xlsx](./Milestone-BART-Ridership-Analysis%20Nguyen%20Dinh.xlsx)

---

### 4. YouTube Trending Video Analysis
**Question:** What makes a video trend on YouTube?
**Dataset:** 6,351 trending videos with views, likes, category, publish date
**Method:** Data type classification, sorting/filtering, distribution analysis
**Findings:** View distribution is heavily right-skewed; the average (~1.96M views) is misleading because a small number of viral videos pull the mean up. A 2M-view video is closer to typical than exceptional.
**Recommendation:** Content strategy should prioritize category fit, publish timing, and engagement rate over raw view targets.
📁 [Milestone-YouTube-Trending-Analysis Nguyen Dinh.xlsx](./Milestone-YouTube-Trending-Analysis%20Nguyen%20Dinh.xlsx)

---

### 5. Terracotta Plant Survey — Customer Segmentation
**Question:** What should Terracotta advertise to drive sales?
**Dataset:** 218 customer survey responses
**Method:** XLOOKUP for joining maintenance/safety attributes; pivot tables with % of parent row total for segmentation
**Findings:**
- 26.7% of customers most frequently buy low-maintenance plants
- Pet/child safety is the top purchase driver for 50% of "once a year" buyers vs. only 31% of "rarely" buyers — occasional buyers care more about safety than frequent buyers

**Recommendation:** Emphasize low-maintenance and pet-safe attributes in marketing, especially in campaigns targeting infrequent buyers. Delivered as a written stakeholder memo.
📁 [Milestone-Terracotta Nguyen Dinh.xlsx](./Milestone-Terracotta%20Nguyen%20Dinh.xlsx)

---

### 6. Winter Sports Search Interest (Curling vs. Luge)
**Question:** What drives search interest in niche winter sports?
**Dataset:** Multi-year Google search interest for Curling and Luge
**Method:** Line charts, seasonality analysis, hypothesis validation with secondary research
**Findings:** Both sports show flat baseline interest punctuated by 4-year Olympic spikes, with February being the peak month. Spike magnitude varies by host country and team performance.
📁 [Milestone-Winter-Sports-Interest-Analysis Nguyen Dinh.xlsx](./Milestone-Winter-Sports-Interest-Analysis%20Nguyen%20Dinh.xlsx)

---

### 7. Grammys Website Performance Analysis
**Question:** How is the Grammys website performing across user engagement metrics?
**Dataset:** Website performance data
**Method:** Performance metric analysis using Excel formulas and pivot tables
**Outcome:** Identified key engagement patterns and opportunities to improve site performance.
📁 [Project-Analyzing-Website-Performance-Grammys Nguyen Dinh.xlsx](./Project-Analyzing-Website-Performance-Grammys%20Nguyen%20Dinh.xlsx)

---

## Currently Learning

- **SQL** (Mode Analytics tutorial)
- **Tableau** for dashboarding
- **Python pandas** for larger datasets

---

## About Me

Bilingual (English/Vietnamese) Applied Math student with 150+ hours of hands-on data work as a Student Ambassador at Santa Ana College (Aug 2024 – Jul 2025). Honors graduate (3.7+ GPA). Open to **Summer 2026 data analyst internships**.

📧 23ndinh@gmail.com
