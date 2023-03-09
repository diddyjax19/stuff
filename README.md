# Nest
 A simple online market place built with the Django Framework using HTML, CSS and Javascript

## Steps to Use
- Clone or download this repository
- After downloading it's [best practice](https://www.freecodecamp.org/news/how-to-setup-virtual-environments-in-python/#:~:text=Conclusion,and%20makes%20it%20easily%20reproducible) to create a virtual environment in the root folder of your repository as it helps to isolate  your Python development projects from your system installed Python and other Python environments.
- Creating a virtual environment, [windows](https://www.geeksforgeeks.org/creating-python-virtual-environment-windows-linux/):
    - [Install Python](https://www.python.org/ftp/python/3.11.2/python-3.11.2-amd64.exe)
    - [Install Pip](https://pip.pypa.io/en/stable/installation/) by running `py get-pip.py`
    - Install Virtualenv: `pip install virtualenv`
    - Create a virtual env `Python -m venv venv`
    - Activate virtual env `venv\Scripts\activate.ps1`
    - To deactivate `deactivate`

- Creating a virtual environment, [Mac OS](https://www.geeksforgeeks.org/creating-python-virtual-environment-windows-linux/):
    - [Install Python](https://www.python.org/ftp/python/3.11.2/python-3.11.2-amd64.exe)
    - [Install Pip](https://pip.pypa.io/en/stable/installation/) if it's not installed on your system `$ sudo apt-get install python-pip`
    - Install Virtualenv: `$ pip install virtualenv`
    - Check your Installation `$ virtualenv --version`
    - Create a virtual env `$ virtualenv virtualenv_name`
    - Activate the virtual env `$ source virtualenv_name/bin/activate`
    - To deactivate `$ deactivate`

- Install [Django](https://docs.djangoproject.com/en/4.1/topics/install/) `pip install django`
- Run `pip install requirements.txt`
- cd into the project folder
- `python manage.py makemigrations`
- `python manage.py migrate`
- Create a superuser t manage the admin panel `python manage.py createsuperuser`
- `python manage.py runserver`
- Access your website on `https://localhost:8000/`
- Admin panel available on `https://localhost:8000/admin`


## Django libraries used
 - [django jazzmin](https://django-jazzmin.readthedocs.io/) intended as a drop-in app to jazz up your django admin site, with plenty of things you can easily customise, including a built-in UI customizer: `pip install django-jazzmin`

 - [django taggit](https://django-taggit.readthedocs.io/) django-taggit is a reusable Django application designed to make adding tagging to your project easy and fun: `pip install django-taggit`

 - [django bootstrap datepicker plus](https://django-bootstrap-datepicker-plus.readthedocs.io/). This django widget contains Bootstrap 3, Bootstrap 4 and Bootstrap 5 Date-Picker, Time-Picker, DateTime-Picker, Month-Picker and Year-Picker input with date-range-picker functionality for django version >= 2.0.: `pip install django-bootstrap-datepicker-plus`

 - [django ckeditor](https://pypi.org/project/django-ckeditor/) Provides a RichTextField, RichTextUploadingField, CKEditorWidget and CKEditorUploadingWidget utilizing CKEditor with image uploading and browsing support included.: `pip install django-ckeditor`

 - [django paypal](https://pypi.org/project/django-paypal/) A pluggable Django application for integrating PayPal Payments Standard or Payments Pro. [Home page](https://github.com/spookylukey/django-paypal): `pip install django-paypal`

 - [django regex](https://pypi.org/project/regex/) The regex module releases the GIL during matching on instances of the built-in (immutable) string classes, enabling other Python threads to run concurrently.: `pip install regex`

 - [Stripe](https://pypi.org/project/stripe/) A Python library for Stripe’s API.: `pip install stripe`

 - [Pillow](https://pillow.readthedocs.io/) The Python Imaging Library adds image processing capabilities to your Python interpreter. This library provides extensive file format support, an efficient internal representation, and fairly powerful image processing capabilities. The core image library is designed for fast access to data stored in a few basic pixel formats. It should provide a solid foundation for a general image processing tool.: ` pip install Pillow`
 
 - [django-shortuuidfield](https://pypi.org/project/django-shortuuidfield/): Provides a ShortUUIDField for your Django models which uses the base-57 "Short UUID" package at https://github.com/stochastic-technologies/shortuuid/: `pip install django-shortuuidfield`.



## Database Model
    https://lucid.app/lucidchart/285fd016-a3c7-4da8-a254-c718238a25ee/edit?viewport_loc=453%2C-658%2C3084%2C1316%2CHWEp-vi-RSFO&invitationId=inv_4846ae5d-a4a9-4a70-b09d-aefe07996820

## Acknowledgements
 1. Havard's Introduction to web programming with javascript and Python [Django](https://cs50.harvard.edu/web/2020/weeks/3/)
 2. [Nest]((https://themeforest.net/search/nest)) Template from Theme forest.
 3. https://simpleisbetterthancomplex.com/tutorial/2016/08/01/how-to-upload-files-with-django.html
 4. Destiny Frank
 5. [Database diagram](https://lucid.app/lucidchart/285fd016-a3c7-4da8-a254-c718238a25ee/edit?viewport_loc=453%2C-658%2C3084%2C1316%2CHWEp-vi-RSFO&invitationId=inv_4846ae5d-a4a9-4a70-b09d-aefe07996820) with the help of lucid Chart
 6. [Django docs](https://docs.djangoproject.com/en/4.1/) 
 7. [geeksforgeeks](https://www.geeksforgeeks.org/filefield-django-models/)
 8. Dennis Ivy