Built a Restaurant website with interactive menu and online reservation service using Django, Python.

Steps to run:
1. Install python, sqlite viewer from VS Code extensions
2. To setup virtual environment:
    pipenv install django
    pipenv shell
3. Migrate changes to Database:
   python manage.py makemigrations
   python manage.py migrate
4. Run the service:
   python manage.py runservice
