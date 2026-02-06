# Automated-Attendance-Tracker

📊 Automated Attendance Tracker & Dashboard (2025)
An end-to-end automated solution for tracking employee attendance, calculating payroll deductions, and visualizing performance insights. This project utilizes Excel for data management and Power BI for advanced interactive reporting.

## 🚀 Key Features
📅 Excel: Data Management & Automation
Dynamic Monthly Sheets: 12 individual month tabs (Jan–Dec) with automated date generation and weekend (Sunday) highlighting.

Attendance Tracking: Supports codes for Present (P), Absent (A), and Leave (L) with conditional formatting for high visibility.

Automated Payroll Calculation: Calculates Total Paid Days, Per-Day Salary, and Salary Deductions based on absence records.

Power Query Integration: Consolidates 12 monthly reports into a single Yearly Report automatically, eliminating manual copy-pasting.

## 📉 Power BI: Interactive Dashboard
Employee Performance Score: A custom-calculated "Performance %" metric using DAX/Power Query.

Interactive Slicers: Filter the entire dashboard by Employee ID or Month to see specific trends.

KPI Cards: Instant visibility into Total Present, Absent, Leaves, and Year-to-Date Salary.

Visual Analytics: * Clustered Column Chart: Comparing attendance types across months.

Funnel Chart: Visualizing salary flow from basic to net pay after deductions.

Gauge Chart: Real-time tracking of employee performance ratings.

![Dashboard Screenshot](https://github.com/Abhishek-Chauhan2628/Automated-Attendance-Tracker/blob/bc5018d02a9b6cc4fe0ae3bcd61fab219c8f35cd/Screenshot%202026-02-06%20212159.png)

## 🛠️ Tech Stack
Microsoft Excel: Data Entry, Conditional Formatting, Data Validation.

Power Query: Data Transformation and Table Merging.

Power BI Desktop: Data Modeling and Visualization.

## 📂 Project Structure
Attendance_Tracker_Source.xlsx: The main data entry file with monthly tabs.

Yearly_Consolidated_Report.xlsx: The Power Query output file.

Attendance_Analytics_Dashboard.pbix: The Power BI project file.

## 🔄 How it Works
Input: Enter daily attendance (P/A/L) in the Excel monthly sheets.

Transform: Open the Yearly Report and click Data > Refresh All to pull in the latest changes via Power Query.

Visualize: Open the Power BI dashboard and click Refresh to see updated employee insights and payroll metrics.
