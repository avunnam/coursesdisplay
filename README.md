                                                        Courses
Motive of this project is to develop an API that could assist students to pick from the Available Courses.
 Build Status: 
          Available courses page has been implemented, the remaining functionality of giving the ability to choose the course not yet achieved.

Buit With:
           Django Framework:  https://www.djangoproject.com/

Code Example:
I have developed app to display the available courses. In student app urls.py file is redirected to the course.urls. In course app urls.py file is redirected to the index which is written in views.py file. In views.py file is redirected to homepage.html. Homepage.html is code to diaplay available courses.

Installation:
Django Framework Installation: https://docs.djangoproject.com/en/2.1/intro/install/
Code Editor PyCharm: https://www.jetbrains.com/pycharm/download/#section=windows

Tests:

$ python manage.py runserver
$ python manage.py startapp
And than you will be able to reach you server from machine in browser http://localhost:8000 
To get to Available courses page: http://localhost:8000/course
