Global Airbnb Performance Dashboard

1.) Short Description / Purpose.
An interactive Power BI dashboard analyzing Airbnb performance across 10 global cities, covering 279,712 listings and 5.3M+ reviews. Built to uncover trends in listing growth, host trust, seasonal demand, pricing, and guest satisfaction — helping hosts, analysts, and stakeholders make data-driven decisions.

2.) Tech Stack
- Power BI Desktop — Main data visualization and report creation platform
- DAX (Data Analysis Expressions)** — Used for calculated measures, KPIs, and dynamic visuals
- Power Query — Data transformation and cleaning layer for reshaping raw data
- Data Modeling — Relationships established among tables to enable cross-filtering and aggregation
- File Format — .pbix for development and .png for dashboard previews

3.) Data Source
Source: Maven Analytics

4.) Features & Highlights
Business Problem:
Airbnb hosts and market analysts lack a unified view of how listings perform across different global cities — making it difficult to benchmark pricing, trust signals, seasonal demand, and guest satisfaction.

Goal of the Dashboard:
To build a multi-page, interactive Power BI report that enables users to explore Airbnb performance across 10 cities through dynamic visuals, bookmarks, and drill-through capabilities.

Key Visuals & Pages:
- Overview Page— KPI cards (279K listings, 182K hosts, 5.3M reviews), new listing growth lifecycle from 2008–2021 segmented by property type, and market share by city with Superhost distribution
- Reviews Page — Review frequency analysis showing 86.5% of guests review only once, seasonal % of monthly reviews by city, and host trust signals (identity verification vs profile picture)
- Ratings Page — Switchable between Overall Rating (bar chart) and Detailed Rating (matrix with Accuracy, Cleanliness, Communication, Location, Value) using bookmarks for a seamless toggle experience

Business Insights:
- Paris dominates with the most listings and reviews — driven by hotel room prices being nearly twice the Airbnb average
- Mexico City and Rio de Janeiro are the highest-rated cities; Hong Kong and Istanbul rank lowest
- October is the peak review month globally, signaling an autumn travel surge across all cities
- Over 66.9% of hosts are identity-verified with a profile picture, building platform-wide trust

Screenshots

Overview:
![Overview](https://github.com/2209Shubham/Airbnb-Dashboard/blob/main/Airbnb_Overview.png)

Overall Ratings:
![Overall Ratings](https://github.com/2209Shubham/Airbnb-Dashboard/blob/main/Airbnb_Overall_rating.png)

Detailed Ratings:
![Detailed Ratings](https://github.com/2209Shubham/Airbnb-Dashboard/blob/main/Airbnb_Detailed_rating.png)

Reviews:
![Reviews](https://github.com/2209Shubham/Airbnb-Dashboard/blob/main/Airbnb_Reviews.png)
