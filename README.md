# 3-tier-web-apps-deployment-for-dynatrace-monitoring

	How to deploy 3-tier web application using docker compose.:
	
	To install a 3-tier web application using Docker Compose, and need to set up the following components:
	
		1. Frontend (Tier 1): A web server or client application (e.g., an Angular/React app or a simple Nginx server serving static files).
		2. Backend (Tier 2): An API or application server (e.g., Node.js, Python Flask, or Java Spring Boot).
		3. Database (Tier 3): A database server (e.g., MySQL, PostgreSQL).
		
	Below is a step-by-step guide to configure and deploy this setup using Docker Compose.
	
	Software requirement: 
		· Docker 
		· Docker compose
		· Git 
		· Python 
		
	Steps: 
		1. Clone git repository  https://github.com/akshaydevops97/3-tier-web-app-deployment-for-dynatrace-monitoring.git 
		2. Deploy the Application 
         docker-compose up -d
		3. Check the running containers 
		         docker ps
	  4. Access the Application  
               http://<public-ip>:8080
	               http://<public-ip>:5050
	  5. Stop & cleanup the package 
                  docker-compose down

