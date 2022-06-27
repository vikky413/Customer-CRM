MEAN Stack Sample Application 
This is a simple CRUD application built using MEAN Stack. 


Run Manually:

1. Run mongodb in a docker container
 
 	docker pull mongo

	docker run -d -p 27017:27017  --name mongotest mongo:latest 

2. Set ATLAS_URI paramter in .env file of server

	ATLAS_URI=mongodb://localhost:27017/mean-stack-example  

3. Run Server

	cd server
	npm install
	npm start

4. Run Client 

	cd client
	npm install
	npm start

When both applications are running, open your browser on http://localhost:4200/.
