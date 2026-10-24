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
Leave this PowerShell window open. Closing it will stop the server.

### Step 6: Open in browser
Open any web browser 
Copy or Type this address into the address bar:
http://127.0.0.1:8000/

The web application should now load.

### Login as a user. 
Login details for existing demo accounts are included in assessment document submitted on Elite. 

## Please Note: 
Please do not open the HTML files in the zipped folder on your web browser directly from File Explorer, this will not apply the backend code done in Django.

