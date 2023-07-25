# Lab - Class 31
## Project: drf-api

Author: Sarah Glass for Python 401

- Worked at a Remo table with Anthony, Slava, Logan, and Jared.

## Overview

- Use Django REST Framework to create an API, then “containerize” it with Docker.

**Feature Tasks and Requirements**

- Rebuild a custom version of Things API demo project from scratch.
- Replace things_project and Thing with your own application and model.
- Your model must have at least as many fields as demo’s model.
- Your model must have one field that is a foreign key to user.
- NOTE: You are not required to build any templates for this lab.


**Features - Docker**

- NOTE Refer to the class demo for built out Dockerfile and docker-compose.yml examples.
- Update Dockerfile and docker-compose.yml if needed.


## Links and Resources

* TA and peer help.
* Reviewing class demo.
* chatGPT helped with tests

## Setup

- No env variables -> used docker

## How to initialize/run your application

- python manage.py runserver
- docker compose up --build
- runs at `http://0.0.0.0:8000/api/v1/states/`

## Libraries / Requirements

asgiref==3.7.2
Django==4.2.3
djangorestframework==3.14.0
iniconfig==2.0.0
packaging==23.1
pluggy==1.2.0
pytest==7.4.0
pytz==2023.3
sqlparse==0.4.4

## Tests

Built-in Django testing

- python manage.py test