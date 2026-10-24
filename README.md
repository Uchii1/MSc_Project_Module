#   README 
Artefact developed for MSc Project in Computer Science Module. 

## Installation Instructions (Windows)

### Prerequisites
Python version 3 or higher  
pip  (with Python)
Windows Powershell

Download studySoft onto your computer by downloading the zipped file in this repository
 Inside a zipped file is a subfolder called studySoft containing manage.py.

### Step 1: Navigate to Project in Powershell
In Windows Powershell, type the following and press Enter:

cd C:\Users\Your UserName \studySoft
(replace 'Your UserName' with your own windows username

### Step 2: Install Django
Run in PowerShell:
pip install Django

### Step 3: Navigate to the Django project subfolder
Run in PowerShell:
cd C:\Users\Your UserName\studySoft\studySoft
manage.py is contained in this subfolder

### Step 4: Apply migrations
Run in PowerShell:
python manage.py migrate
This sets up the database. 

### Step 5:  Run the server
Run in PowerShell:
python manage.py runserver

You should see output ending with:
Starting development server at http://127.0.0.1:8000/
Leave this PowerShell window open — closing it will stop the server.

### Step 6: Open in browser
Open any web browser 
Copy/Type this address into the address bar:
http://127.0.0.1:8000/

Press Enter. The StudySoft app should NOW load.

### Login as a user. 
Login details for existing demo accounts are included in assessment submission document submitted on Elite. 

#### ! Important: Do not open the HTML files in the zipped folder on your web browser directly from File Explorer, this will not apply the backend code done in Django.

