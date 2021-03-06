# THE NAME OF THE APP

### Instagram Clone

## AUTHOR

Patience Cyuzuzo

## DESCRIPTION

This is an application more or less like the popular social media platform Instagram where users can sign up, post pictures
view pictures posted by others comment on them as well as like or dislike the pictures


## User stories
As a user can do the following:
* Sign in to the application to start using
* Upload pictures to the application.
* View their profiles containing all their pictures
* A user can Follow other users and see their the users  timeline.
* Like a picture and leave a comment on it.

## Set Up and Installation

#### Prerequisites

* Python 3.6.2
* Virtual environment
* Postgres Database
* Reliable Internet Connection

## Installation Process

* Copy repolink

in your terminal run the following commands

* $ git clone REPO-URL in your terminal
* $ cd Instagram_clone
* $ python3.6 -m venv virtual
* $ touch .env ( to the file add :
        SECRET_KEY=<your secret key>
        DEBUG=True)
* $ source virtual/bin/activate
* $ python3.6 -m pip install -r requirements.txt
* $ psql ; CREATE DATABASE instagram ;

In the settings.py module of the project make the following changes

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'instagram',
        'USER': *POSTGRES_USERNAME*,
        'PASSWORD': *POSTGRES_USERNAME*,
    }
}

* $ python3.6 manage.py runserver (this command runs the application of port http://127.0.0.1/8000 )
 
## Known Bugs

No known bugs

## CREDITS

Moringa School,Python Documentation, StackOverflow.com and W3 schools

## Technologies Used

This project uses major technologies which are :

* HTML5/CSS
* Bootstrap
* Python3.6
* Django Frame Work
* Postgress Database
## License 

Copyright MIT [LiCENSE](./LICENSE) (c) 2021 [Patience Cyuzuzo](https://github.com/Pcyuzuzo/Instagram)

