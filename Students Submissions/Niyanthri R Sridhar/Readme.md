# Optimizing-IT-Support-Team-Performance-Using-Analytics

## 📌Problem Statement
The objective of this project is to analyse IT support ticket data to identify key performance trends, optimise resolution times, and enhance service efficiency through data analysis and visualisation. The goal is to uncover patterns in customer requests, technical issues, and support performance metrics to recommend improvements in workflow and resource allocation.

## 📈Dataset Description
**Dataset:** Customer Support Ticket Dataset

**Source:** [API Key](https://mock-api-srm8.onrender.com/api/ticketsURL)

**Scale:** 7 rows and 50 columns

**Dataset Description:** The dataset includes customer support tickets. It consists of customer inquiries. 

**Feature Description:**
- Ticket ID: A unique identifier for each ticket.
- Category: The type of ticket.
- Country: Where is the ticket from?
- Date Created: The date the ticket was created.
- Ticket Priority: The priority level assigned to the ticket.
- Ticket Status: The status level assigned to the ticket.
- Time to Resolution: The time taken to resolve the ticket.

## 📊KPI Metrics
- Average Resolution Time: Measures efficiency against the 5-day SLA target.
- Primary Cost Driver: Identifies which ticket category consumes the most resources.
- Active Backlog: Tracks the total number of unresolved issues.
- Total Tickets: Number of tickets received.
- Critical Unresolved: Specifically tracks high-urgency issues currently in "Open" or "Pending" status.
- Oldest Open Ticket: Identifies the longest-standing unresolved request to mitigate stagnation risk.

## 📂Dashboard Details
The project utilises a two-tier interactive dashboard system to separate strategic oversight from tactical operations.

**Strategic Executive Oversight**
- Resolution Path Discovery
- Category Friction & Volume Matrix: Visualises the relationship between volume and complexity to identify high-cost pain points.
- High-Priority Distribution by Region
- Portfolio Composition

**Tactical Operations Centre**
- Ticket Ageing & Status Pipeline
- Daily Throughput

## 💡Key Insights
- Primary Bottleneck: "Server Down" were identified as the highest volume category and a major driver of resolution delays.
- Complexity Risk: "Server Down" issues, while lower in volume, consistently exceed target resolution times (Avg 6.13 days).
- Regional Hotspots: India and Europe were identified as regions with the highest concentration of critical unresolved tickets.

## 🚀Recommendation
- SLA Recovery Plan: Implement an "Express Lane" for tickets exceeding 4 days to lower the global average.
- Root Cause Analysis: Launch an R&D investigation into integration protocols to reduce the volume of recurring bugs.
- Resource Reallocation: Shift senior technical staff to the India and Germany regions to handle high-priority server and security events.

## 🛠️Tools Used
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PowerBI](https://img.shields.io/badge/PowerBI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
- Python(Pandas): Data manipulation library to load datasets, explore data schema and handle missing values.
- Power BI: A business tool used to clean data, build interactive dashboards and visualise performance trends.
- VS Code: Primary IDE used to write and debug Python scripts for cleaning, pre-processing, exploratory data analysis, visualising, and feature engineering.
- GitHub: A version control platform used to host the project's and final documentation.
