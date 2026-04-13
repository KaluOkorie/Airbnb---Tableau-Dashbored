# Airbnb - Tableau Dashboard

An end-to-end Tableau analytics project that transforms Airbnb listing data into an interactive storytelling dashboard for business and operational decision-making.

## Overview

This project analyzes Airbnb market behavior across neighbourhoods, room types, pricing, bookings, and review trends. The dashboard is designed to answer high-impact business questions quickly using interactive filters, custom KPIs, and visual storytelling.

It combines map views, bar charts, trend visuals, and a custom doughnut-style chart built in Tableau (non-native default approach) to make insights clear for both technical and non-technical audiences.

## Objective

Build a recruiter-grade, interactive dashboard that helps stakeholders:

- Understand demand distribution across neighbourhoods and neighbourhood groups
- Compare booking and review performance over time
- Evaluate pricing differences by room type and location
- Identify top hosts and high-performing areas
- Support revenue, supply, and customer-experience decisions with data

## Statement of the Problem

Airbnb-style marketplace data is high-volume and multi-dimensional. Without a well-designed dashboard, business users struggle to answer key questions around demand, host performance, and pricing strategy.

The core problem solved by this project is:

**How do we convert raw listing-level Airbnb data into a clear, interactive, and decision-ready analytics experience for location strategy, pricing intelligence, and host performance monitoring?**

## Dataset

Source file used in this repository:

- `Inputs/AB_NYC_2019.csv`

Dataset profile:

- Rows: **49,080** data records (49,081 including header)
- Columns: **16 fields**
- Domain: NYC Airbnb listings (location, host, room type, pricing, reviews, availability)

## Tech Steps to Build This Project

### 1. Data Ingestion and Profiling

- Imported Airbnb dataset into Tableau
- Validated field types (dimensions vs measures)
- Checked schema consistency for location, pricing, and review fields

### 2. Data Cleaning Steps

- Removed/handled null or incomplete values in critical fields (e.g., review/date-based attributes)
- Standardized categorical values for `room_type`, `neighbourhood_group`, and `neighbourhood`
- Ensured numeric fields (price, reviews, availability) were correctly typed for aggregations
- Prepared date-level structure for yearly trend analysis

### 3. Data Modeling in Tableau

- Built calculated fields to create custom measures and KPI cards
- Applied groups for improved segment-level analysis
- Configured interactive filter actions across worksheets
- Added hierarchy-driven exploration paths for deeper location analysis

### 4. Dashboard Design and Storytelling

- Designed a clean dashboard layout with branding (including dashboard logo)
- Selected relevant chart types based on analytical intent
- Built a **custom doughnut chart** approach not available as a direct default chart type in Tableau
- Integrated storytelling flow so users can move from summary KPIs to detailed breakdowns

### 5. Publishing and Delivery

- Published dashboard to Tableau Public
- Exported workbook assets (`.twb`, `.twbx`) and screenshot for portfolio use

## Questions Answered by the Dashboard

The dashboard is built to answer:

- **Total Booking per Month by Neighbourhood - Room Type: `<Room Type>`**
- **Total Neighbourhoods by Neighbourhood Group**
- **Top 10 Host by Total Reviews**
- **Total Bookings by Neighbourhood Group and Room Type**
- **Total Review by Year**
- **Average Price by Neighbourhood - Roomtype: `<Room Type>`**
- **Average price by Neighbourhood: Neighbourhood Group: `<Neighbourhood Group>`**
- **Average Reviews per month, by Room type and neighbourhood group**

## Key Insights (What Stakeholders Can Learn)

- Demand concentration varies significantly by neighbourhood group and room type
- Review activity highlights quality/engagement differences across hosts and locations
- Pricing differs materially by neighbourhood and listing segment, informing dynamic pricing strategy
- Top-host concentration reveals where supply and guest trust may be clustered
- Monthly and yearly patterns support seasonal planning and operational forecasting

## Business Recommendations

- Prioritize supply expansion in high-demand neighbourhood/room-type combinations
- Use neighbourhood-level pricing benchmarks to tune listing strategy
- Build host enablement programs for mid-tier hosts to improve review performance
- Plan promotions around high-performing months and neighbourhood clusters
- Monitor low-performing segments with targeted interventions (pricing, availability, listing quality)

## Tools Used

- Tableau Public/Desktop
- Microsoft Excel (data review and supporting checks)
- CSV data processing workflow

## Tableau Public Link

- https://public.tableau.com/views/Airbnb-TableauDashbored/Dashboard1?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Screenshots

Dashboard snapshot available in this repository:

- `outputs/Airbnb - Tableau Dashbored.png`

![Airbnb Tableau Dashboard](https://raw.githubusercontent.com/KaluOkorie/Airbnb---Tableau-Dashbored/master/outputs/airbnb-dashboard.png)

## Project Value

This project demonstrates practical strengths in:

- Business Intelligence and dashboard engineering
- Data storytelling for non-technical stakeholders
- Advanced Tableau design (calculated fields, groups, custom chart patterns)
- KPI-driven analytics and decision support
- Portfolio-ready publishing and communication

## CTA

I am open to opportunities where I can:

- Build high-impact analytical dashboards
- Translate business questions into measurable insights
- Support decision-making with clear, story-driven visuals

Let’s connect and collaborate.
