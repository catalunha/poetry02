cd folder-project
poetry init
poetry env use 3.10
poetry shell
poetry add django djangorestframework
django-admin startproject project .
python manage.py runserver