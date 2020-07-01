# my-first-docker-app

To containerize this app, follow these steps
Make sure you are in my-first-docker-app-pub folder on your system

docker build -t first-docker-app .

docker container run --name=first-docker-cont -d -p 8500:80 first-docker-app

