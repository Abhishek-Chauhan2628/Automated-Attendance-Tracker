# Automated-Attendance-Tracker

📊 Automated Attendance Tracker & Dashboard (2025)
An end-to-end automated solution for tracking employee attendance, calculating payroll deductions, and visualizing performance insights. This project utilizes Excel for data management and Power BI for advanced interactive reporting.

🚀 Key Features
📅 Excel: Data Management & Automation
Dynamic Monthly Sheets: 12 individual month tabs (Jan–Dec) with automated date generation and weekend (Sunday) highlighting [07:07].

Attendance Tracking: Supports codes for Present (P), Absent (A), and Leave (L) with conditional formatting for high visibility [48:43].

Automated Payroll Calculation: Calculates Total Paid Days, Per-Day Salary, and Salary Deductions based on absence records [51:20].

Power Query Integration: Consolidates 12 monthly reports into a single Yearly Report automatically, eliminating manual copy-pasting [02:00:42].

📉 Power BI: Interactive Dashboard
Employee Performance Score: A custom-calculated "Performance %" metric using DAX/Power Query [02:31:20].

Interactive Slicers: Filter the entire dashboard by Employee ID or Month to see specific trends [02:25:25].

KPI Cards: Instant visibility into Total Present, Absent, Leaves, and Year-to-Date Salary [02:22:55].

Visual Analytics: * Clustered Column Chart: Comparing attendance types across months.

Funnel Chart: Visualizing salary flow from basic to net pay after deductions [02:21:16].

Gauge Chart: Real-time tracking of employee performance ratings [02:33:04].

🛠️ Tech Stack
Microsoft Excel: Data Entry, Conditional Formatting, Data Validation.

Power Query: Data Transformation and Table Merging.

Power BI Desktop: Data Modeling and Visualization.

FlatIcon: Custom UI icons for professional aesthetics.

📂 Project Structure
Attendance_Tracker_Source.xlsx: The main data entry file with monthly tabs.

Yearly_Consolidated_Report.xlsx: The Power Query output file.

Attendance_Analytics_Dashboard.pbix: The Power BI project file.

🔄 How it Works
Input: Enter daily attendance (P/A/L) in the Excel monthly sheets.

Transform: Open the Yearly Report and click Data > Refresh All to pull in the latest changes via Power Query [02:05:33].

Visualize: Open the Power BI dashboard and click Refresh to see updated employee insights and payroll metrics [03:26:30].
