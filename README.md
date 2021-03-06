# ODH s2i Project Cookiecutter

_A logical, reasonably standardized, but flexible project structure for doing and sharing data science work._


#### [Project homepage](http://drivendata.github.io/cookiecutter-data-science/)


### Requirements to use the cookiecutter template:
-----------
 - Python 3.5+
 - [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0

``` bash
$ pip install cookiecutter
```

### To start a new project, run:
------------

    cookiecutter https://github.com/cfchase/odh-s2i=cookiecutter


### The resulting directory structure
------------

The directory structure of your new project looks like this: 

```
.
├── README.md
├── LICENSE
├── requirements.txt
├── 0_start_here.ipynb
├── 1_run_flask.ipynb
├── 2_test_flask.ipynb
├── .gitignore
├── .s2i
│   └── environment
├── gunicorn_config.py
├── prediction.py
└── wsgi.py
```
