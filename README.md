# MEAN Stack Sample Application

This is a simple CRUD application built using the MEAN (MongoDB, Express, Angular, Node.js) stack. You can also follow the step-by-step [tutorial](https://www.mongodb.com/languages/mean-stack-tutorial) for building this application.

![Demonstration of the web application](demo.gif)

## How To Run
Run mongodb in a docker container
 
 ```
 docker pull mongo
 docker run -it -p 27017:27017  --name mongodb -d mongo
```
 
 Set your [Atlas URI connection string](https://docs.atlas.mongodb.com/getting-started/) as a parameter in `server/.env`.

```
ATLAS_URI=mongodb://<VM IP>:27017/mean-stack-example
```
Note :To get VM IP, Go to Settings-> Network -> Wired Setting -> Copy IPv4 Address


Start the Client & Server applications with Dockerfile:
```
cd mean-stack-example
```
```
docker build -t serverclient .
```
```
docker run -p 5200:5200 -p 4200:4200 --net=host serverclient
```


When both applications are built and running, open your browser on http://localhost:4200/.