# This Branch do the deployment into AWS EKS using Helm charts

# Application Description:
  - NestJS Application with npm package manager
  - Create uses in DB using HTTP POST and retrive them using HTTP GET
  - Two Docker containers
    1. Front end to handle API requests and for the busness logic 
      - image: thush1990/repo1:api2 <- Built using Dockerfile and uploaded to my DockerHub
    2. Postgres DB
      - image: postgres:latest

# Behaviour 
- Docker compose up <- Run using Docker compose in your local machine
- HTTP GET -> ALB:3000 -> "Hello World!"
- HTTP GET -> ALB:3000/users -> [Output all the users]
- HTTP POST {"name" : "Thushara" } -> ALB:8080/users -> [save use in postgres DB]

# Resources
https://www.youtube.com/watch?v=BrlQthcUHGw
https://www.youtube.com/watch?v=jYFyLLqvHy8