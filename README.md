# Django + docker-compose

Bootstrap your django project inside docker.

## Usage

### Install cookiecutter
```shell
pip install cookiecutter
```

### Start your project
```shell
cookiecutter gh:cyriac/django-docker-compose-template
```

or 

```shell
cookiecutter https://github.com/cyriac/django-docker-compose-template
```

Once your project is bootstrapped, navigate to your project and start the app

```shell
docker-compose up
```