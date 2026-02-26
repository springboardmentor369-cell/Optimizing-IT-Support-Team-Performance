# ⚡ DAX Calculations – Customer Support Ticket Analysis

## 🧠 What is DAX?

**DAX (Data Analysis Expressions)** is the formula language used in Power BI to create intelligent calculations.

It transforms raw data into meaningful insights like:

* 📊 Total number of tickets
* 👥 Total customers
* ⭐ Customer satisfaction score
* ⏱️ Response and resolution efficiency

DAX acts as the **analytical brain of the dashboard**.

---

# 🧩 Types of DAX Used in This Project

There are two main types of DAX:

---

## 1️⃣ Implicit DAX (Automatic Calculations)

Implicit measures are automatically created by Power BI when aggregation is applied in visuals.

Example:

When you drag **Ticket Id** into a visual and select **Count**, Power BI automatically performs:

```
COUNT(Fact_Tickets[Ticket Id])
```

✔ No manual formula needed
✔ Used for quick analysis

---

## 2️⃣ Explicit DAX (Manual Calculations)

Explicit measures are manually written using DAX formulas.

Example:

```
Total Tickets = COUNT(Fact_Tickets[Ticket Id])
```

✔ More control
✔ Reusable
✔ Professional approach
✔ Industry standard

Explicit DAX was used throughout this project.

---

# 🧱 Base Measures (Foundation Measures)

Base measures are simple calculations created directly from dataset columns.

They form the **foundation of all advanced analytics**.

---

## 📊 Total Tickets

```
Total Tickets = COUNT(Fact_Tickets[Ticket Id])
```

**Purpose:**
Calculates total number of support tickets.

**Insight:**
Measures overall support workload.

---

## 👥 Total Customers

```
Total Customers = DISTINCTCOUNT(Fact_Tickets[Customer Email])
```

**Purpose:**
Counts unique customers.

**Insight:**
Measures customer reach and engagement.

---

## ⭐ Average Satisfaction

```
Avg Satisfaction = AVERAGE(Fact_Tickets[Customer Satisfaction Rating])
```

**Purpose:**
Measures customer happiness level.

**Insight:**
Evaluates service quality.

---

## ⏱️ Average Resolution Time

```
Avg Resolution Time = AVERAGE(Fact_Tickets[Resolution Time])
```

**Purpose:**
Measures issue resolution speed.

**Insight:**
Tracks support efficiency.

---

## ⚡ Average Response Time

```
Avg Response Time = AVERAGE(Fact_Tickets[Response Time])
```

**Purpose:**
Measures response speed.

**Insight:**
Evaluates support responsiveness.

---

# 🧮 Calculated Column

Calculated columns create new classifications inside the dataset.

---

## 🏷️ Resolution Status

```
Resolution Status =
IF(
ISBLANK(Fact_Tickets[Resolution]),
"Not Resolved",
"Resolved"
)
```

**Purpose:**
Categorizes tickets into Resolved and Not Resolved.

**Insight:**
Helps analyze resolution performance.

---

# 🧩 Composite Measure (Advanced Measure)

Composite measures use logic and filters.

---

## 🚨 High Priority Tickets

```
High Priority Tickets =
CALCULATE(
COUNT(Fact_Tickets[Ticket Id]),
Fact_Tickets[Ticket Priority] = "High"
)
```

**Purpose:**
Counts critical support tickets.

**Insight:**
Helps identify urgent support workload.

---

# 🎯 Why These DAX Measures Were Created

These measures help answer key business questions:

* 📊 How many tickets were raised?
* 👥 How many customers needed support?
* ⭐ Are customers satisfied?
* ⏱️ How fast are issues resolved?
* ⚡ How fast is the response?
* 🚨 How many high-priority issues exist?

These metrics are called **KPIs (Key Performance Indicators)**.

---

# 🏗️ DAX Architecture Used

```
Implicit DAX  → Automatic aggregation
Explicit DAX  → Manual calculations
Base Measures → Basic metrics
Composite Measures → Advanced metrics
Calculated Columns → Data classification
```

---

# 🚀 Impact of DAX in This Project

DAX enabled:

* 📊 KPI creation
* 📈 Performance tracking
* 🔎 Insight generation
* ⚡ Fast dashboard calculations
* 🧠 Intelligent analytics

---

# 🛠️ Tools Used

* Power BI Desktop
* DAX (Data Analysis Expressions)

---

# 🌟 Final Note

DAX transforms data into intelligence.
It converts raw customer support records into actionable business insights.

---

