0. Create a project folder, such as hello_django
    - sudo apt-get install python3-venv    # If needed
    - python3 -m venv .venv
    - source .venv/bin/activate
	
    - python -m pip install --upgrade pip
	
    - python -m pip install django

1. Create the Django project
    - django-admin startproject web_project .

2. Create an empty development database 
    - python3 manage.py migrate

3. Run server
    - python manage.py runserver
	
4. Create a Django app
    - python manage.py startapp hello

5. Work with data, data models, and migrations
    - Make changes to the models in your models.py file.
    - Run python manage.py makemigrations to generate scripts in the migrations folder that 		migrate the database from its current state to the new state.
    - Run python manage.py migrate to apply the scripts to the actual database.