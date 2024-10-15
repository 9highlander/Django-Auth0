# Django-Auth0
Simple Auht0 django implementation


## Installation

### Install `virtualenv` (optional)

```sh
python -m pip install virtualenv
```

### Create a Virtual Environment

```sh
python -m venv venv
```

| Code  | Explanation                     |
| ----- | ------------------------------- |
| `-m`  | executes module `venv`          |
| `env` | name of the virtual environment |

### Activate environment

```sh
source venv/bin/activate
```

### Install `requirements`

```sh
pip install -r requirements.txt
```

## Getting Started
1)Register an account on https://auth0.com/ 

2)Rename .env_example as .env and fill with your data

3)Rename .credential_example as .credntial and fill with your data

4)run followings command on terminal 
```sh
python manage.py migrate'
```

```sh
python manage.py runserver
```
then open the link
