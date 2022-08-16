## Prerequisites

- Python version 3.9.13
- Poetry

## Installation Flow
- Setup environment
```bash
poetry install
```

## setting env
- copy .env.sample -> .env
- change variable env


### env connect to postgres db
  ```dotenv
      DB_HOST=
      DB_PORT=
      DB_NAME=
      DB_USER=
      DB_PASSWORD=
  ```

## migrate database
```bash
    python manage.py migrate
  ```

### Config setting users account
pip install -U djoser

### Authenticate using JWT
pip install -U djangorestframework_simplejwt

## make migrations
default create migrations
```bash
    python manage.py makemigrations
  ```

## Frontend
```bash
    npx create-react-app frontend
```

### Setting send email
https://djoser.readthedocs.io/en/latest/settings.html