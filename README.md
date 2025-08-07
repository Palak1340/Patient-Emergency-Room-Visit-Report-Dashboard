# Patient-Emergency-Room-Visit-Report-Dashboard

<img width="940" height="511" alt="Patient Dashboard" src="https://github.com/user-attachments/assets/995ff908-6ff0-4c36-9a3c-43defc5a8b77" />

🔍 Overview

This project is a comprehensive Patient analysis developed using Power BI for a hospital, a healthcare domain. The case study explores and visualizes trends using one core dataset:
* Hospital ER

The goal is to understand Patient behavior, analyze health, average wait time, and help hospitals to make data-driven decisions.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🎯 Objectives

* Analyze Patient behavior and trends.
  
* Understand the relationship between no. of patients visit by year.
  
* Explore Patient visiting hospital on weektype.
  
* Build an interactive dashboard for actionable business insights.
  

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🧾 Datasets Used

📁 Patient Information

* date : Date and time of patient visit	

* patient_id : Unique patient identifier (SSN-like)	

* patient_gender : Patient's gender	

* patient_age : Patient's age in years	

* patient_sat_score : Patient satisfaction score (1-10)	

* patient_first_inital : Patient's first initial	

* patient_last_name : Patient's last name	

* patient_race : Patient's racial/ethnic identity	

* patient_admin_flag : Whether patient required special admin handling(Patient requires additional admin work (e.g., insurance verification, complex billing, medical records requests)

* patient_waittime : Wait time in minutes before being seen	

* department_referral : Department patient was referred to	

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


🧹 Data Cleaning & Transformation

* Removed duplicates and handled null value.

* Formatted dates.

* Merged Patient First Initial and  Patient Last Name as Full Name.


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🧱 Data Modeling

Defined calculated tables and DAX measures.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📐 Key DAX Measures

* Total Patients

* % Administrative Schedule 

* % Non- Administrative Schedule 

* Average Satisfaction Score 

* % No Rating 

* Age Buckets 

* Age Group

* CF Max Point (Month) 

* CF Max Point (Year) 


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📊 Dashboard Features

* Total Patient Visists

* Average Satisfaction

* Average Wait Time

* Total Patient by Age Group

* Total Patient Visits by Year

* Slicers for Moment


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📈 Key Insights

* Total Patient Visit is 9526.

* Average Satisfaction is 5.47

* Average Wait Time is 35.26

* Max Patients by Age Group is from Adult Category


----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🛠️ Tools & Technologies

Power BI Desktop

Power Query

DAX (Data Analysis Expressions)

Excel (for initial data inspection)




