# DMP
![download (1)](https://github.com/RubaALmohya/DMP/assets/87912604/5176e505-5d9e-4cfe-b000-c136ad7143ce)

## Overview

This README file provides an overview of the project, including information about the team, data, and tools used. It serves as a guide for contributors and users of the project repository on GitHub.

## Project Description: Data Classification and Security Policies for Twauiq Academy

The project aims to develop a comprehensive data classification and security policies and procedures document for Twauiq Academy. The document will provide guidelines and controls to ensure the protection and appropriate handling of sensitive data within the organization. Additionally, the project will define the data governance operating model to establish effective data management practices.

 ## Goals and Objectives
 The primary goals of this project are:
-	Establish a Data Classification Framework:
Develop a systematic approach to classify data based on its sensitivity and criticality. This framework will help identify and prioritize data assets for appropriate security controls.
-	Define Security Policies and Procedures:
Create a set of comprehensive security policies and procedures that outline the acceptable use, handling, and protection of data within Twauiq Academy.

-

## Timeline

The project is expected to be completed within 4 Days. 


## Team

The project is being developed and maintained by a team of dedicated individuals. The team members and their roles are as follows:

- [Ruba Almuhya]: [Technical side ]
- [Manar Alahaimid]: 
- Ruba A. Almuhya: [Technical side, Framework design, Document ]
- Mariam M. Albenyan: [Classification policy writing, Framework, design]
-  Shouq Almutairi: [Business Glossary ]
-  Manar Alahaimid: [Presentation, writing document]
-  Rand Almajmaj: [writing document]

Feel free to reach out to any team member if you have questions, suggestions, or would like to contribute to the project.

## Data

The project utilizes a database with several tables to store information about students, employees, and programs. Please note that the data provided below is for illustrative purposes and not actual data.

**Table: students**
- Columns:
  - id: Unique identifier for each student (auto-incremented)
  - name: Student's name (up to 50 characters)
  - nationality: Student's nationality (up to 50 characters)
  - university: Name of the university the student attends (up to 100 characters)
  - major: Student's major or field of study (up to 100 characters)
  - graduation_date: Date of the student's graduation
  - date_of_birth: Date of the student's birth
  - email: Student's email address (up to 100 characters)
  - phone_number: Student's phone number (up to 20 characters)
  - gender: Student's gender (up to 10 characters)
  - address: Student's address (up to 200 characters)

**Table: employees**
- Columns:
  - id: Unique identifier for each employee (auto-incremented)
  - name: Employee's name (up to 50 characters)
  - nationality: Employee's nationality (up to 50 characters)
  - gender: Employee's gender (up to 10 characters)
  - department: Department where the employee works (up to 100 characters)
  - joining_date: Date when the employee joined the company
  - salary: Employee's salary (up to 10 digits with 2 decimal places)
  - job_type: Type of job or position held by the employee (up to 50 characters)

**Table: programs**
- Columns:
  - id: Unique identifier for each program (auto-incremented)
  - name: Name of the program (up to 100 characters)
  - number_of_students: Number of students enrolled in the program
  - program_level: Level of the program (up to 50 characters)
  - program_type: Type of the program (up to 50 characters)
  - program_duration: Duration of the program in months

**Table: student_programs (relationship table)**
- Columns:
  - student_id: Foreign key referencing the id column in the students table
  - program_id: Foreign key referencing the id column in the programs table
  - Primary Key: Combination of student_id and program_id to ensure uniqueness

**Table: employee_programs (relationship table)**
- Columns:
  - employee_id: Foreign key referencing the id column in the employees table
  - program_id: Foreign key referencing the id column in the programs table
  - Primary Key: Combination of employee_id and program_id to ensure uniqueness
    
 ### ERD 
 ![image](https://github.com/RubaALmohya/DMP/assets/87912604/6c6f4b9e-a001-43f7-98b8-250b4d2c9c6b)


## Tools and Technologies

The project leverages various tools and technologies to facilitate development and enhance its functionality. The key tools and technologies used in this project include:

- [Postgres]: [is an open-source, object-relational database management system (DBMS)]
- [Openmetadata]: [is an open-source metadata management tool designed to help organizations manage and govern their data assets.]
  ![Recording-2023-11-15-130245](https://github.com/RubaALmohya/DMP/assets/87912604/36cb47d9-4a4c-4abd-b93b-93a856f59d90)
![Recording-2023-11-15-130245](https://github.com/RubaALmohya/DMP/assets/87912604/783d5bb7-48d0-4a6a-802d-2fd5b5525bda)

## Conclusion

The project aims to develop a comprehensive data classification and security policies and procedures document for Twauiq Academy. By establishing clear guidelines, controls, and a data governance operating model, the project will ensure the protection and proper handling of sensitive data, as well as compliance with data privacy and regulatory requirements.


