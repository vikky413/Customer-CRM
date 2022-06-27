MEAN Stack Sample Application 
This is a simple CRUD application built using MEAN Stack. 

Run with docker-compose file 

1. Set ATLAS_URI parameter in .env file of server
	
   ATLAS_URI=mongodb://localhost:27017/mean-stack-example

   (Change localhost to db i.e service name of database in docker-compose file)
   
   ATLAS_URI=mongodb://db:27017/mean-stack-example

2. Run docker-compose file to start all containers:

   command : docker-compose up -d

When both applications are running, open your browser on http://localhost:4200/.
