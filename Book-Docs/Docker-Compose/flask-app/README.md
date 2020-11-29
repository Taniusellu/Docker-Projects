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
