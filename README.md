# kong-gateway
Sample demonstration of how kong gateway can work.

# Pre requisites
Docker, Node JS

# Steps to run
1. Run docker-compose.yml up -d
2. This should start 4 containers. (Kong, Postgres, 2 sample apis)
3. From the attached postman collection, create a new service for each api. With the respective port number and hostname
4. Add routes to the service. 
5. Test if the routes are working.

# Reference
Detailed explanation can be found in the README.md - https://github.com/trevorkennedy/kong_docker_demo/blob/master/README.md
Inspired by: https://github.com/trevorkennedy/kong_docker_demo