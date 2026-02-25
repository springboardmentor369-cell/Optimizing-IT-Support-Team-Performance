# Optimizing IT Support Team Performance Using Analytics

## Project Overview
This project analyzes IT support ticket data to evaluate team performance, identify operational inefficiencies, and generate actionable insights.  
The analysis focuses on transforming raw ticket data into meaningful metrics and interactive dashboards that support data-driven decision-making in IT support operations.

The final output is a **Power BI dashboard** designed for both **executive monitoring** and **operational analysis**.

---

## Problem Statement
IT support teams handle a high volume of tickets with varying priorities, issue categories, and response expectations.  
Without proper analytical visibility, organizations often face:

- Delayed resolution of critical tickets
- SLA breaches
- Repeated or recurring issues
- Uneven workload across regions
- Reduced customer satisfaction

This project aims to address these challenges using analytics and visualization.

---

## Dataset Overview

- **Format:** JSON (converted to tabular format)
- **Type:** Structured data
- **Records:** 50 IT support tickets
- **Granularity:** One row per ticket
- **Nature:** Synthetic dataset (ITSM-style)

Each record represents a single IT support ticket.

---

## Dataset Fields

| Column Name | Description |
|------------|------------|
| `ticket_id` | Unique identifier for each ticket |
| `category` | Issue type (Server Down, Login Issue, Security Alert, Integration Bug) |
| `country` | Country where the ticket was raised |
| `created_at` | Ticket creation date |
| `priority` | Ticket urgency (low, normal, high, urgent) |
| `status` | Ticket status (open, pending, solved) |
| `resolution_time` | Time taken to resolve the ticket (hours) |

---

## Key Dimensions
- **Category:** Server Down, Login Issue, Security Alert, Integration Bug
- **Priority:** Low, Normal, High, Urgent
- **Status:** Open, Pending, Solved
- **Country:** India, USA, UK, Germany
- **Time:** Ticket creation date

---

## Key Performance Indicators (KPIs)

The following KPIs were calculated using Power BI (DAX):

- Total Tickets
- Open Tickets
- Pending Tickets
- Solved Tickets
- Average Resolution Time
- High & Urgent Open Tickets
- SLA Breach Tickets
- Tickets by Category
- Tickets by Country
- Tickets by Priority and Status

---

## Power BI Dashboards

### Dashboard 1: IT Support Performance Overview
**Purpose:** High-level view for management.

**Includes:**
- KPI cards (Total, Open, Pending, Solved, Avg Resolution Time)
- Monthly ticket trend
- Ticket distribution by priority and status
- Tickets by category
- Tickets by country
- Ticket status distribution

---

### Dashboard 2: IT Support Operational Analysis
**Purpose:** Action-focused dashboard for support managers.

**Includes:**
- SLA breach ticket count
- High & urgent open ticket count
- High & urgent tickets by category
- SLA breach tickets by category
- Average resolution time by priority
- High & urgent tickets by country
- Interactive slicers (Country, Month, Priority, Category)

---

## Key Insights
- High and urgent tickets contribute most to operational risk.
- Integration bugs and server issues are frequent problem categories.
- SLA breaches are concentrated in specific issue types.
- Resolution time varies significantly by priority.
- Ticket volume differs by country, indicating resource imbalance.

---

## Recommendations
- Prioritize high and urgent tickets to reduce SLA breaches.
- Address recurring issue categories through root-cause analysis.
- Improve workload distribution across regions.
- Monitor resolution time continuously.
- Use dashboards proactively to manage IT support operations.

---

## Tools & Technologies

### Tools
- Power BI Desktop

### Technologies
- Power BI
- DAX

---

## Notes
- This dataset is synthetic and created for learning and demonstration purposes.
- The structure closely resembles real IT Service Management (ITSM) data.
- No sensitive or real customer data is used.

---

## Conclusion
This project demonstrates how analytics and visualization can be used to optimize IT support team performance, reduce operational risk, and enable better decision-making.
