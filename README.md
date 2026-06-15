 Global Airbnb Performance Dashboard — Power BI
 Power BI DAX Data Analytics
 # 🏠 Global Airbnb Performance Dashboard — Power BI

![Power BI](https://img.shields.io/badge/POWER_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0088CC?style=for-the-badge)
![Data Analytics](https://img.shields.io/badge/DATA_ANALYTICS-FF5A5F?style=for-the-badge&logo=airbnb&logoColor=white)

> A 3-page interactive Power BI dashboard analyzing Airbnb listing, pricing, ratings, and review data across 10 global cities — uncovering market trends, customer behavior, and host trust patterns.


---


## 📊 Dashboard Preview

### Page 1 — Overview
![Overview Dashboard](screenshots/Overview.png)


### Page 2 — Ratings & Market Share


### Page 3 — Reviews & Trust


---

## 📌 Key Metrics

| Metric             | Value   |
| ------------------ | ------- |
| 🏘️ Total Listings | 279,712 |
| 👤 Total Hosts     | 182,024 |
| 🏙️ Cities Covered | 10      |
| 🏷️ Property Types | 144     |
| ⭐ Total Reviews    | 5.37M   |

---

## 📁 Dashboard Pages

### 🔹 Page 1 — Overview

* Tracks total listings, hosts, cities, property types, and reviews at a glance
* Lifecycle analysis of Airbnb's growth — from Introduction → Growth → Maturity → Decline → Reinvention → COVID-19
* 2015 marked the peak year for new listings
* Growth was restrained from 2016–2017 due to tightening local regulations
* Airbnb turned profitable in the second half of 2016
* New listing growth halted in 2019 due to the COVID-19 pandemic
* Entire Place listings dominate across all property types
---

### 🔹 Page 2 — Ratings & Market Share

This page focuses on customer satisfaction, pricing, and city-level market concentration.

#### Market Share Insights

* Paris, New York City, and Sydney account for nearly half of all listings and 48% of total reviews.
* Paris leads with the most listings and reviews.
* Key pricing insights: Hotel rooms average $800 - nearly double Entire Places($673)

| Room Type    | Average Price |
| ------------ | ------------- |
| Hotel Room   | $800          |
| Entire Place | $673          |
| Shared Room  | $580          |
| Private Room | $462          |

* Highest-rated cities: Mexico City (94.8) and Rio de Janeiro (94.6)
* Lowest-rated cities: Hong Kong (89.7) and Istanbul (91.1)
* Cleanliness and Value for Money are the lowest-rated categories globally.

---

### 🔹 Page 3 — Reviews & Trust

* Most customers reviewed only once; 98.8% of reviewers gave 3 or fewer reviews.
* Paris and Rome dominate review share from April to August, reflecting peak European summer travel.
* New York saw a review spike in November and December during the holiday season.
* Over two-thirds (66.9%) of Airbnb hosts are fully verified (identity verified + profile picture).
* Nearly all hosts provide at least one trust signal, keeping anonymous/unverified profiles minimal.

---

## 🛠️ Tools & Skills Used

| Category | Details                                                                                                                      |
| -------- | ---------------------------------------------------------------------------------------------------------------------------- |
| Tool     | Microsoft Power BI Desktop                                                                                                   |
| Language | DAX (Data Analysis Expressions)                                                                                              |
| Skills   | Data Visualization, Business Analysis, EDA, KPI Design, Dashboard Development, Data Storytelling |

---

## 📐 DAX Functions Used

```DAX
CALCULATE
FILTER
ALL
ALLSELECTED
DIVIDE
DISTINCTCOUNT
MAXX
VALUES
```

---

## 💡 Key Business Insights

1. Pricing Gap - Hotel rooms are priced ~73% higher than Entire Places, yet customer satisfaction remains competitive across room types

2. Market Concentration - Only three cities—Paris, New York City, and Sydney—drive nearly 50% of Airbnb's total activity.

3.Review Behavior - Airbnb's review system is sparse; the vast majority of guests review only once, suggesting reviews carry high signal value.

4. Seasonality - European destinations dominate mid-year travel demand, while U.S. cities peak during the holiday season.

5. Host Trust - Strong verification adoption reflects a mature and trust-focused hosting ecosystem.

6. COVID-19 Impact - The pandemic interrupted Airbnb's growth trajectory and significantly slowed new listing creation globally.

---

## 📸 Dashboard Features

✔ Interactive navigation buttons
✔ Dynamic KPI cards
✔ Custom DAX calculations
✔ Market share analysis
✔ Review distribution insights
✔ Seasonal trend analysis
✔ Host trust and verification metrics
✔ Responsive visual storytelling

---

## 📬 Connect

If you found this project useful, feel free to:

* ⭐ Star this repository
* 🐛 Report issues
* 💡 Suggest improvements

Let's connect on [Linkedin](https://www.linkedin.com/in/gajendra01/) and discuss data analytics, Power BI, and business intelligence projects.

