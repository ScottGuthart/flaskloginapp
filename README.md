# flaskloginapp
Flask App Template

Inspired by and modeled after [Miguel Grinberg's Flask Tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world). Check out this resource to understand more about how this code works.

Includes:
* Login with email confirmation
* Bootstrap 4 via [bootstrap-flask](https://github.com/greyli/bootstrap-flask)
* Heroku Procfile
* Redirect to HTTPS and Content Security Policy (CSP) Support* via [flask-talisman](https://github.com/GoogleCloudPlatform/flask-talisman)
* Blueprint app structure
* Easy database upgrades via [flask-migrate](https://flask-migrate.readthedocs.io/en/latest/)
    
<sub><sup>*This template ships with a more relaxed CSP than included with flask-talisman by default in order to allow Bootstrap 4 to work properly. Please refer to flask-talisman documentation to decide what's right for your site.</sup></sub>

## Basic Setup
* Set up a virtual environment and install the requirements [more info](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world)
* Create a .env file in the root directory (/.venv) [more info](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-x-email-support)
    * Set up your gmail accout to allow third party sign-in. See above link for more info.
    * Sample .env file:
        FLASK_APP=flaskapp
        MAIL_SERVER=smtp.googlemail.com
        MAIL_PORT=587
        MAIL_USE_TLS=1
        MAIL_USERNAME=example@gmail.com
        MAIL_PASSWORD=examplepassword
        SECURITY_PASSWORD_SALT=put_your_password_salt_here
        SECRET_KEY=put_your_secret_key_here
* In config.py, edit the admins list so that the first entry uses your 

