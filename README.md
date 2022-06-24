<div align="center">
  
# Phone Book App 📞
![image](https://user-images.githubusercontent.com/76960580/175349450-14c1afc6-7e2d-443f-b384-e8abe272ff4c.png)
</div>

## Screen Shots 🎞
<div align="center">

[Screen Shot](https://github.com/shubhajeet1207/Phone-Book-App/tree/master/screen%20shots)
</div>

## Features 🌟

#### User 👩🏻🧑🏻

Following features are available/unavailable to the Users:

- [x] User authentication.
- [ ] Users can change their username and display image.
- [ ] Users can search contacts by name.
- [x] Users can add number to the Database.

#### Admin 👨🏻‍💻

Following features are available/unavailable to the Users:

- [x] Can view, create, update, and delete admin users.
- [x] Can view, create, update, and delete numbers/users.

#### Installation Guide

Follow the steps below for setting up the project into your System:
1. Activate the virtual environment first to stay away from verson conflicts.
```python
virtualenv venv
```
2. Now activate the virtual environment which is being created. 
```python
.\venv\Scripts\activate
```
3. Now Run the server
```python
python manage.py runserver
```
**Note -** If any changes made in models.py file than user need to migarte the changes made in the models to the production database(i.e. SQLite3).
For this following command would be used:
```python
python manage.py makemigrations
python manage.py migrate
```


