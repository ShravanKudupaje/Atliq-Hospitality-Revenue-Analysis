**Atliq Hospitality Revenue Analysis**
End-to-end revenue analytics project for the hospitality domain using SQL, Excel, and Power BI, focused on hotel performance, pricing intelligence, and week-on-week trend analysis.

**📌 Overview**
This project simulates a real-world Revenue Analyst / Revenue Management engagement for Atliq Hospitality, a multi-city luxury and business hotel chain in India.

The objective is to analyze historical booking and property data, create industry-standard hospitality KPIs, and deliver a decision-ready Power BI dashboard for Revenue Managers and the Head of Revenue.

The project follows a full analytics lifecycle:
   - Raw data understanding
   - Metric engineering
   - SQL validation
   - Excel transformations
   - Interactive BI dashboarding
   - Business-driven insights & recommendations

**This project demonstrates:**
   - Revenue analytics & hospitality domain knowledge
   - KPI design and metric standardization
   - SQL querying & validation logic
   - Excel (Power Query, Pivot Tables, formulas)
   - Power BI dashboarding & storytelling
   - Business decision support thinking

**Business Context**

**Client (Simulated):** Atliq Hospitality

**Domain:** Hospitality

**Function:** Revenue Management

Atliq Hospitality owns multiple five-star hotels across major Indian cities. Due to increasing competition and sub-optimal pricing and capacity decisions, the company has experienced declining market share and revenue in the luxury and business hotel segment.

The leadership team decided to adopt Business Intelligence & Data-Driven Revenue Management practices and engaged a third-party analytics provider (this project) to:

   - Standardize revenue KPIs
   - Track performance across properties, cities, room classes, and channels
   - Enable pricing, occupancy, and capacity optimization

**🎯 Project Objectives**
1. Create all hospitality KPIs as defined in the official metric list
2. Build a Power BI dashboard aligned with stakeholder mock-ups
3. Generate additional revenue insights beyond the predefined metrics
4. Enable trend analysis, filters, and drill-downs for revenue decisions

**📂 Dataset**
_Source: Codebasics (Hospitality Revenue Case Study)_

**Data Files Used (CSV / Excel):**
   - dim_hotels – Property master data (hotel, city, category)
   - dim_rooms – Room types and room classes
   - fact_bookings – Detailed booking transactions
   - fact_aggregated_bookings – Aggregated booking metrics
   - dim_date – Date, week, month, and weekday/weekend mapping
   - metrics_list – Definition of hospitality KPIs
   - 
**Data Coverage Includes:**
   - Property-level performance
   - Room classes and room categories
   - Booking platforms / channels
   - Ratings, cancellations, realization
   - Time-based trends (day, week, month)

**🛠️ Tech Stack**
**Data Analysis & Transformation**
1. SQL (for metric logic, joins, validation)
2. Excel
   - Power Query
   - Pivot Tables
   - Advanced formulas
3. Business Intelligence
   - Power BI (Interactive dashboard & visuals)
4. Version Control
   - Git & GitHub

**📐 Key KPIs & Metrics Analyzed**
1. Core Revenue & Capacity Metrics
   - Total Bookings
   - Total Capacity
   - Total Successful Bookings
   - Occupancy % 
   - Average Rating
   - Number of Days
2. Revenue Performance Metrics
   - ADR (Average Daily Rate)
   - Realisation %
   - RevPAR (Revenue per Available Room)
3. Room Night Metrics
   - DBRN – Daily Booked Room Nights
   - DSRN – Daily Sellable Room Nights
   - DURN – Daily Utilized Room Nights
4. Trend & Change Metrics (WoW)
   - Revenue WoW Change %
   - Occupancy WoW Change %
   - ADR WoW Change %
   - RevPAR WoW Change %
   - Realisation WoW Change %
   - DSRN WoW Change %
5. Segmentation Metrics
   - Booking % by Room Class
   - Revenue by Category (Luxury vs Business)
   - Platform-wise revenue split

**🔍 Business Questions Answered**
This dashboard is designed to help Revenue Managers answer questions such as:
1. How can all live KPIs be monitored with week-on-week change visibility?
2. How do weekday vs weekend trends differ for:
   - RevPAR
   - Occupancy %
   - ADR
   - Realisation %
3. Which cities, properties, and room classes drive the highest revenue and margins?
4. How does performance vary by:
   - City / State / Country
   - Room type, room class, price band
5. How does revenue split across booking platforms / channels?
6. How should pricing strategies vary across:
   - Weekdays vs weekends
   - Dynamic vs flat pricing
   - High-demand vs low-demand periods
7. How does pricing influence:
   - Occupancy
   - Revenue realization
   - Overall revenue efficiency
8. How can the Pareto Principle (80/20) be used to identify:
   - Low-performing properties
   - High-impact improvement opportunities
9. How to apply differential pricing and discounts across channels without brand dilution?

**📊 Power BI Dashboard** <img width="1488" height="817" alt="image" src="https://github.com/user-attachments/assets/61757959-3be4-4855-8f0f-86aed6e97dd6" />


 - Executive KPI cards with WoW indicators
 - Revenue, RevPAR, ADR, and Occupancy trend analysis
 - Property-level performance comparison
 - Platform-wise realization & ADR analysis
 - Interactive slicers for:
    - City
    - Room Class
    - Booking Platform
    - Time (Week / Month)

**📈 Key Insights**
- ADR and Occupany are in directly proportional
- Dynamic pricing exits nill with Atliq hospitality which must be bought in place instant to increase ADR and overall revenue as well 
- Weekend performance consistently shows higher ADR and RevPAR compared to weekdays
- A small set of properties contributes to a disproportionate share of total revenue (Pareto effect)
- Certain booking platforms show high bookings but lower realization %, indicating discount leakage
- Occupancy and ADR move inversely in select cities, highlighting pricing elasticity opportunities
- Underperforming properties can be uplifted through targeted pricing and channel mix optimization

📌 Outcome
**This project delivers a production-ready hospitality revenue dashboard that enables:**

- Faster pricing decisions
- Clear performance monitoring
- Property-level accountability
- Data-driven revenue optimization

It reflects the real responsibilities of a Revenue Analyst / Business Analyst in the hospitality industry.
