# Sea Social Project
The Sea Social Application is a multi-user blog application built with the Django web framework.

## Getting Started

**Windows:** Use the Git Bash program (installed with Git) to get a Unix-style terminal.  
**Other systems:** Use your favorite terminal program.

1. From the terminal run `git clone https://github.com/jjp601/Sea-Social-Project`. This will provide you with all of the source code and files to get the Django application up and running.
2. Once you have the project files you will want to set up a virtualenv. You may do this from your terminal with `python -m  venv [name of project]`. This will create a virtual environment for the project.
3. Next, install Django with the command `pip install django==1.11.12`. I used Django 1.11.12 for this project.
4. Run `python manage.py runserver` to run the Django web server and setup the SQLite database. The Sea Social application can the be viewed in your browser at **http://localhost:8000**.
5. Once you have the application running you will be able to login or set up an account. You can add, edit, and delete your own groups or posts.

## Resources
* [Django](https://docs.djangoproject.com/en/1.11/)
* [SQLite](https://www.sqlite.org/)
* [Django Debug Toolbar](https://github.com/jazzband/django-debug-toolbar)
