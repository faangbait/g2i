# G2I Image Builds

Glass2Image: containerized builds for personal use; leverages the S2I pipeline.

## Python 3.11

`make python-311 TARGET=c9s VERSIONS=3.11`

`docker push ...`

### Django 4

`docker build django/4 -t django-4:latest`

`docker push ...`

#### Demo Application

`docker build demo -t demo:latest`
