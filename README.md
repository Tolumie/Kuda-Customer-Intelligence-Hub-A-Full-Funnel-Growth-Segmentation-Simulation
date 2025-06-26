
# 🚀 Business Intelligence Analyst Simulation – Kuda for Business

## 💼 Project Purpose

This is a self-directed simulation project built to mirror the full responsibilities of a **Business Intelligence Analyst at Kuda for Business**, designed and built with a **full-funnel analytics pipeline** that mirrors how fintech teams drive **product growth**, **customer segmentation**, and **retention**. The system simulates real-world data for Kuda — a digital-only bank — and tracks the **entire user lifecycle** from **marketing clicks to churn**. The system tracks the **entire user journey from marketing to retention, integrates data ingestion, transformation, analysis, and dashboarding**, calculates key business metrics (e.g., **Churn, CAC, LTV, MoM/YoY Growth**), and also includes **A/B testing simulations** to support decision-making across **Product**, **CRM**, and **Growth** teams — all tuned for smarter strategy and sharper execution.

The end goal is to provide a **dashboard and reporting suite** that empowers executive teams to make data-driven decisions—**all while showcasing the real challenges fintechs face in aligning growth with product performance**, and most importantly, enabling **personalized strategies through a dynamic customer segmentation framework, designed to maximize user value and minimize churn.**

It goes beyond basic dashboards — covering **data simulation, trend analysis, segmentation, campaign testing**, and **executive reporting** — all grounded in realistic FinTech use cases.


---
## 🎯 Business Goals & Stakeholder Questions

### 👥 **Assumed Stakeholders**

* **Growth Marketing Team** — focused on user acquisition & CAC
* **Product Managers** — tracking activation & retention funnels
* **CRM Team** — driving re-engagement via emails & push
* **Executives (CEO/COO/CFO)** — care about ROI, LTV, and growth

---

### 🧠 **Core Business Objectives & Analytical Questions**

#### 📌 **Retention & Churn**

* What percentage of users return on **Day 1**, **Day 7**, and **Day 30**?
* Where are users **dropping off** in the onboarding funnel?
* What are our **monthly** and **quarterly churn rates**?

#### 📌 **Customer Acquisition Cost vs Lifetime Value (CAC vs LTV)**

* What’s the **CAC per campaign/platform**?
* What’s the **average LTV** by UTM source, signup cohort, or platform?
* Are we **overpaying** to acquire **low-LTV users**?

#### 📌 **Funnel Conversion Rates**

* What percentage of users move from:
    * **Signup → Activation?**
    * **Activation → First Transaction?**
    * **First Transaction → Retention?**

#### 📌 **CRM Campaign ROI**

* What’s the **retention uplift** from email/push campaigns?
* Does **A/B testing** show a statistically significant impact?
* What’s the **ROI** on our CRM automation tools?

#### 📌 **Growth Metrics**

* What’s our **Month-on-Month (MoM)** and **Year-on-Year (YoY)** user growth?
* How are **campaign spend and signups trending** over time?

#### 📌 **Customer Segmentation & Personalization**

* Can we **cluster users** based on behavioral or transactional patterns?
* Which segments have the **highest LTV, lowest churn, or strongest growth**?
* Are we able to **personalize marketing/CRM strategies** based on these segments?
* What are the demographics and behaviors of our **most loyal customers**?
* How can we leverage **segment-specific insights** to recommend tailored product features or CRM interventions?


---

