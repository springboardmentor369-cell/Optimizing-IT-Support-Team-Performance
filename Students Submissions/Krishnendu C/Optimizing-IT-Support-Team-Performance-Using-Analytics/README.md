# Optimizing IT Support Team Performance Using Adavanced Analytics

This project focuses on analyzing IT support ticket data to identify performance bottlenecks, measure efficiency using key metrics, and provide data-driven insights that help improve response times, resolution rates, and overall service quality.

---

## 📌 PROBLEM STATEMENT

IT support teams handle a large volume of service tickets daily. Delays in resolution, poor prioritization, and inefficient workload distribution can negatively impact user satisfaction and operational efficiency.

---

## 📂 DATASET DESCRIPTION 
### 🔗 Data Source 

#### Python Cleaning (Static Dataset) : [Kaggle – Technical Support Dataset](https://www.kaggle.com/datasets/suvroo/technical-support-dataset)
#### PowerBI Dashboard (Live API Data): [Live Ticket API Endpoint](https://mock-api-srm8.onrender.com/api/tickets)

#### Note: A static CSV dataset was used for data cleaning and preprocessing in Python, while a live REST API was used in Power BI to simulate real-time ticket monitoring.  


### 📄 Python Dataset (Data Cleaning & Preprocessing)
Number of rows: 50  
Number of columns: 2330  
Each row of the dataset represents one support ticket. 

The dataset includes the information regarding:
 - Source and Status of the ticket  
 - Geographic information  
 - Agent group and agent name handling the ticket  
 - Expected SLA to resolve,SLA for resolution and for first response  
 - First response time and SLA for first respnse  
 - Priority and topic,product group of the ticket  
 - Creation and resolution time  
 - Agent interactions and survey results  
 - Support level,latitude and longitude of the ticket  
   
#### 🧱 Key Columns 
Status – Current state (Open, Closed, Resolved, etc.)  
Priority – Urgency level of the ticket  
Source – Channel through which the ticket was raised  
Topic – Issue classification  
Created time – When the ticket was created  
First response time – Time taken for initial response  
Resolution time – Total time taken to resolve the issue  
Expected SLA to first response – Target time for first response  
Expected SLA to resolve – Target resolution time  
SLA For first response – Whether first response SLA was met  
SLA For Resolution – Whether resolution SLA was met  
Close time – Final closure timestamp  

### 📄 Power BI Dataset (Live Dashboard Data)
Number of rows: 50  
Number of columns: 7  
Each row of the dataset represents one support ticket. 

The dataset includes the information regarding:
 - Status of the ticket
 - Geographic information
 - Priority and Category of the ticket
 - Creation and resolution time
   
#### 🧱 Key Columns 
Status - Current state of the ticket  
Priority - Urgency level of the ticket   
Created At - Timestamp when the ticket was created  
Resolution Time	- Hours it took to solve the issue  
Category - Service related to the issue  
Country - Country from which the ticket was raised

---

## 📈 KPIs USED FOR THE DASHBOARD
Total Tickets  
Average Resolution Time  
Closed Tickets  
SLA Violated %  
Average Resolution Time by Priority  
SLA Violation % by Country & Category
Ticket Distribution by Country  
Tickets By Day of Week  
Ticket Status Distribution  

---

## 👩🏻‍💻 DASHBOARD  

### 1. IT SUPPORT OPERATIONS MONITORING & SLA PERFORMANCE OPTIMIZATION  

  - #### Purpose:
  - To evaluate IT support team performance by analyzing ticket volume,resolution efficiency,SLA Compliance,prioritization effectiveness and geographic distribution of tickets and ticket statuses.  
  - #### Includes:
  - Total Tickets (Workload Indicator)
  - Closed Tickets (Productivity Indicator)
  - SLA Violation % (Compliance Indicator)
  - Average Resolution Time (Efficiency Indicator)
  - Tickets by Day of Week (Workload Pattern)
  - Average Resolution Time by Priority (Prioritization Effectiveness)
  - SLA Violation by Country & Category (Risk Concentration Analysis)
  - Ticket Distribution by Country (Geographic Load Analysis)
  - Ticket Status Distribution (Backlog Monitoring)

#### Helps to
- Support data-driven staffing and process optimization decisions
- Identify operational issues
- Detect SLA risk areas

---

## 🔍 KEY INSIGHTS 
- SLA Risk Compliance is high - 36% of tickets violated SLA
- High Priority Tickets Take the Longest to Resolve
- Low Priority Tickets Are Resolved Fastest
- SLA Violations Are Concentrated in Specific Countries
- Security Alerts & Specific Categories Show Higher Risk
- Workload Peaks on Friday
- Only 23 Out of 50 Tickets Closed - less than 50%
---

## 💡 RECOMMENDATIONS 
Strengthen SLA Compliance Monitoring  
Improve Priority Handling Process  
Optimize High-Risk Categories  
Manage End-of-Week Workload Spike  
Improve Ticket Closing Rate

---

## 🛠 TOOLS USED 

  - Data Handling : Python (Pandas)
  - Data Visualization: Power BI
  - Documentation: Jupyter Notebook, GitHub Repository

---

## 📌 CONCLUSION 
This dashboard serves as an operational diagnostic framework for evaluating IT support performance using KPIs such as ticket volume, average resolution time, SLA violation rate, prioritization efficiency, and geographic workload distribution.

The analysis highlights structural inefficiencies in SLA compliance and priority-based resolution handling, suggesting that process-level optimization may yield greater impact than resource expansion alone.

