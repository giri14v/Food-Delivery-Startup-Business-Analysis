# Food-Delivery-Startup-Business-Analysis
The Analysis is all about Crisis impact of QuickBites Express, a Bengaluru based Food Delivery Startup

# 📊 QuickBite Express Crisis Analysis & Recovery Strategy

## 🏷️ Project Tagline
**Primary Analysis:** *Diagnosing a 70% Demand Collapse Through Operational Failure*  
**Secondary Analysis:** *Why QuickBite Failed While the Market Thrived*

---

## 📌 Project Overview
This project delivers an **end-to-end analytical investigation** into the **QuickBite Express platform crisis**, which resulted in a **sustained ~70% collapse in order volume** during mid-2025.  
Unlike short-lived market fluctuations, QuickBite’s decline showed **no V-shaped recovery**, indicating a **structural breakdown of trust and operations**.

The study combines:
- **Primary analysis** (internal platform data)
- **Secondary analysis** (market & competitor benchmarking)
- **Strategic recommendations** grounded in operational reality

---

## 🧠 Business Problem
QuickBite faced:
- Severe **order volume collapse**
- Sharp **increase in cancellations**
- Major **rating deterioration**
- **Churn of loyal & high-value customers**
- **~71% revenue loss**
- **Tripling of CAC**

Core question:
> *Was this a market slowdown—or an internal failure—and how can QuickBite recover competitively?*

---

## 🛠️ Tools & Technologies
- **Power BI** – KPI modeling, DAX measures, dashboards  
- **SQL** – Customer cohorts, churn & loyalty segmentation  
- **Python (optional extension)** – Sentiment & review analysis  
- **Market Research** – Swiggy & Zomato benchmarking  

---

## 📂 Datasets (High-Level)
- Orders, customers, restaurants, delivery partners  
- Ratings, cancellations, delivery times  
- Revenue components (subtotal, discount, delivery fee)  

---

## 📘 Abbreviations & Terminology

This section lists all key abbreviations used throughout the **QuickBite Express Crisis Analysis & Recovery Strategy** project, along with their meanings, to ensure clarity for readers and reviewers.

| Abbreviation | Full Form | Meaning / Context |
|-------------|----------|------------------|
| **SLA** | Service Level Agreement | Defined delivery time commitment promised to customers |
| **SLA Breach** | — | Order delivered beyond the promised SLA window |
| **CAC** | Customer Acquisition Cost | Cost incurred to acquire a new customer |
| **LTV** | Lifetime Value | Total revenue expected from a customer over their lifetime |
| **GOV** | Gross Order Value | Total value of orders placed (used by Swiggy) |
| **NOV** | Net Order Value | Net order value after adjustments (used by Zomato) |
| **MTU** | Monthly Transacting Users | Number of unique users placing orders in a month |
| **YoY** | Year over Year | Comparison of metrics against the same period last year |
| **QoQ** | Quarter over Quarter | Comparison of metrics against the previous quarter |
| **KPI** | Key Performance Indicator | Metrics used to measure business performance |
| **ETA** | Estimated Time of Arrival | Estimated delivery time shown to customers |
| **COD** | Cash on Delivery | Payment mode where customers pay upon delivery |
| **Tier-1 Cities** | — | Major metro cities with high demand density |
| **Tier-2 Cities** | — | Emerging cities with moderate demand growth |
| **Cloud Kitchen** | — | Restaurant operating only via delivery, no dine-in |
| **Dine-in Restaurant** | — | Restaurant offering on-premise dining |
| **Churn** | — | Customers or restaurants stopping usage of the platform |
| **Reactivation Rate** | — | Percentage of churned users who return to place orders |
| **Basket Size** | — | Average value of an order |
| **High-Value Customers** | — | Top 5% customers ranked by total spend |
| **Loyal Customers** | — | Customers with ≥5 pre-crisis orders |
| **V-shaped Recovery** | — | Rapid drop followed by quick rebound in demand |
| **Operational Moat** | — | Sustainable competitive advantage through execution |
| **Sentiment Score** | — | Quantitative measure of customer review sentiment |

---

**Note:**  
All abbreviations are used consistently across dashboards, analysis sections, and strategic recommendations to maintain analytical clarity and professional reporting standards.


# 🔍 PRIMARY ANALYSIS — What Happened Inside QuickBite?

## 1️⃣ Order Volume Collapse
- **~69–71% drop starting June 2025**
- Volumes stayed **flat at the lowest level (July–September)**
- No organic recovery → **habitual demand destroyed**

**Insight:**  
QuickBite lost **core high-frequency users**, not fringe demand.

---

## 2️⃣ City-Level Demand Shock
- Tier-1 cities (Chennai, Bengaluru, Kolkata, Hyderabad, Ahmedabad) saw **~69–70% declines**
- Indicates **systemic operational failure**

---

## 3️⃣ Restaurant-Level Impact
- Even **high-volume restaurants (≥50 pre-crisis orders)** experienced **50–74% order declines**
- Brand strength did **not protect** restaurants from platform failure

---

## 4️⃣ Cancellation Surge
- Pre-crisis: **~7–8%**
- Crisis: **~11–13%**
- **~55–70% relative increase**

Most impacted cities: **Ahmedabad, Mumbai, Chennai**

---

## 5️⃣ Delivery & SLA Breakdown
- Avg delivery time: **~40 → ~60 minutes**
- SLA breach rate: **~90%**

This operational collapse directly fueled **cancellations, churn, and rating decline**.

