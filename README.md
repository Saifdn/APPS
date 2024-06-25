# APPS

Advanced Production Planning System (APPS) is an application for manufacturing company to plan their production in certain range. The mathematical model that we are using are based on the undisclosed company's case study. The documentation can be read on "Multiperiod Production Smoothing Problem.pdf" file. To solve the mathematic model, we utilized the PuLp algorithm from python library which can be used to solve linear programming problems.


## HOW TO RUN THIS PROJECT
- Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python)

- Download This Project Zip Folder and Extract it
- Move to project folder in Terminal. Then run following Commands :

## Install Widget Tweaks
```
pip install django-widget-tweaks
```

## Install Django Compressor
```
pip install django_compressor
```

## Install python XLWT library
```
pip install xlwt
```

## Install PuLp library
```
pip install pulp
```

## Install django-environ 0.9.0
```
pip install django-environ
```

## Install plotly
```
pip install plotly
```

## Run Server

```
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

- Now enter following URL in Your Browser Installed On Your Pc
```
http://127.0.0.1:8000/
```
