#1 Describe the app
#2 Tell docker how to containeriza the application - create an image with the app inside 

FROM alpine       
LABEL mantainer="tatianamoraru.tech@gmail.com"
RUN apk add --update nodejs nodejs-npm
COPY . /src
WORKDIR /src
RUN npm install
EXPOSE 8080
ENTRYPOINT ["node", "./app.js"] 

#FROM - the base layer of an image

# docker image build -t 1_app:latest . 
