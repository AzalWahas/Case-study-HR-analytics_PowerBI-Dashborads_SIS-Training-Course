A comprehensive, multi-page Power BI workforce analytics solution designed to track employee metrics, demographic distributions, performance evaluations, and organizational attrition trends.

---

## 📂 Dashboard Pages & Structure

├── Overview Page            # High-level organizational headcount, hiring trends, and active departmental breakdowns
├── Demographics Page        # Employee age distribution, marital status splits, and ethnicity/salary profiles
├── Performance Tracker Page # Individual employee progression timelines, satisfaction scores, and rating histories
└── Attrition Page           # Turnover rates by tenure, department, travel frequency, and overtime status

---

## 📊 Detailed Page Breakdown

### 1. Overview Page
* **KPI Header Cards**: Displays total employees (1,470), inactive employees (237), active employees (1,233), and the overall company attrition rate (16%).
* **Employee Hiring Trend**: Multi-year column chart tracking hiring volume and status distribution from 2012 to 2022.
* **Active Employee by Department**: Decomposition tree visual outlining active staff breakdowns across Technology, Sales, and Human Resources down to individual job roles.

### 2. Demographics Page
* **Summary Cards**: Identifies workforce age extremes (Youngest employee at age 18, Oldest at age 51).
* **Marital Status Breakdown**: Donut chart segmenting total employees by Married (42.45%), Single (37.35%), and Divorced (20.20%).
* **Gender & Age Distribution**: Hierarchical decomposition tree mapping total employees by gender and age bins.
* **Ethnicity & Salary Analysis**: Combined column and line chart plotting total headcount alongside average salary tiers across various ethnic groups.

### 3. Performance Tracker Page
* **Employee Selector**: Interactive dropdown allowing deep-dives into individual staff records (e.g., Abra MacGray) with milestone dates (Hiring date, Last review date, Next review date).
* **Satisfaction Metrics**: Longitudinal line charts tracking multi-year scores across Job satisfaction, Relationship, Work-life balance, and Work environment.
* **Rating Metrics**: Historical performance trend lines evaluating Self-ratings and Manager ratings from 2014 to 2022 alongside reference level scales.

### 4. Attrition Page
* **Attrition by Department**: Doughnut visualization illustrating turnover distribution across Sales, Human Resources, and Technology sectors.
* **Attrition by Travel Frequency**: Comparative metrics analyzing departures across Non-Travel, Some Travel, and Frequent Traveller segments.
* **OverTime & Hire Date Impact**: Bar charts and trend lines highlighting elevated turnover risk among staff working overtime and across specific cohort hiring years.

---

## 🛠️ Global Filters & Navigation

* **Navigator Panel**: Quick-access button sidebar allowing seamless switching between Overview, Demographics, Performance Tracker, and Attrition views.
* **Global Filters**: Persistent slicers enabling real-time cross-filtering across the entire report by **Year**, **Department**, and **Gender**.

---

## 🚀 Getting Started

1. **Prerequisites**: Ensure you have **Power BI Desktop** installed.
2. **Open Project**: Open the corresponding `.pbix` report file to load the underlying data model and visual layouts.
3. **Explore**: Utilize the global filters on the left panel and switch between pages using the Navigator menu to interact with the workforce insights.
