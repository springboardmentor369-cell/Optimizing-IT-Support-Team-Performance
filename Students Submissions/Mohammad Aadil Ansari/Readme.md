Mohammad Aadil Ansari
Repository Link - https://github.com/mohammadaadill/Optimizing-IT-Support-Team-Performance-Using-Analytics
Supportlytics – IT Ticket Analysis Dashboard
📌 Problem Statement
The project analyzes IT support ticket data to uncover patterns in ticket distribution, user demographics, departmental workload, and satisfaction levels. The goal is to provide insights into how tickets are raised and handled across different dimensions of the organization.

📊 Dataset Description
Source: Kaggle IT Support Ticket dataset

Size: ~100K tickets, 967 users, 15 departments

Columns include:

Ticket_ID
Ticket_Type (Issue, Request)
Department
Job Classification (Blue Collar, White Collar, Other)
Requestor Seniority & Gender
Priority
Severity
Satisfaction
Group Assignment
Raw Data: Original Kaggle dataset

Processed Data: Cleaned dataset with duplicates removed, standardized categories, and structured fields for analysis

📈 KPIs Used
Total Tickets
Total Users
Total Departments
Ticket Type Distribution (Issue vs Request)
Tickets by Department
Tickets by Job Classification
Tickets by Requestor Seniority & Gender
Tickets by Groups (A–D)
Tickets by Satisfaction Levels
Tickets by Priority
Tickets by Severity
📊 Dashboards Used
Overview Metrics
KPIs: Total Tickets, Users, Departments
Ticket Type Distribution (Issue vs Request)
Demographics
Tickets by Gender
Tickets by Job Classification
Tickets by Requestor Seniority & Gender
Departmental Analysis
Ticket counts across 15 departments
Group Assignment
Tickets handled by Groups A–D
Satisfaction & Priority
Customer satisfaction levels
Ticket priority distribution
Severity Analysis
Normal, Major, Minor, Critical ticket breakdown
Why these visuals?

Cards: For headline KPIs (tickets, users, departments)
Pie Charts: For proportional distributions (gender, job classification, ticket type)
Bar Charts: For departmental workload, satisfaction, priority, severity
Stacked Bars: For seniority vs gender breakdown
🔑 Key Insights
Requests dominate over issues (75K vs 25K)
Workload is evenly spread across departments, but Finance and Tech Support have slightly higher ticket counts
Job classifications are balanced (blue collar, white collar, other ~33% each)
Satisfaction is high overall, but ~20K tickets have unknown feedback
Priority distribution shows a large share of unassigned tickets (~25K)
Severity is overwhelmingly “Normal” (91K), with very few critical cases
💡 Recommendations
Reduce unassigned priority tickets by enforcing stricter categorization
Improve feedback collection to reduce “Unknown” satisfaction cases
Investigate why Finance and Tech Support have slightly higher workloads
Focus on critical severity tickets to ensure faster resolution
🛠 Tools Used
Power Query (Power BI): Data cleaning (duplicates removed, categories standardized)
Power BI Desktop: Dashboard creation and visualization
GitHub: Documentation, version control, and project sharing
