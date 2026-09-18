# HR Analytics Dashboard

## Project Overview

An interactive Power BI dashboard created to analyze employee attrition, workforce demographics, and compensation metrics across departments—tracking 1.47K total employees, 237 exits (16.12% attrition rate), and average tenure of 7.0 years.

---

## Short Description

This report provides HR leadership with a centralized view to monitor workforce retention, identify high-turnover job roles and age groups, analyze attrition by salary brackets, and make data-driven decisions to improve employee retention.

---

## Tech Stack

* Power BI Desktop: Core platform used for dashboard layout design, dynamic visuals, and interactive slicers.
* Power Query: Utilized for data cleaning, transforming HR datasets, and custom column creations.
* DAX (Data Analysis Expressions): Applied to build calculated measures for total employee count, attrition count, attrition rate %, average age, and average salary.

---

## Data Source

* Source: HR Employee Attrition Dataset
* Format: CSV (.csv)
* Key Attributes: Employee ID, Age, Gender, Department, Job Role, Education Field, Monthly Income, Years at Company, Job Satisfaction, and Attrition Status.

---

## Features & Highlights

### Business Problem

HR departments face difficulties in pinpointing why employees leave the company and which specific demographics or roles are at high turnover risk. Key questions addressed:

* Which job roles and age groups suffer from the highest attrition rates?
* Is low salary or lower compensation directly correlated with employee exits?
* Which education backgrounds represent the largest share of departing employees?
* How does employee attrition vary across department slicers (HR, R&D, Sales)?

---

### Goal of the Dashboard

* Monitor core workforce metrics using top KPI cards (**1.47K Employees, 237 Attrition, 16.12% Attrition Rate, 37 Avg Age, $6.5K Avg Salary, 7.0 Avg Years**).
* Isolate high-turnover job roles to implement targeted retention policies.
* Track attrition by salary slabs to optimize compensation structures.

---

### Walkthrough of Key Visuals

* Top KPI Summary Cards: Direct visibility into Count of Employee (**1.47K**), Attrition (**237**), Attrition Rate (**16.12%**), Avg Age (**37**), Avg Salary (**$6.5K**), and Avg Years (**7.0**).
* Department Slicers: Top interactive filters for **Human Resources**, **Research & Development**, and **Sales**.
* Attrition by Education (Donut Visual): Highlights **Life Sciences (38%)** and **Medical (27%)** as top education fields among exiting employees.
* Attrition by Age (Bar Chart): Shows the **25–35 age group (116 exits)** as the highest turnover risk segment, followed by **18–25 (44 exits)**.
* Attrition by Job Role (Horizontal Bar Visual): Pinpoints **Laboratory Technicians (62 exits)**, **Sales Executives (57 exits)**, and **Research Scientists (47 exits)** as high-attrition roles.
* Attrition by Salary (Horizontal Bar Visual): Indicates that employees earning **Upto $5K (163 exits)** account for the vast majority of total turnover.
* Attrition by Gender & Years: Tracks gender breakdown (**Male: 140, Female: 79**) and tenure patterns (**Peak exits occur at 1 year of service: 59 exits**).

---

## Key Business Insights

* Salary Bracket Risk: Employees in the **Upto $5K monthly income bracket** drive the majority of exits (**163 out of 237 total exits**), showing a clear link between entry-level pay and attrition.
* Early Tenure Attrition: Turnover peaks heavily within the **first year of service (59 exits)**, suggesting a need for better onboarding and early employee engagement.
* Critical Job Roles: **Laboratory Technicians (62)** and **Sales Executives (57)** require immediate HR intervention, career pathing, or workplace satisfaction reviews.
* Age Risk Factor: Young professionals aged **25–35 (116 exits)** represent nearly 49% of all exits, highlighting mid-career retention challenges.

---

## Dashboard Preview
![HR-Analytics-Dashboard] (Snapshot%20of%20the%20Dashboard.png)
