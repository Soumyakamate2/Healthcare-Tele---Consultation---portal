
🏥 Hospital Management System (PHP & MySQL)

This is a fully functional Hospital Management System built using PHP, MySQL, HTML, CSS, and JavaScript. It digitalizes core hospital operations including patient registration, doctor management, appointment scheduling, medical history tracking, and admin control. The system supports role-based access for Admins, Doctors, and Patients, ensuring secure and streamlined workflow.

🚀 Features
👨‍💼 Admin Module

Manage doctors (add/edit/delete)

Manage specializations

Manage patients

View and manage appointments

Track doctor and patient login logs

Review contact/feedback messages

View/update medical records

Full database record control

🩺 Doctor Module

Doctor login panel

View scheduled appointments

Update patient medical history

Manage diagnoses, prescriptions, and treatment notes

Update availability and schedule (from doctorschedule table)

👤 Patient Module

Patient registration/login

Book doctor appointments

View appointment history

View prescriptions & treatment details

Update personal information

📌 Other Features

Role-based secure authentication

Contact form with admin reply flow

Track login records for security (userlog & doctorslog)

Medical history storage (BP, sugar, weight, temperature, prescription)

Doctor schedule & timings

Clean database structure with multiple tables

🛠️ Technologies Used

Frontend: HTML5, CSS3, Bootstrap, JavaScript

Backend: PHP

Database: MySQL (hms.sql, doctorschedule.sql)

Server: Apache (XAMPP/WAMP/LAMP)

🗄️ Database Structure

Your database includes the following major tables:

Table Name	Purpose
admin	Admin login details
users	Patient login & personal info
doctors	Doctor accounts & details
doctorspecilization	List of medical specialties
appointment	Patient–doctor appointments
tblpatient	Detailed patient information
tblmedicalhistory	Patient medical history & prescriptions
doctorslog	Log history of doctor logins
userlog	Log history of user logins
tblcontactus	Contact form & admin replies
doctorschedule	Doctor working days & timings
📂 Folder Structure (Typical Layout)
/admin               -> Admin dashboard files
/doctor              -> Doctor panel files
/user                -> Patient panel files
/includes            -> Config & reusable components
/sql                 -> Database files (hms.sql, doctorschedule.sql)
index.php            -> Homepage

⚙️ Installation Guide

Install XAMPP/WAMP/LAMP

Clone or download this repository

Copy the project folder to:

xampp/htdocs/


Import hms.sql and doctorschedule.sql into MySQL

Update database credentials in config.php

Start Apache and MySQL

Open the project in browser:

http://localhost/hms/

🔐 Default Credentials
Admin:
username: admin
password: Test@12345


(From the admin table)

🤝 Contributing

Contributions are welcome. Please create a pull request or open an issue for discussion.

📄 License

This project is open-source and free to use
