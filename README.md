# django-demo

Demo django application

## Steps

1. Create a 'django demos' directory.
2. Create a virtualenv 'django_venv'.
3. `cd` to 'django demos'.
4. Open the terminal or commandline in this directory.
5. Run `source <the_path_to>/django_venv/bin/activate`.
6. Run `pip install django`.
7. Run `django-admin startproject mysite` to create an app called 'mysite'. Note that 'mysite' has a directory 'mysite' inside it but you can only rename the parent directory of the two. At this point, our settings have it that the app is called 'mysite'. I renamed mine to 'django mysite' which contains directory 'mysite' but you don't have to do thagt.
8. Run `python manage.py runserver` and visit the url `http://127.0.0.1:8000/`. If that works, all is well. Also, an error will state `Run 'python manage.py migrate'` to apply migrations.
9. Run `python manage.py startapp webapp` or whatever name you want to call your app.
