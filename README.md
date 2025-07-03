Educational Management System using ServiceNow
This project demonstrates the development of an Educational Management System on the ServiceNow platform. It streamlines key operations such as student admissions, academic progress tracking, and administrative management using ServiceNow capabilities like tables, forms, client scripts, workflows, and update sets.

Project Setup and Implementation
Step 1: Creating an Update Set
Created an update set named Educational Organization.

Captures and transports all ServiceNow customizations.

Insert Image 1: Screenshot of Update Set creation

Step 2: Creating Tables
SalesForce Table: Base table for records.

Admission Table (extends SalesForce): For student admission data.

Student Progress Table (extends SalesForce): For tracking academic performance.

Insert Image 2: Screenshot of Table creation page
Insert Image 3: Screenshot of Admission Table configuration
Insert Image 4: Screenshot of Student Progress Table configuration

Step 3: Form Layout Configuration
Configured form layout for the Student Progress Table.

Insert Image 5: Screenshot of Form Layout setup for Student Progress Table

Step 4: Form Design
Designed form layouts for each table to provide structured data entry:

SalesForce Table

Insert Image 6: Form design for SalesForce Table

Admission Table

Insert Image 7: Form design for Admission Table

Student Progress Table

Insert Image 8: Form design for Student Progress Table

Step 5: Number Maintenance
Implemented auto-generation of Admin Number using number maintenance.

Insert Image 9: Screenshot of Number Maintenance configuration

Step 6: Process Flow for Admissions
Created a process flow for the Admission Table.

Flow: InProgress → Joined → Rejected → Rejoined → Closed → Cancelled

Insert Image 10: Screenshot of Process Flow setup

Step 7: Client Scripts
Several client scripts were implemented to enhance interactivity:

Auto Populate – Prefills fields in the Admission Table
Insert Image 11: Auto Populate script

Pincode Update – Updates fields based on pincode
Insert Image 12: Pincode Update script

Disable Fields – Prevents edits on specific fields in Student Progress Table
Insert Image 13: Disable Fields script

Total Update – Computes total marks
Insert Image 14: Total Update script

Result – Calculates Pass/Fail
Insert Image 15: Result script

Percentage – Calculates percentage
Insert Image 16: Percentage script

Conclusion
The Educational Management System built on ServiceNow illustrates a practical use of platform capabilities beyond IT services. It enables educational institutions to digitize and automate their admission and academic processes efficiently. By integrating structured tables, process workflows, and intelligent scripts, this project offers a scalable, user-friendly administrative solution.
