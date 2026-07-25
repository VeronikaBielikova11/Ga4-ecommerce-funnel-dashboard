# GA4 Ecommerce Funnel Dashboard

## Overview

This project analyses user behaviour and ecommerce conversions using the Google Analytics 4 (GA4) public dataset from BigQuery.

The data was transformed with SQL to create a session-level dataset and visualised in an interactive Tableau dashboard. The dashboard enables marketing teams to monitor key ecommerce KPIs, analyse the conversion funnel, and explore performance across different traffic sources and user segments.

## Data Preparation

**Source:** Google Analytics 4 Public Ecommerce Dataset (BigQuery)

After executing the SQL query, a session-level table was created containing the following information:

- User and session identifiers
- Session date and timestamp
- Funnel event (Session Start → Purchase)
- Landing page
- Traffic source, medium and campaign
- Country
- Device category
- Device language
- Operating system

## Dashboard Features

- KPI cards (Visits, Orders, Conversion Rate)
- Ecommerce conversion funnel
- Sessions by device category
- Sessions by device language
- Sessions by country
- Operating system distribution
- Weekly conversion trend

## Interactive Filters

- Session date
- Landing page
- Source
- Medium
- Campaign
- Device category
- Device language
- Operating system

## Tech Stack

- BigQuery SQL
- Google Analytics 4
- Tableau Public

## Links

- **📊 Tableau Public:** [View Dashboard](https://public.tableau.com/views/E-commercePerfomance/E-commercePerfomance?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
- **💻 BigQuery:** [View SQL Query](https://console.cloud.google.com/bigquery?sq=88159869841:7a1847d64a31421b97d659d8d0964498)

## Dashboard Preview
<img width="1329" height="776" alt="Screenshot 2026-07-25 at 18 08 17" src="https://github.com/user-attachments/assets/33e1aaac-689c-463c-b222-7ea09123612c" />