| 💬 **Term**                          | 🔍 **Simple Meaning**                                                        |
| ------------------------------------ | ---------------------------------------------------------------------------- |
| **Neobank**                          | A 100% online bank — no branches, just the app. Kuda is one of them.         |
| **Smart Budgeting**                  | The app helps users manage money using rules or AI.                          |
| **Instant Credit**                   | Giving loans based on app activity, no long paperwork.                       |
| **LTV (Lifetime Value)**             | Total money a user brings in before they leave.                              |
| **CAC (Customer Acquisition Cost)**  | How much it costs to bring in one new user.                                  |
| **Churn Rate**                       | % of users who stop using the app.                                           |
| **Conversion Rate (CR%)**            | % of people who take an action (like sign up after seeing an ad).            |
| **Customer Segmentation**            | Grouping users by behavior or value for smarter targeting.                   |
| **BI Tools (Power BI)**              | Tools for building charts and dashboards. Used to report metrics clearly.    |
| **SQL**                              | Language used to talk to Kuda’s databases.                                   |
| **A/B Testing**                      | Testing two versions (e.g., offer A vs B) to see which works better.         |
| **Full-Funnel Analytics**            | Tracking every step from user sign-up to repeat use.                         |
| **Data Ingestion**                   | Pulling data in from all sources (like CRM, product, support).               |
| **Data Transformation**              | Cleaning and reshaping the data for analysis.                                |
| **Data Analysis**                    | Finding patterns or problems in the data to help decisions.                  |
| **Dashboarding**                     | Turning insights into visual charts for managers to act on.                  |
| **CRM Team**                         | Handles user messages (emails, in-app), and how/when users are contacted.    |
| **Executives (CEO/COO/CFO)**         | Top decision makers who use dashboards and reports to steer growth.          |
| **Retention**                        | % of users who keep using the app over time.                                 |
| **CAC vs. LTV**                      | Comparing cost to acquire a user vs. how much they bring in.                 |
| **ROI (Return on Investment)**       | Whether what Kuda spends (on ads, campaigns, features) is worth it.          |
| **CRM (Customer Relationship Mgmt)** | Tools and systems to manage how users are treated.                           |
| **Funnel Conversion Rates**          | Checking where users drop off in the journey (e.g., signup → first deposit). |
| **CRM Campaign ROI**                 | Profit made from messages/campaigns sent through the CRM.                    |
| **MoM Growth**                       | Month-over-month growth — short-term progress tracking.                      |
| **Personalization**                  | Making user experiences feel tailored and custom (e.g., custom offers).      |
| **Engagement**                       | How often users interact with Kuda's app and features.                       |
| **Attribution**                      | Figuring out what ad or source brought a user to Kuda.                       |
| **Predictive Modeling**              | Using past data to forecast behavior (like churn or credit risk).            |
| **Anomaly Detection**                | Flagging weird or unexpected user behavior (e.g., fraud spikes).             |
| **KPI (Key Performance Indicator)**  | Important metrics Kuda tracks to know if things are working.                 |
| **Data Literacy**                    | The ability of Kuda’s team (tech + non-tech) to understand and act on data.  |

---
---

## 🧠 Bonus Jargon

| **Jargon** | **Translation** |
| :--------------------- | :---------------------------------------------------------------------------------------------------------------- |
| “Data Democratization” | Making data accessible to *everyone* in the company, not just analysts. |
| “North Star Metric” | The one KPI that matters most. For Kuda, it might be *monthly active users* or *retention*. |
| “Attribution” | Tracking where users come from (e.g., Google Ads, social media). |
| “Retention Cohorts” | Tracking users over time based on when they signed up. Helps you know if product changes actually help. |
| “Data Ecosystem” | The complete stack: data warehouse, pipelines, BI tools, analytics. |

---

## 🔄 **Project Architecture Flow:**

```css
Marketing Sources → CRM (HubSpot) → App Events (Amplitude)
→ SQL Database (Snowflake/PostgreSQL) → Retention & Metrics Analysis (Python, SQL)
→ Customer Segmentation (Python/ML) → Personalization Recommendations → A/B Testing → Dashboard Visualization (Tableau/Power BI)
```

---
## 🧱 Phase 1: Data Ecosystem Simulation

### ✅ Status: Complete

Simulated 5 core datasets reflecting Kuda’s operational layers:

| Table | Description |
|-------|-------------|
| `customers` | Business users with churn flags, signup dates, and A/B group tags |
| `transactions` | Deposit/transfer/withdrawal actions tied to merchants |
| `merchants` | Vendors segmented by industry and region |
| `campaigns` | Marketing actions with test/control design |
| `tickets` | Support logs, resolutions, and ticket types |

