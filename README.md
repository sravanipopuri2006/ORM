# Ex02 Django ORM Web Application
## Date: 

## AIM
To develop a Django application to store and retrieve data from a Book database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here

## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
Enter the code for admin.py and models.py

### STEP 4:
Execute Django admin and create details for 10 books

## PROGRAM
## Admin.py
from django.contrib import admin
from .models import students
admin.site.register(students)

## Models.py
from django.db import models
class students(models.Model):
    rollno=models.IntegerField()
    name=models.CharField(max_length=20)
    refno=models.IntegerField()
    age=models.IntegerField()
    email=models.CharField(max_length=20)


## OUTPUT

![image](https://github.com/sravanipopuri2006/ORM/assets/139778301/eefbdc0a-7028-484c-842d-b90d00a17066)


![image](https://github.com/sravanipopuri2006/ORM/assets/139778301/2b6aeaef-c51a-4e84-aa6d-5d3dcc14a950)



## RESULT
Thus the program for creating a database using ORM hass been executed successfully
