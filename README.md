Meddy
==========

Welcome to the Meddy repository. By reading this file, we're guessing that you are either a hacker, or a recent immigrant to the Meddy world, welcome stranger.

## Prerequisites:
This application requires Django 1.6.5, if you don't have it you can get it by:

```
    # Installing pip (Python Package Index)
    $ sudo easy_install pip

    # Installing Django 1.6.5
    $ sudo pip install django==1.6.5
    
    # Installing Dependencies
    $ sudo pip install django-endless-pagination
    $ sudo pip install django-analytical
    $ sudo pip install south # deprecated but we still like it
    $ sudo pip install Pillow # to take a nap, and to load images
    $ sudo pip install python-social-auth # because social media is a thing

    #RespectTheCode 1 Line Install Dependencies (Don't do this if you already did the above)
    $ sudo pip install django-endless-pagination django-analytical south Pillow python-social-auth

```

## Installation & Running the Application

```
    # Navigate to a directory to save the app
    $ cd /path/to/save/app

    # Download the app
    $ git clone https://github.com/haghadi/meddy.git

    # Switch to that directory
    $ cd meddy

    # Run the application (localhost:8000)
    $ python manage.py runserver
```

To run the application on a different port: `$ python manage.py runserver 8008` where 8008 is the port number that you want.

... and that's it :)!

## Developers:
Haris Aghadi, Abdulla AlKhenji# meddyco
