# Hospital Management System
This is a basic console-based application to manage patients and doctors of a hospital.

# Features
Add new patients and capture their details like name, age, contact etc.
Assign patients to different departments based on their medical condition.
View doctor details like specialization, contact for emergency/non-emergency cases etc.
View route/direction to reach different departments in the hospital.
Visit existing patients by entering their patient ID.
Exit/quit the application.
Getting Started
Clone the repository

# Copy
git clone https://github.com/username/hospital-management-system.git
Open the project in your IDE of choice and run the main.c file. Follow the on-screen instructions to manage patients, doctors and departments.

# Data Structures
The project uses following data structures:

struct to store patient details
struct to store doctor details
Arrays to store patient and doctor data
# Functions
Main functions include:

loadPolicies() - Load hospital rules
loadDoctorsArray() - Populate doctor details array
getMedicalAttention() - Add new patient
patientVisit() - Visit existing patient
listOutDeptsWithIds() - View department list
showDeptRoute() - Display route for department
view() - View patient details
# Scope for Improvement
Add validation for user inputs
Store and retrieve data from file
Add more features like search, update, delete
Enhance UI with menus and options
Error handling for invalid inputs
# License
MIT
