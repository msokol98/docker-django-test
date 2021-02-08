# docker-django-test

This is a quick test application to verify that dockerization of djagno app works on both Windows and Linux.

Terminal commands:

 ``` 
git clone https://github.com/msokol98/docker-django-test.git
cd docker-django-test
docker-compose build
docker-compose up
 ``` 
 
Visit localhost:8000/hello in any web browser. It should return "Hello World".
