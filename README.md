🏠 Airbnb Performance Dashboard – Power BI
📌 Project Overview

This project analyzes Airbnb listing performance across 10 major global cities using Power BI.

The objective was to:

Identify market concentration by city

Analyze listing growth across lifecycle stages

Compare pricing across property types

Evaluate city-wise ratings and review performance

Measure cumulative market share contribution

The dashboard transforms raw listing data into structured business insights using data modeling and advanced DAX measures.

📊 Key Metrics (From Dashboard)

280K+ Listings

10 Cities

182K+ Hosts

144 Property Types

5.37M+ Reviews

🏗 Data Modeling

Implemented structured relationships between listings, cities, hosts, and property types

Applied ranking logic using DAX

Designed cumulative measures for market share analysis

Used filter context properly for dynamic visuals

📈 Advanced DAX Measures Implemented
1️⃣ Total Listings

Used for KPI cards and ranking logic.

2️⃣ City Ranking (Based on Total Listings)

Used RANKX() to dynamically rank cities by listing count.

3️⃣ Cumulative Listings

Calculated running total based on ranked cities to understand market concentration.

4️⃣ Cumulative %

Measured each city’s contribution to total listings using:

CALCULATE()

FILTER()

ALL()

DIVIDE()

This allowed Pareto-style analysis of market dominance.

📊 Dashboard Pages Breakdown
🔹 1. Listing Growth Lifecycle Analysis

Visualized listing trends across stages:

Introduction (2008–2010)

Growth (2011–2013)

Maturity (2014–2016)

Decline (2017–2018)

Reinvention

COVID-19 Impact

📌 Insight:

2015 recorded peak new listings.

2016–2017 saw regulatory impact.

2019 growth slowed due to COVID-19.

🔹 2. Market Share by City

Paris, New York, and Sydney account for nearly half of total listings.

Cumulative % visualization shows market concentration.

Superhost vs Non-superhost comparison included.

📌 Insight:
Top 3 cities dominate overall supply and review count.

🔹 3. Pricing Analysis by Property Type

Average price comparison:

Hotel Room – Highest avg price

Entire Place

Shared Room

Private Room

📌 Insight:
Hotel rooms are priced significantly higher, impacting revenue concentration.

🔹 4. Ratings & Quality Analysis

Heatmap and ranking of cities across:

Accuracy

Communication

Cleanliness

Location

Avg Review Score

📌 Insight:

Mexico City and Rio show highest overall ratings.

Cleanliness and value-for-money score relatively lower across cities.

🎯 Business Questions Answered

Which cities dominate Airbnb supply?

What % of listings are concentrated in top markets?

How has Airbnb evolved over time?

Which property type drives premium pricing?

Which cities offer the best guest experience?

💡 Business Value

This dashboard can help:

Investors identify high-concentration markets

Hosts benchmark pricing and ratings

Analysts study supply dominance patterns

Hospitality businesses evaluate competitive positioning

🛠 Skills Demonstrated

Advanced DAX (RANKX, CALCULATE, FILTER, ALL, DIVIDE)

Cumulative & Pareto Analysis

Data Modeling (relationship optimization)

KPI Design

Business Insight Storytelling

Dashboard UX Structuring