---

## 6️⃣ Rating Collapse
- Pre-crisis stable: **4.3–4.7**
- July crash: **2.6**
- September low: **~2.3**

**Trust failure, not gradual dissatisfaction.**

---

## 7️⃣ Revenue Impact
- **Revenue loss:** ~**70.96%**
- Driven primarily by **order subtotal collapse**
- Discount reduction was a **symptom**, not a fix

---

## 8️⃣ Loyalty & High-Value Customer Erosion

### Loyalty Impact
- Loyal customers (≥5 pre-crisis orders): **57**
- Stopped ordering during crisis: **48 (~84%)**
- Of these, **52% had avg ratings >4.5**

### High-Value Customers (Top 5% by spend)
- Avg rating change: **–4.22**
- Avg order frequency drop: **–2.46 orders**
- **~74% faced delivery times >60 minutes**

---

# 🌍 SECONDARY ANALYSIS — Why Competitors Didn’t Collapse

## Competitive Benchmarking: QuickBite vs Swiggy & Zomato

| Platform | Q2 FY26 Trend | Crisis Nature | Recovery |
|--------|--------------|--------------|---------|
| **QuickBite** | ~70% volume drop | Structural trust failure | No rebound |
| Swiggy | +18–19% GOV YoY | Minor softness | Strong recovery |
| Zomato | +14% NOV YoY | Temporary dips | Full recovery |

**Conclusion:**  
The market remained strong. QuickBite’s collapse was **internally driven**, not macroeconomic.

---

## CAC Explosion — Root Cause
- Rating collapse → poor conversion
- SLA failures → first-order churn
- Loyal user loss → organic demand collapse

**CAC tripled because trust collapsed.**

---

# 🧩 ADDITIONAL DEEP-DIVE INSIGHTS

## Restaurant Churn Risk: Who Is Most Vulnerable?

### High Churn Risk
- **Cloud kitchens**
- **Small, unbranded restaurants**
- **Delivery-time–sensitive cuisines**:
  - Biryani
  - Fast food
  - North Indian combos

### Lower Churn Risk
- Established dine-in brands
- Restaurants with:
  - Strong brand recall
  - Multi-platform presence
  - Consistent SLA performance

**Insight:**  
Supply-side churn compounds demand loss, accelerating platform decline.

---

## Lapsed Customers Most Likely to Return

### High Return Probability
- Pre-crisis loyal users (≥5 orders)
- Avg rating **>4.5 before crisis**
- Top 5% spenders
- Urban Tier-1 customers
- Churn driven by **experience failure**, not price sensitivity

### Low Return Probability
- Crisis-period first-time users
- Low-frequency, discount-only customers

**Insight:**  
Recovery should prioritize **reactivation over acquisition**.

---

# 📌 EXTRA INSIGHTS

## Priority Cities at Long-Term Risk
- Ahmedabad, Bengaluru, Chennai, Mumbai
- High overlap of:
  - Delivery delays
  - Cancellations
  - Loyal customer churn

---

## Behavior Shift During Crisis
- Movement from **high-value habitual orders** to **low-value survival orders**
- Basket size erosion preceded full churn

---

## Feedback Alignment
- Negative review spikes align with:
  - Delivery outages
  - SLA breach surge
  - Rating collapse (June–July)

---

# 🚀 STEP-PHASE STRATEGIC RECOMMENDATIONS

## 🟢 Phase 1: Stabilize Trust (0–30 Days)
**Goal:** Stop demand freefall

**Actions**
- SLA-backed delivery guarantees
- Emergency food safety audits
- Transparent in-app communication
- Realistic ETA commitments

**KPIs**
- SLA breach ↓
- Cancellation rate ↓
- Avg delivery time ↓

---

## 🟡 Phase 2: Win Back the Core (30–90 Days)
**Goal:** Reactivate loyal & high-value users

**Actions**
- Personalized offers for:
  - ≥5 pre-crisis orders
  - Avg rating >4.5
  - Top 5% spenders
- Experience-linked incentives
- “Verified Fast & Safe” restaurant badges

**KPIs**
- Reactivation rate
- Repeat order frequency
- Rating recovery trend

---

## 🔵 Phase 3: Strengthen Supply & Ops (90–180 Days)
**Goal:** Build operational moat

**Actions**
- Prune high-cancellation restaurants
- Prioritize reliable dine-in & audited cloud kitchens
- Segment ops for time-sensitive cuisines
- Reliability-based delivery partner payouts

**KPIs**
- Restaurant churn ↓
- Avg basket size ↑
- High-value order share ↑

---

## 🟣 Phase 4: Controlled Growth (6–12 Months)
**Goal:** Sustainable recovery

**Actions**
- Trust-first growth marketing
- Tier-1 city stabilization before expansion
- Early-warning system for SLA, cancellations, ratings

**KPIs**
- CAC normalization
- Organic vs paid order mix
- City-level recovery curves

---

## 🧾 Final Executive Insight
> **QuickBite did not lose demand because the market weakened—it lost demand because trust collapsed in a strong market.**

Recovery requires:
**Operational reliability → Trust restoration → Loyal user reactivation → Sustainable growth**

---

## 📎 Future Extensions
- Power BI KPI monitoring dashboards  
- Churn prediction & reactivation scoring  
- Board-level recovery roadmap

**Author:** Sri Sankar Giri | Data Analyst
**Use Case:** Portfolio | Consulting Case | Power BI Project | Strategy Analysis
