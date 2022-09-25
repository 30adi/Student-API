# Student-API

This is a REST API built using django, to demonstrate CRUD operations of Student's information that includes 'name', 'email' and 'phone number'.

## Clone the project

```bash
git clone https://github.com/30adi/Student-API.git
```

Open the project in any python supported IDE

## Installations
```bash
pip install djangorestframework
```
## Start server
```bash
python manage.py runserver
```
## create a user
Create SuperUser
```bash
python manage.py createsuperuser
```

## Follow the instructions below to perform CRUD operations:

To view all students and their details
```bash
http://127.0.0.1:8000/api/
```
To view individual student's details:
http://127.0.0.1:8000/api/student-view/pk 
// pk is the primary key or id of the student
```bash
http://127.0.0.1:8000/api/student-view/1
```
To add student details
```bash
http://127.0.0.1:8000/api/add-student
```
To update existing student details
```bash
http://127.0.0.1:8000/api/update-student
```
To delete existing student // "pk" is primary-key or student id
```bash
http://127.0.0.1:8000/api/delete-student/pk
```


