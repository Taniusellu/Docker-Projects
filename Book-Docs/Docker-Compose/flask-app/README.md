Let's quicly describe each file: 

* app.py - is the app code (a Python Flask app). 
* docker-compose.yml - is the Docker Compose file that describes how Docker should deploy the app
* Dockerfile - describes how to build the image for the web-fee service 
* requirments.txt - lists the Python packages rewuired for the app 

Note: 
   - The app.py is obviously the core of app. But docker-compose.yaml is the glue that sticks all the app components together. 


Run the bellow commands: 

```
docker-compose up &
```
check images
```
docker images    
```
check containers 
```
docker ps
```
check network 
```
docker network ls
```
check volumes
```
docker volume ls
```

You should be able to access your app

<img width="345" alt="docker4" src="https://user-images.githubusercontent.com/13994900/100533790-c6e6c000-31cd-11eb-8ad3-cc454d4cfd02.PNG">

Note: Every time when you access your app, automatically in your shell will show that logs was collected .
