# HR Analytics Dashboard

## Project Overview
An interactive Power BI dashboard created to analyze employee attrition, workforce demographics, and compensation metrics across departments—tracking 1470 total employees, 237 exits (16.12% attrition rate), and average tenure of 7.0 years.

---

## Short Description
This report provides HR leadership with a centralized view to monitor workforce retention, identify high-turnover job roles and age groups, analyze attrition by salary brackets, and support data-driven retention strategies.

---

## Tech Stack
* Power BI Desktop: Core platform used for dashboard layout design, dynamic visuals, and interactive reporting.
* Power Query: Utilized for data cleaning, transforming raw HR datasets, and shaping attributes.
* Calculated Measures: Applied basic DAX formulas to calculate key metrics (Total Employees, Attrition Count, Attrition Rate %, Avg Age, Avg Salary).
* Data Architecture: Single-table transactional data model focused on clean layout structure and smooth usability.

---

## Data Source
* Source: HR Employee Attrition Dataset
* Format: CSV (.csv)
* Key Attributes: Employee ID, Age, Gender, Department, Job Role, Education Field, Monthly Income, Years at Company, Job Satisfaction, Attrition Status.

---

## Features & Highlights

### Business Problems
HR departments face difficulties in pinpointing why employees leave the company and which specific demographics or roles are at high turnover risk. Key questions addressed:
* Which job roles and age groups suffer from the highest attrition rates?
* Is low salary or lower compensation directly correlated with employee exits?
* Which education backgrounds represent the largest share of departing employees?
* How does employee attrition vary across department slicers (HR, R&D, Sales)?

---

### Walkthrough of Key Visuals
* **Top KPI Cards:** Instant visibility into Employees (**1470**), Attrition (**237**), Attrition Rate (**16.12%**), Avg Age (**37**), Avg Salary (**$6.5K**), and Avg Tenure (**7.0 Yrs**).
* **Filters & Slicers:** Top interactive filters for **Human Resources**, **Research & Development**, and **Sales**.
* **Demographics & Education Charts:** Donut and bar visuals mapping attrition across Education Fields, Age Groups (**25–35** risk segment), and Gender.
* **Role & Salary Breakdown:** Horizontal bar charts isolating high-exit Job Roles (Laboratory Technicians, Sales Executives) and Salary Slabs.

---

## How to Use

1. Download the `.pbix` (Power BI file) and the dataset file from this repository.
2. Open the `.pbix` file in Microsoft Power BI Desktop.
3. Reconnect the dataset source locally if prompted to load the interactive dashboard properly.
4. Check out the `Snapshot of the Dashboard.png` file for a quick preview of the final design!

---

### Key Business Insights
* **Salary Bracket Risk:** Employees in the **Upto $5K monthly income bracket** drive the majority of exits (**163 out of 237 total exits**), showing a clear link between entry-level pay and attrition.
* **Early Tenure Attrition:** Turnover peaks heavily within the **first year of service (59 exits)**, suggesting a need for better onboarding and early employee engagement.
* **Critical Job Roles:** **Laboratory Technicians (62 exits)** and **Sales Executives (57 exits)** represent high-attrition roles requiring targeted HR intervention.
* **Age Risk Factor:** Young professionals aged **25–35 (116 exits)** account for nearly 49% of all exits, highlighting mid-career retention challenges.

---

## Dashboard Preview
![HR-Analytics-Dashboard](Snapshot%20of%20the%20Dashboard.png)

---

## Author

**Divyani Tiwari** | B.Sc. Computer Science & Mathematics Student | Aspiring Data Analyst
