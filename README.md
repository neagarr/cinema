# Dockerized DRF Cinema

> Additional information or tagline

This is my second Django project.<br>
It is designed to organize all cinema processes

## Installing / Getting started

Python3.11 and Docker must be already installed
```
- run "git clone https://github.com/neagarr/cinema"
- run "cd cinema/"
- Run "sudo docker-compose up" command, and check with "docker ps", that 2 services are up and running;
- Go to "127.0.0.1:8000/api/" and check project endpoints via DRF interface;
```
## Features

What's all the bells and whistles this project can perform?
* Powerful admin panel for advanced managing
* Validated ticket serializer
* Filtering movies by title, genres, actors
* Order history with pagination
* Custom permissions used
* Implement ImageField for Movie with unique name
* Use email instead of username
* API documentation (Swagger UI)
* Implement throttling
* Used JSON Web Token Authorization
* API tests implemented
* Dockerized Cinema service with PostgreSQL
* Implemented "wait_for_db" which waits for the database to be available
* Implemented Docker Media Volumes
