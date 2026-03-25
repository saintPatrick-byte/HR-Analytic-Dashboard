# HR-Analytic-Dashboard
Checking the Attrition of an organization

This project demonstrates how to build an interactive HR Analytics Dashboard using Tableau. The dashboard provides insights into employee data, including attrition, demographics, job satisfaction, and departmental trends.

The goal is to help organizations make data-driven HR decisions by visualizing key workforce metrics.

Key Features of the Dashboard

The dashboard includes:

Employee Count – Total number of employees

Attrition Count & Rate – Number and percentage of employees who left

Active Employees – Current workforce size

Average Age – Workforce age insight

Attrition by Gender – Gender-based turnover comparison

Department-wise Attrition – Which departments are most affected

Age Group Distribution – Employee spread across age groups

Job Satisfaction Rating – Satisfaction levels by job roles

Education Field Analysis – Attrition trends by education background

Attrition by Age & Gender – Combined demographic insights



Tools & Technologies

Tableau Desktop / Tableau Public

CSV / Excel dataset

Basic data cleaning techniques

Step-by-Step Guide to Creating the Dashboard
1. Connect Data to Tableau

Open Tableau

Click Connect → Text File / Excel

Load your dataset

2. Create Calculated Fields

Create important metrics such as:

Attrition Count

IF [Attrition] = "Yes" THEN 1 ELSE 0 END

Attrition Rate

SUM([Attrition Count]) / COUNT([Employee ID])
3. Build Individual Visualizations
📌 KPI Cards

Use Text Marks

Display:

Employee Count

Attrition Count

Attrition Rate

Active Employees

Average Age

📌 Department-wise Attrition (Pie Chart)

Drag Department → Color

Drag Attrition Count → Angle

📌 Age Group Distribution (Bar Chart)

Create bins for Age

Use:

Age (Bins) → Columns

Employee Count → Rows

📌 Job Satisfaction (Table / Heatmap)

Rows → Job Role

Columns → Satisfaction Level

Values → Count of Employees

📌 Education Field Attrition (Bar Chart)

Rows → Education Field

Columns → Attrition Count

📌 Attrition by Gender (Donut Chart)

Use Gender as color

Use Attrition Count as measure

📌 Attrition by Age & Gender (Donut Charts)

Create multiple donut charts for different age groups

4. Build the Dashboard

Go to Dashboard → New Dashboard

Set size (e.g., 1400 x 700)

Drag all sheets into the canvas

Use containers for layout organization

5. Design & Formatting

Add a title: HR Analytic Dashboard

Use consistent colors:

Blue for neutral data

Orange for attrition

Purple for gender comparison

Add labels and tooltips

Remove unnecessary gridlines

6. Add Interactivity

Filters (e.g., by Department, Gender)

Highlight actions

Tooltips for detailed insights

7. Export & Share

Save as .twbx (packaged workbook)

Export dashboard as image for preview

