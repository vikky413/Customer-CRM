# MEAN Stack Sample Application

This is a simple CRUD application built using the MEAN (MongoDB, Express, Angular, Node.js) stack. You can also follow the step-by-step [tutorial](https://www.mongodb.com/languages/mean-stack-tutorial) for building this application.

![Demonstration of the web application](demo.gif)

## How To Run
Run mongodb in a docker container
 
 ```
 docker pull mongo
 docker run -d -p 27017:27017  --name mongotest mongo:latest
```
 
 Set your [Atlas URI connection string](https://docs.atlas.mongodb.com/getting-started/) as a parameter in `server/.env`.

```
ATLAS_URI=mongodb://localhost:27017/mean-stack-example
```

Start the server application:
```
cd server
```
```
npm install
```
```
npm start
```

Start the client application:
```
cd client
```
```
npm install
```
```
npm start
```
When both applications are built and running, open your browser on http://localhost:4200/.


## Contributors ✨

<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center">
        <a href="https://github.com/AbiramiSukumaran">
            <img src="https://avatars.githubusercontent.com/u/13735898?v=4" width="100px;" alt=""/><br />
            <sub><b>Abirami Sukumaran</b></sub>
        </a><br />
    </td>
    <td align="center">
        <a href="https://twitter.com/StanimiraVlaeva">
            <img src="https://avatars.githubusercontent.com/u/7893485?v=4" width="100px;" alt=""/><br />
            <sub><b>Stanimira Vlaeva</b></sub>
        </a><br />
    </td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

## Disclaimer

Use at your own risk; not a supported MongoDB product

