# Visualization for student score
A college management system built using Django framework. It is designed for interactions between students and teachers and to visualize student score. Features include attendance, marks .

## Installation

Python and Django need to be installed

```bash
pip install django
```

## Usage

Go to the visualization-tool-for-analysing-student-score folder and run

```bash
python manage.py runserver
```

Then go to the browser and enter the url **http://127.0.0.1:8000/**


## Login

The login page is common for students and teachers.  
 

Example usernames for student:  
username- 'abhinav'  
password- 'abhi12345'  

Example usernames for teacher :  
username- 'raghukishore'  
password- 'raghu12345'  


You can access the django admin page at **http://127.0.0.1:8000/admin** and login with username 'MAHINDRA' and the  password 'MAHINDRA12'.

Also a new admin user can be created using

```bash
python manage.py createsuperuser
```

## Users

New students and teachers can be added through the admin page. A new user needs to be created for each. 

The admin page is used to modify all tables such as Students, Teachers, Departments, Courses, Classes etc.


 

