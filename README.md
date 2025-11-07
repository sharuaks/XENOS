✈️ XENOS – Airport Operation Management System
📚 Course:

Database Management System (CS2102-1)
Semester: IV CSE, Section C
Institution: NMAM Institute of Technology
Submitted To: Dr. Pradeep Kanchan, Assistant Professor Gd-III, Dept. of CSE
Submitted By:

Sharanya Aithal K.S. (NNM23CS177)

Shaldon Barnes (NNM23CS172)

🧾 Project Overview

XENOS is a database-driven airport operation management system developed to automate and streamline essential airport activities.
It efficiently manages flight schedules, passenger information, staff details, and report generation, ensuring operational efficiency, data consistency, and security across the airport ecosystem.

🚩 Problem Statement

Airports often rely on fragmented or outdated systems that lead to:
Inefficiency in managing operations
Difficulty accessing real-time data
Security risks and data inconsistencies
XENOS addresses these issues by providing a centralized, user-friendly, and secure system for managing all airport operations.

🎯 Objectives

Provide 24×7 access to flight and staff data
Automate scheduling and reporting
Improve inter-department communication
Support access via desktops, tablets, and mobiles
Enhance security through role-based access
Reduce manual workload and improve accuracy

🧰 Hardware & Software Requirements
Hardware:
1.6 GHz or faster processor
Minimum 1 GB RAM
Stable Internet connection

Software:
Browser: Chrome / Firefox (latest version recommended)
Text Editor: Visual Studio Code
Node.js (v18 or higher)
PostgreSQL + pgAdmin (for database)

⚙️ Methodology
Sign In Page – Secure login for users
Home Page – Central dashboard
Flights Module – Manage flight data (arrival/departure, gates, status)
Passengers Module – Manage passenger details and check-in info
Reports Module – Generate detailed, filterable, and exportable reports
All modules interact with a centralized PostgreSQL database, ensuring real-time updates and role-based access.

🗄️ Database Design
ER-Diagram Entities:
FLIGHTS: Flight_id, Flight_name, Flight_no, Dept_time, Arr_time, Gate_id
GATE: Gate_id, Terminal, Status
PASSENGERS: Pass_id, Pass_name, Flight_no, Dept_time
REPORTS: Report_id, Pass_id, Admin_id, Report_type, Generated_on
ADMIN_USERS: Admin_id, Email_id, Password, Role

💻 Implementation Steps
Initialize Node.js Project
npm init -y
Install Dependencies
npm install express pg path
Setup Database
Create the database and tables in PostgreSQL using SQL or pgAdmin.
Run the Server
node server.js

📊 Results

Successfully implemented a functional web-based airport management system
Enabled real-time database operations for flight, passenger, and report modules
Improved accuracy, security, and user experience

🚀 Future Enhancements

Mobile app for staff and crew
Real-time flight tracking and notifications
Passenger self-service portal for check-ins
Data analytics and reporting dashboard
Multi-language and multi-airport support

🔗 References
W3Schools – Node.js
W3Schools – PostgreSQL
W3Schools – JavaScript

🏁 Conclusion

XENOS demonstrates the power of database-driven web systems in transforming traditional airport operations.
It provides a secure, efficient, and scalable platform that can evolve into a complete smart airport management solution.
