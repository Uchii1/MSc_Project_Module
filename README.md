#   README 

## Descripton
This artefact was developed for the MSc Project in Computer Science Module. 

## Installation Instructions (Windows)

### Prerequisites
Python version 3 or higher  
pip  (with Python)
Windows Powershell

Download the StudySoft zipped file in this repository onto your computer, and unzip the file.
The zipped file contains a subfolder called studySoft, which contains the Python file manage.py.

### Step 1: Navigate to Project in Powershell
In Windows Powershell, type the following and press Enter:

cd C:\Users\Your UserName \studySoft
(replace 'Your UserName' with your own Windows username

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
*Starting development server at http://127.0.0.1:8000/*
Leave this PowerShell window open while working with StudySoft. Closing it will stop the server.

### Step 6: Open in browser
Open any web browser (Google Chrome, Microsoft Edge and Mozilla Firefox all work well for this)
Copy or Type this address into the address bar:
**http://127.0.0.1:8000/**
The web application should now load in your browser

### Step 7: Login as a user. 
Most features can be used without logging in. However, to use the *My Progress* webpage, you must log in as a user.
You can create a new account.

(**For the Examiner**: Login details for two existing demo accounts in the programme were included in the assessment document submitted on Elite. The accounts can be logged into to see how the *My Progress* tab works)

### Please Note: 
Please do not open the HTML files in the zipped folder on your web browser directly from your File Explorer. This will not apply the backend code written in Django.

