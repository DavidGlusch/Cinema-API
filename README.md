# CINEMA API

REST API for cinema

Technologies used:
- Django REST Framework
- PostgreSQL
- Docker
## Installing using GitHub:

```shell
  git clone https://github.com/DavidGlusch/Cinema-API.git
  cd cinema_api
  python -m venv venv
  venv\Scripts\activate (on Windows)
  source venv/bin/activate (on macOS)
  pip install -r requirements.txt
```

## Run with docker:
```shell
  docker-compose up --build
```


## Features:

- Authenticate with JWT
- Admin panel (/admin/)
- SWAGGER documentation (/api/doc/swagger/) 
- Managing orders and tickets
- Creating cinema halls
- Creating movies with genres, actors
- Adding movie sessions
- Filtering movies and movie sessions

## Access:
- creating user (/api/user/register/) 
- get a JWT token to use (/api/user/token/)
