# Mediview: Hospital Data Analytics Dashboard

## 📊 Project Overview
Mediview is a comprehensive data analytics dashboard designed to streamline hospital operations using interactive visualizations in Power BI. The project leverages a relational MySQL database to deliver insights on bed occupancy, patient appointments, billing data, and satisfaction trends. The dashboard enables hospital administrators and healthcare analysts to make data-driven decisions efficiently.

## 🔧 Technologies Used
- **Power BI Desktop**: For building interactive dashboards and reports
- **MySQL**: As the backend database storing structured hospital data
- **Power Query (M language)**: For data cleansing, transformation, and ETL processes
- **DAX (Data Analysis Expressions)**: For custom calculations, aggregations, and dynamic filtering

## 🗃️ Dataset Structure
The dataset is modeled in a normalized relational format and includes the following key tables:

- **beds**: Contains bed IDs, types (ICU/General), and availability status
- **rooms**: Includes room IDs, types, and occupancy linkage
- **patients**: Demographic details such as age, gender, and patient IDs
- **doctors**: Doctor IDs, names, specialties
- **appointments**: Schedules linking patients and doctors
- **hospital_bills**: Billing amounts, types, and patient associations
- **medical_tests**: Test names, departments, and patient-test mappings
- **satisfaction_score**: Patient feedback and scores

## 📈 Key Features & Visuals
- **Bed Occupancy Dashboard**: Displays current usage by bed type and availability status
- **Room Type Utilization**: Highlights underutilized room categories
- **Appointments Overview**: Doctor-wise and department-wise appointment metrics
- **Billing Insights**: Shows revenue by department and payment types
- **Patient Satisfaction**: Trends based on collected feedback scores
- **Demographic Analysis**: Breakdowns by age groups, gender, and patient inflow trends

## 🔍 Insights Derived
- ICU beds show a trend of over-utilization during weekends
- Room Type B is consistently underutilized, suggesting potential restructuring
- High billing departments correlate with low satisfaction, indicating potential inefficiencies
- Patients experience delays in departments with high test request density

## 🧠 Skills Gained
- Connecting Power BI to a MySQL relational database
- Writing advanced DAX formulas for calculated columns and measures
- Transforming and modeling data with Power Query
- Creating interactive dashboards with slicers, filters, and drill-down visuals
- Interpreting healthcare data to inform actionable decisions

## ⚙️ How to Run
1. Clone this repository.
2. Open `Mediview.pbix` in Power BI Desktop.
3. Navigate to **Transform Data > Data Source Settings** and update the MySQL server and credentials as per your environment.
4. Refresh the data and explore the dashboard.
