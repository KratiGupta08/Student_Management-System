# Student_Management-System
Student Management System
This Python project is a Student Management System built using Tkinter for the graphical user interface and SQLite3 for the database. It allows users to manage student records efficiently, including adding, viewing, deleting, and resetting records.

Features
Add Records: Input and save student details (Name, Email, Contact, Gender, Date of Birth, and Stream) to the database.
View Records: Display all student records stored in the SQLite database.
Delete Records: Remove specific student records.
Reset Fields: Clear all input fields for fresh data entry.
Reset Form: Delete all data from the database and refresh the display.
Graphical User Interface: Intuitive and user-friendly interface with separate frames for input, actions, and data display.
Technologies Used
Python
tkinter (GUI framework)
sqlite3 (database)
tkcalendar (Date Picker)
SQLite3 Database
Prerequisites
Before running the project, ensure you have the following:

Python 3.x installed on your system.
Required Python libraries:
tkinter (comes pre-installed with Python)
sqlite3 (comes pre-installed with Python)
tkcalendar
Install via pip:
bash
Copy code
pip install tkcalendar  
How to Run
Clone the Repository:

bash
Copy code
git clone https://github.com/your-username/student-management-system.git  
cd student-management-system  
Install Dependencies:
Ensure all required libraries are installed:

bash
Copy code
pip install tkcalendar  
Run the Application:
Execute the Python script:

bash
Copy code
python student_management_system.py  
Use the Application:

Input student details in the left panel.
Use buttons to manage records (Add, View, Delete, Reset).
View all records in the table on the right panel.
Project Structure
perl
Copy code
student-management-system/  
│  
├── student_management_system.py  # Main application script  
├── Student_Database.db           # SQLite3 database file (auto-created on first run)  
├── README.md                     # Project documentation  
Screenshots
1. Main Interface
Displays input fields, action buttons, and a record table.

2. Add Records
Fill in details and click Submit and Add Record to save the student’s data.

3. Delete Records
Select a record and click Delete Record to remove it.

Contributing
Contributions, issues, and feature requests are welcome!

Fork the repository.
Create your feature branch:
bash
Copy code
git checkout -b feature/your-feature-name  
Commit your changes:
bash
Copy code
git commit -m 'Add some feature'  
Push to the branch:
bash
Copy code
git push origin feature/your-feature-name  
Submit a pull request.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
Special thanks to the developers of:

Tkinter for creating a GUI framework for Python.
Tkcalendar for providing an easy-to-use date picker widget.
