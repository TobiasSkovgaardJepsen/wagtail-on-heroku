# Introduction
A basic Wagtail project ready to be deployed on Heroku. You can see a deployed version of the project [here](https://wagtail-on-heroku.herokuapp.com/).

The project is an extension of [the Heroku Django Starter Template](https://github.com/heroku/heroku-django-template). Instructions on how to deploy to Heroku can be found in their README.

If you are new to Wagtail, please visit the [Wagtail Tutorial](http://docs.wagtail.io/en/v1.13.1/getting_started/tutorial.html). After installation of this project you can continue from step 3 of the tutorial.

# Installation
1. Clone the repository:
```
git clone https://github.com/TobiasSkovgaardJepsen/wagtail-on-heroku.git
```

2. Step into the project directory:
```
cd wagtail-on-heroku
```

3. Install the project dependencies:
```
pipenv install
bash build_wagtail.sh
```

# Other remarks
At the time of development the Wagtail versions available through the Python Package Index (PIP) did not support Django 2.0. The project therefore currently contains a local version of the latest version of Wagtail which supports Django 2.0. This has some implications for the license, see LICENSE.txt.
