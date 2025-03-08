

Prerequisites: Ensure you have Python, Pip, and XAMPP/[Version 11.4+]MariaDB(MySQL) installed before proceeding.

Step 1: Download or clone the project files.

Step 2: Launch MySQL or XAMPP and open PhpMyAdmin.

Step 3: Import the "student_db.sql" database file from the GitHub repository into PhpMyAdmin via the SQL Import section.

Step 4: Create a directory named "Django," navigate into it, and move the "student_management" folder from the GitHub repository into this directory.

Step 5: Open a Command Prompt/Terminal inside the "Django" folder and set up a Python virtual environment by running: "python -m venv venv" or "py -m venv venv." This will create and activate the virtual environment.

Step 6: Activate the virtual environment by running "venv\Scripts\activate," then install MySQL support for Django and MariaDB by executing: "pip install mysqlclient."

Step 7: Move into the "student_management" directory using "cd student_management," then start the Django server by running: "python manage.py runserver."

Step 8: Open your web browser and go to 127.0.0.1:8000 to access the application.

Step 9: Navigate through the platform and test its functionalities, including CRUD (Create, Read, Update, Delete) operations.