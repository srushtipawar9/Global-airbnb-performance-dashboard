<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/36c1773a-08bc-4d08-8868-1cbd076139ec" /># 🏠 Global Airbnb Performance Dashboard

An interactive 3-page Power BI dashboard analyzing Airbnb's global performance across 10 major cities — covering listings, hosts, reviews, pricing, ratings, trust signals, and seasonality trends from 2008 to 2020.

![Dashboard Preview](assets/overview.png)

---

## 📌 Problem Statement

Airbnb operates across dozens of global markets, but performance, pricing, and guest trust signals vary widely by city. This project answers key business questions a market strategy or growth team would ask:

- Which cities dominate Airbnb's global listings and review volume?
- How has the platform's growth evolved over its lifecycle (2008–2020), and what external events shaped it?
- How do prices vary by room type, and how does that compare to hotel pricing?
- Which cities have the most trustworthy (verified) hosts, and which have quality/rating gaps?
- Are there seasonal booking patterns that vary by city?

---

## 📊 Dataset

- **Scope:** 10 global cities
- **Size:** 2,79,712 listings · 7M+ hosts · 144 property types · 527T+ reviews
- **Fields:** listing ID, city, room type, price, host verification status, review count, review date, rating categories (accuracy, cleanliness, communication, location, value)

---

## 🛠️ Tools & Tech Stack

| Category | Tools |
|---|---|
| Data Modeling & Visualization | Power BI |
| Data Transformation | Power Query |
| Calculations / KPIs | DAX |
| Data Source / Querying | SQL |

---

## 🔍 Approach

1. **Data Cleaning & Transformation** — Used Power Query to clean and shape raw listings/reviews data, handling inconsistent city naming, missing values, and date formatting.
2. **Data Modeling** — Built relationships between listings, hosts, and reviews tables; created DAX measures for cumulative %, average ratings, and review frequency.
3. **Dashboard Design** — Built a 3-page report (Overview, Ratings, Reviews) with drill-down interactivity via city and property filters.

---

## 💡 Key Findings

### 📈 Overview — Platform Lifecycle (2008–2020)
- Airbnb's listings growth follows a clear lifecycle: **Introduction → Growth → Maturity (peak ~2015) → Decline → Reinvention → COVID-19 impact**.
- **2015** marked the highest number of new listings; growth slowed in 2016–2017 due to tightening local regulations in major cities.
- Airbnb became **profitable in H2 2016**, with **2017 as its first full year of positive income**.
- Renewed growth from 2018 was cut short by the **COVID-19 pandemic in 2019–2020**.

### 🌍 Market Share by City
- **Paris, New York, and Sydney** together account for **almost half of total listings and 48% of total reviews** — heavy market concentration in a few cities.
- **Paris** leads in both listings and reviews, likely driven by **hotel room prices being nearly 2x Airbnb's average price** in the city.
- Average price by room type: **Hotel room ($800) > Entire place ($673) > Shared room ($580) > Private room ($462)**.

### ⭐ Ratings
- **Mexico City and Rio de Janeiro** are the highest overall-rated cities; **Hong Kong and Istanbul** rank lowest.
- Across all cities, **cleanliness and value-for-money** are consistently the two lowest-scoring rating categories — a potential focus area for host quality programs.

### 📝 Reviews & Trust
- **Guest engagement is mostly one-time**: most customers leave only **one review**, and **98.8% of customers review 3 times or fewer**.
- One outlier customer left **283 reviews** — flagged as a likely **data anomaly or unusually frequent traveler**, both submitted on the same day for two Bangkok listings.
- **Trust signals are strong platform-wide**: over **two-thirds (66.9%) of hosts are fully identity-verified with a profile picture**, and only **0.3% show neither signal** — showing Airbnb's verification system is largely effective.
- **Seasonality**: **Paris and Rome dominate review share from April–August** (peak European summer travel), while **New York sees a spike in November–December** (holiday season).

---

## 📷 Dashboard Pages



---

## 🚀 How to View
1. Download the `.pbix` file from Google Drive: **[Download PBIX File](https://drive.google.com/file/d/1lj0V0h61GRPFpNfsouQ7vDGY-NVRPUbb/view?usp=sharing)**
2. Open in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)

---

## 🔮 What I'd Improve Next

- Investigate the 283-review outlier as a potential data quality issue before drawing conclusions from review-frequency metrics
- Add a booking-price-over-time trend to correlate pricing changes with the regulatory slowdown seen in 2016–2017
- Layer in host superhost status to see if it correlates with the cleanliness/value rating gaps

---

## 👤 Author

**Srushti Pawar**
[LinkedIn](https://linkedin.com/in/srushtipawar9) · [GitHub](https://github.com/srushtipawar9)
