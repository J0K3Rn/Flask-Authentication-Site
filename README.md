# Flask-Authentication-Site

Flask Site that uses user-authentication and disallows unregistered users from accessing a secret file 

Features:
- Allows users to register and login to accounts
- User info stored in database
- Passwords are encrypted with sha256 and a salt
- Uses LoginManager for authentication
- Uses Flask flash to give user info on why register/login failed
- Secret file that can only be accessed by logged-in users

How to run:
- Download repository
- Open downloaded repository with a command line interface
- run `pip install flask`
- run `pip install Werkzeug`
- run `pip install Flask-SQLAlchemy`
- run `pip install flask_login`
- run `python main.py`
- Go to `127.0.0.1:5000/` to view site

Home Page:

![alt text](https://github.com/J0K3Rn/Flask-Authentication-Site/blob/main/screenshots/home_page.png?raw=true)

Incorrect Password Prompt on Login-in Page:

![alt text](https://github.com/J0K3Rn/Flask-Authentication-Site/blob/main/screenshots/incorrect_password_prompt.png?raw=true)

Logged-In Page:

![alt text](https://github.com/J0K3Rn/Flask-Authentication-Site/blob/main/screenshots/logged_in_page.png?raw=true)

Secret File:

![alt text](https://github.com/J0K3Rn/Flask-Authentication-Site/blob/main/screenshots/secret_file.png?raw=true)
