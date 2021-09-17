# Django_Project2


Prepare the environment:

- Navigate to the project folder Django_Project2
- create a virtual enviroment (Python 3):
  python -m venv v_env
- activate the virtual environment:
  Linux: source v_env/Scripts/activate
  Windows: .\v_env\Scripts\activate.bat
  Make sure the virtuan enviroment is active (by rendering v_env in the console)


Install Django:

- be sure the folder of the virtual environment (here it's v_env) is rendered in the console
- python -m pip install django
- pin the django-python dependencies (make sure requirements.txt exists)
  python -m pip freeze > requirements.txt


Set Up a Django project

- django-admin startproject my_project
  "my_project" is the current project name. The command creates the top level project folder my_project/


Start a Django app

- cd my_project
- python manage.py startapp my_app
