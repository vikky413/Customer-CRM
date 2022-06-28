# MEAN Stack Sample Application

This is a simple CRUD application built using the MEAN (MongoDB, Express, Angular, Node.js) stack. You can also follow the step-by-step [tutorial](https://www.mongodb.com/languages/mean-stack-tutorial) for building this application.

![Demonstration of the web application](demo.gif)

## How To Run

 Set your [Atlas URI connection string](https://docs.atlas.mongodb.com/getting-started/) as a parameter in `server/.env`.

```
ATLAS_URI=mongodb://db:27017/mean-stack-example
```
Note: db is the name of database service in docker-compose.yaml


Start the Client & Server applications with docker-compose:
```
docker-compose up -d
```

When both applications are built and running, open your browser on http://localhost:4200/.