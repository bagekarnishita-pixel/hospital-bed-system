# hospital-bed-system
🏥 Centralized Hospital Bed Allocation System

A full-stack emergency management system that automates hospital bed availability tracking and allocation — built to save time in critical medical situations.

📌 What It Does

In emergency situations, hospital staff waste valuable minutes manually checking which beds are free. This system solves that by:

Showing real-time bed availability across all departments on a single dashboard Automatically allocating the nearest available bed based on emergency type Eliminating manual data entry — staff update bed status with one click Speeding up response time for emergency services

🛠️ Tech Stack

LayerTechnologyFrontendHTML, CSS, JavaScriptBackendNode.jsDatabaseMySQLArchitectureFull-Stack Web Application

🚀 How to Run Locally

Clone the repository
bashgit clone https:

Install backend dependencies
bashnpm install

Set up the database
Open MySQL and create a database:

sqlCREATE DATABASE hospital_db;

Import the schema:

bashmysql -u root -p hospital_db < database/schema.sql

Configure environment variables
Create a .env file:

DB_HOST=localhost DB_USER=root DB_PASSWORD=your_password DB_NAME=hospital_db PORT=3000

Start the server
bashnode server.js

Open in browser
http://localhost:3000

🖥️ System Flow

Emergency arrives at hospital ↓ Staff opens dashboard → sees all beds in real time ↓ System checks bed availability by department ↓ Auto-allocates nearest available bed ↓ Database updates instantly — all screens refresh

✨ Key Features

Live dashboard — real-time bed status across all departments Auto-allocation logic — no manual decision needed in emergencies Role-based access — doctors, nurses, and admin have different views Instant updates — when a bed status changes, all connected screens update

📊 Database Structure

TablePurposebedsBed ID, department, status (available/occupied)patientsPatient info, assigned bed, admission timedepartmentsDepartment names and capacitystaffStaff login and role management

👨‍💻 Author

nishita bagekar

BCA (Cybersecurity) — GH Raisoni Skill Tech University, Nagpur

bagekarnishita@gmail.com

🔗 GitHub
