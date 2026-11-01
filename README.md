# acrisure-arena-marketing-dashboard
End-to-end data analytics portfolio project featuring relational multi-table data modeling, SQL/Excel preparation, and an interactive Tableau Public executive dashboard evaluating ticket sales, event category performance, and campaign ROI for Acrisure Arena / Oak View Group.
Acrisure Arena — Executive Marketing & Revenue Performance Dashboard



## Project Overview
An end-to-end data analytics and visualization project built to evaluate ticket sales, event category performance, and multi-channel campaign ROI for **Acrisure Arena / Oak View Group** in Palm Springs, CA. 

This project simulates a real-world venue marketing analysis workflow, integrating relational transactional data with direct marketing attribution models to optimize promotional spend and maximize fan engagement.

---

## Key Business Metrics
* **Total Venue Revenue:** $204,495.00[cite: 1]
* **Total Tickets Sold:** 1,354[cite: 1]
* **Active Events Analyzed:** 25 Distinct Events[cite: 1]
* **Top-Grossing Category:** Basketball ($73,453)
* **Primary Marketing Channels:** Email, SMS, App Push[cite: 1]

---

## Data Architecture & Relational Schema
The data model is built around four core relational tables linked via Snowflake/Star schema principles in Tableau:
1. **`transactions.csv`** (Central Fact Table): Stores core purchase history, ticket quantities, and transaction totals[cite: 2, 4].
2. **`events.csv`** (Dimension Table): Linked via `Event ID = Event ID` to categorize events (Concerts, Sports, Family Shows)[cite: 2, 4].
3. **`campaign_sends.csv`** (Dimension Table): Linked via `Customer ID = Customer ID` to track direct marketing touches and channel attribution[cite: 1, 2, 4].
4. **`customers.csv`** (Dimension Table): Linked via `Customer ID = Customer ID` for demographic and loyalty tier segmentation[cite: 2, 4].

---

## Dashboard Architecture (`Executive_Summary`)
* **Sheet 1 (`KPI_Cards`):** High-level executive banner displaying total revenue, total ticket volume, and distinct event counts[cite: 1].
* **Sheet 2 (`Category_Performance`):** Descending horizontal bar chart ranking event categories by total revenue generation with custom color coding[cite: 1].
* **Sheet 3 (`Campaign_ROI`):** Channel-attributed performance breakdown comparing revenue return across Email, SMS, and App Push campaigns[cite: 1].

---

## Live Tableau Public Dashboard
Explore the fully interactive visualization here:  
👉https://public.tableau.com/app/profile/ryan.vinson/viz/AcrisureArenaExecutiveMarketingRevenueDashboard/Executive_Summary





---

## Tools & Technical Stack
* **Relational Modeling & Data Prep:** Tableau Data Source Canvas (Multi-table logical relationships)[cite: 1, 2, 4]
* **Data Visualization:** Tableau Public Web Authoring (KPI Cards, Horizontal Bars, Custom Color Palettes)[cite: 1]
* **Version Control:** Git & GitHub for professional portfolio presentation
