# Breaking Games Dashboard
## Project Overview

This project presents an interactive e-commerce analytics dashboard created for the **Breaking Games SQL & Database Architecture Externship**.

The dashboard was designed to support Q4 planning by highlighting patterns in revenue performance, traffic quality, Meta advertising efficiency, and checkout behavior.

> **Note:** The underlying SQL queries, raw datasets, and database files are not included in this repository. This repository contains only the final dashboard deliverable and project-level documentation.

## Dashboard Focus Areas

The dashboard is organized around four business questions:

1. **Revenue Performance** — Which products contribute the most revenue, and how concentrated is revenue across the catalog?
2. **Traffic Quality** — Which acquisition channels generate meaningful traffic and stronger reported conversion performance?
3. **Meta Advertising Efficiency** — Which campaigns show stronger engagement and cost-efficiency signals, and where should spending be reviewed?
4. **Checkout Friction** — Which products and geographic markets show the largest observed checkout-to-order gaps?

## Key Findings

### Revenue Performance

- Approximately **13 products account for 80% of company revenue**.
- The **Dwellings of Eldervale** product family appears among the strongest revenue-generating products.
- Dwellings of Eldervale 2nd Edition has an **Average Selling Price (ASP) of approximately $103.28**, compared with the **$30.98 catalog average**.

### Traffic Quality

- **Organic Search** generated **79,556 pageviews** and **378 checkout sessions**.
- **Email** and **Community/Referral** show stronger reported conversion efficiency at lower traffic volumes.
- **Paid Social** generated substantial traffic but showed weaker reported downstream conversion performance.

### Meta Advertising Efficiency

- **Traffic TOF** generated 39,419 recorded results at approximately **$0.22 per result**.
- **Dwellings LPV** showed strong engagement and a low **$0.24 cost per result**.
- **Sales ATC** recorded the highest CTR at approximately **2.507%**.
- **DA | Sales** represented approximately **$12.9K in spend with zero recorded results**, making tracking validation and budget review a priority.

### Checkout Behavior

- Several products show large observed checkout-to-order gaps and may warrant deeper investigation.
- International abandoned checkouts are associated with materially higher shipping costs than U.S. checkouts.
- The dashboard also shows checkout volume by billing country using both counts and percentage share.

## Q4 Recommendations

- Prioritize availability and replenishment for the small group of products driving the majority of revenue.
- Continue investing attention in Organic Search while testing controlled growth in Email and Community/Referral.
- Maintain efficient Meta traffic campaigns while reviewing high-spend campaigns with unclear recorded outcomes.
- Investigate product pricing, shipping transparency, availability, and international shipping costs where checkout gaps are largest.
- Improve future attribution tracking so marketing spend can eventually be connected more directly to orders and revenue.

## Dashboard Features

The interactive dashboard includes:

- KPI summary cards
- Product revenue leaderboard
- Revenue distribution
- Average Selling Price analysis with catalog benchmark
- Cumulative revenue concentration / Pareto analysis
- Marketing traffic mix
- Channel conversion comparison
- Meta campaign performance table
- Campaign engagement vs. cost-efficiency analysis
- Meta ad spend by campaign
- Product checkout outcome analysis
- Average shipping cost by billing country
- Checkout volume and percentage by billing country
- Q4 recommendations

## Technologies Used

- HTML
- CSS
- JavaScript
- Chart.js
- Tailwind CSS

## Repository Structure

```text
breaking-games-dashboard/
│
├── index.html
└── README.md
