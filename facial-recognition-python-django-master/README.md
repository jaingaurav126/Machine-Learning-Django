# facial-recognition-python-django
Face detection and facial recognition along with recognized persons information fetched from database.

General Languages and versions

    •	Python version: 2.7.14
    •	Django version: 1.11.9
    •	OpenCV version: 3.4.0
    •	Sklearn version: 0.19.1
   

Change mysql setting

       go to settings.py under faceRecog folder.
       change database configuration under DATABASES object.



Run -

    python manage.py makemigrations
    python manage.py migrate
    python manage.py createsuperuser
    python manage.py runserver

