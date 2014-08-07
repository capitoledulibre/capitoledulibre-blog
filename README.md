# Capitole du Libre blog site

Capitole du Libre blog site, based on mezzanine, a django project for blog system.

## Installation

* Clone it

* Create a virtualenv

    cd capitoledulibre-blog
    virtualenv .

* Deploy the blog project

    cp local_settings.py.example local_settings.py # set all your local settings there, as database connection
    python manage.py syncdb
    python manage.py migrate
    python manage.py runserver
