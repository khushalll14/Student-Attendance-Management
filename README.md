# Django Student Management System (beta)
This is a Simple Student Management System Developed for Educational Purpose using Python (Django).

## Features of this Project

### A. Admin Users Can
1. See Overall Summary Charts of Stuudents Performance, Staffs Perfomrances, Courses, Subjects, Leave, etc.
2. Manage Staffs (Add, Update and Delete)
3. Manage Students (Add, Update and Delete)
4. Manage Course (Add, Update and Delete)
5. Manage Subjects (Add, Update and Delete)
6. Manage Sessions (Add, Update and Delete)
7. View Student Attendance
8. Review and Reply Student/Staff Feedback
9. Review (Approve/Reject) Student/Staff Leave

### B. Staff/Teachers Can
1. See the Overall Summary Charts related to their students, their subjects, leave status, etc.
2. Take/Update Students Attendance
3. Add/Update Result
4. Apply for Leave
5. Send Feedback to HOD

### C. Students Can
1. See the Overall Summary Charts related to their attendance, their subjects, leave status, etc.
2. View Attendance
3. View Result
4. Apply for Leave
5. Send Feedback to HOD


### Pre-Requisites:

1. Install Python Latest Version
[ https://www.python.org/downloads/ ]


### Installation
**1. Create a Folder where you want to save the project**

**2. Create a Virtual Environment and Activate**

Install Virtual Environment First
```
$  pip install virtualenv
```

Create Virtual Environment

```
$  python -m venv venv
```

Activate Virtual Environment

```
$  source venv/scripts/activate
```

**3. Install Requirements from 'requirements.txt'**
```python
$  pip install -r requirements.txt
```

**4. Add the hosts**

- Got to settings.py file 
- Then, On allowed hosts, Add [‘*’]. 
```python
ALLOWED_HOSTS = ['*']
```


**5. Now Run Server**

Command for PC:
```python
$ python manage.py runserver
```


**7. Login Credentials**

Create Super User (HOD)
```
$  python manage.py createsuperuser
```
Then Add Email, Username and Password

for login use this details:
read the admininfo.txt file.

for more logins see admininfo text file in folder.

## For Projects Enquiry
1. Email - ladvakhushal14@gmail.com
2. LinkedIn - [LADVA KHUHSAL](https://www.linkedin.com/in/ladva-khushal/ "ladva-khushal on LinkedIn")

