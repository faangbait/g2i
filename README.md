# G2I Image Builds

## Python 3.11

`make python-311 TARGET=c9s VERSIONS=3.11`
`docker push ...`

### Django 4

`docker build django/4 -t django-4:latest`
`docker push ...`

#### Application

`docker build . -t app:latest`