Data volume: 
| Table             | Rows    | Business Function                         |
| ----------------- | ------- | ----------------------------------------- |
| `customers`       | 100,000 | Core user base + churn + A/B assignment   |
| `merchants`       | 500     | Merchant partners + category + risk       |
| `transactions`    | 1.7M+   | Core behavioral data (spend, fraud, etc.) |
| `crm_events`      | 300,000 | Campaigns, opens, clicks, conversions     |
| `support_tickets` | 300,000 | Issues, delays, complaints, churn signals |

Tools: Python (`faker`, `pandas`, `uuid`), CSV/Excel previews

**📂 File Structure**:  
`/01_data_simulation/`  
Includes: `simulate_customers.py`, `init_db.sql`, `data_dictionary.xlsx`, `ERD.drawio`

---

## 📊 Phase 2: Exploratory Data Analysis (EDA)

### ✅ Status: In Progress

**Focus**: Uncover actionable behavioral trends using the simulated data.

### 🔍 Key Business Questions Tackled:
| Question | KPI | Source |
|----------|-----|--------|
| Which industries churn the most? | `churn rate` | `customers.industry` |
| Are CRM campaigns affecting behavior? | `churn vs ab_group` | `customers.ab_group` |
| Which regions show the highest signup or drop-off? | `monthly_signups` | `customers.region` |

---

### 📈 Current EDA Progress:

- 🧾 Cleaned and profiled `customers.csv`
- 📊 Built **monthly signup timeline**
- 📍 Analyzed **churn by industry**
- 🌍 Heatmap of **signup by region over time**
- 🔁 Evaluated **A/B group churn differentials**

### 🧠 Sample Insight:
> **“Logistics and Agriculture sectors show 27%+ churn rates. Lagos dominates user signup growth, but churn is higher in Northern zones. CRM ‘treatment’ groups churn ~7% less — signaling campaign potential.”**

---

### 📘 What’s Coming in Phase 2:

- 📊 **Merchant-level activity visualizations**
- 🧩 **Churn clustering with transaction behavior**
- 📬 CRM engagement impact (if `crm_events` simulated)

---

### 📂 Folder Structure (New)
```bash
/02_eda/
├── Exploratory Data Analysis (EDA).ipynb
├── churn_by_industry.png
├── signup_trends_over_time.png
└── ab_churn_summary.png
````

---

## 📆 Project Roadmap (Sprint-Based)

| Phase                       | Status         | Summary                           |
| --------------------------- | -------------- | --------------------------------- |
| Phase 1: Data Simulation    | ✅ Done         | Generated 5 datasets & schema     |
| Phase 2: EDA                | 🔄 In Progress | Signup trends, churn signals      |
| Phase 3: Dashboarding       | ⏳ Coming       | CAC/LTV, funnel, churn heatmaps   |
| Phase 4: Segmentation       | ⏳              | KMeans, DBSCAN personas           |
| Phase 5: A/B Testing        | ⏳              | Campaign test evaluation          |
| Phase 6–7: KPIs & Reporting | ⏳              | Executive TL;DR + PDF decks       |
| Phase 8: Compliance         | ⏳              | Field minimization + schema notes |

---

## 👀 Live Preview (Coming Soon)

* 📊 Power BI dashboard
* 🧪 A/B test significance reports
* 📄 Final TL;DR summary & executive PDF

---

## 🔗 Repo Contents

* `/data/` – raw + processed mock data
* `/notebooks/` – EDA workflows
* `/dashboards/` – Power BI files + screenshots
* `/sql/` – schema, views, metrics queries
* `/reports/` – stakeholder-facing outputs
* `/code/` – clustering & analytics logic
* `README.md` – current file
* `requirements.txt` – libraries used

---

## 📞 Contact & Notes

If you're from the Kuda team, this simulation was engineered precisely to reflect your job role — but with extra strategic polish. If you'd like a walkthrough or want to run this on real data, let's talk.

**Toluwalope Ogunbodede**
📩 ogunbodedetolulopeisrael@gmail.com
🔗 www.linkedin.com/in/ogunbodede-tolulope-israel-b4568219b

> 🧠 “This project doesn’t ask for the job. It shows you the **impact you're missing** by not hiring the mind behind it.”

```
