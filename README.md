# Ophthalmology Clinic Patient Analysis using SQL
**
This project simulates a real-world ophthalmology clinic database using SQL Server and a star schema design approach. The database was designed to reflect realistic healthcare workflows commonly used in Canadian ophthalmology clinics, including patient management, appointment scheduling, procedure tracking, and appointment status monitoring.

The project contains:

- Dimension Tables
  - Patients
  - Procedures
- Fact Table
  - Appointments

The dataset includes:
- Patient demographics
- PHN tracking
- Appointment schedules
- Ophthalmologists
- Procedure categories
- Appointment statuses
- Eye clinic workflow simulations
  
Tools Used
- Microsoft SQL Server
- Azure Data Studio
- GitHub
- Power BI (for future dashboard integration)

Database Structure
Dimension Tables
1. Patients
Stores patient demographic information:
- PatientID
- PHN
- First Name
- Last Name
- Age
- Gender
- Location

2. Procedures
Stores ophthalmology procedure information:
- ProcedureID
- Procedure Name
- Procedure Category
- Procedure Type
- Estimated Duration
- Fact Table

3. Appointments
Stores appointment transaction records:
- AppointmentID
- PatientID
- DoctorName
- ReasonForVisit
- AppointmentDate
- AppointmentTime
- AppointmentStatus

SQL Skills Demonstrated
- CREATE DATABASE
- CREATE TABLE
- INSERT INTO
- SELECT statements
- WHERE filtering
- GROUP BY
- ORDER BY
- COUNT aggregation
- AVG aggregation
- CASE statements
- INNER JOIN
- Fact and Dimension table modeling
- Healthcare data analysis queries

Analysis Performed
Patient Analysis
- Total number of patients
- Female patient filtering
- Senior vs Adult vs Pediatric patient segmentation
- Average patient age
- Oldest patient identification
- Patient distribution by location
    
Appointment Analysis
- Total appointments per doctor
- Appointment status breakdown
  - Arrived
  - Cancelled
  - No Show
- Doctor with the highest No Show appointments
- Full Eye Exam appointment tracking
- Cancelled appointment analysis with patient details

Procedure Analysis
- Routine consultations
- Diagnostic examinations
- Pre-surgical testing
- Treatment procedures
- Estimated procedure durations

Key Insights
- Senior patients represented a large portion of clinic visits.
- Follow-up and Full Eye Exam appointments were the most common visit types.
- Appointment status tracking helped identify No Show and Cancelled appointment trends.
- Procedure categorization supports future healthcare reporting and dashboard development.
- The project demonstrates foundational healthcare analytics and database modeling skills.

Future Improvements
- Integrate Power BI dashboard visualizations
- Add doctor dimension table
- Create billing and insurance tables
- Add appointment duration analysis
- Implement stored procedures and views
- Build automated reporting queries


Project Screenshots
1. Patient Dimension Table
Shows the creation and population of the Patients dimension table.

2. Patient Analysis Queries
SQL queries used for patient demographic and segmentation analysis.

3. Appointment Fact Table
Fact table containing appointment transactions and scheduling records.

5. Appointment Analysis Queries
SQL analysis queries for appointment trends, No Shows, and status breakdowns.

7. Procedure Dimension Table
Dimension table for ophthalmology procedures and procedure categorization.

Author

Daniela Monique Bie
Management Information Systems Graduate
Healthcare Administration & Data Analytics Enthusiast
