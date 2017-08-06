# Personal Blog

This project it's a simple blog app made in Django.
It was designed to serve a very particular purpose: to serve as a support for [my own publications](http://robsonfs.me). Do not expect to find here complex features like those you would find in [wordpress](https://github.com/WordPress/WordPress) (At least that's not the initial intention), but if you want to create your own personal blog in python / django, feel free to clone this repository and use it as You want.

## Requirements

* Python 3.6 or higher
* Django 1.11.4 or higher

## Run project in development mode

1. ``` virtualenv myblog -p /usr/bin/python3.6```
2. ``` source myblog/bin/activate```
3. ``` git clone git@github.com:robsonfs/personal-blog.git```
4. ``` cd personal-blog```
5. ``` pip install -r requirements.txt```
6. ``` python manage.py runserver```
7. Have fun.

## Run tests

```
python -m unittest
```
