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