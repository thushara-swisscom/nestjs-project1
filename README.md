# This Branch do the deployment in your local machine using Docker-compose 

# Application Description:
  - NestJS Application with npm package manager
  - Create uses in DB using HTTP POST and retrive them using HTTP GET
  - Two Docker containers
    1. Front end to handle API requests and for the busness logic 
    2. Postgres DB

# Behaviour 
- Docker compose up <- Run using Docker compose in your local machine
- HTTP GET -> localhost:8080 -> "Hello World!"
- HTTP GET -> localhost:8080/users -> [Output all the users]
- HTTP POST {"name" : "Thushara" } -> localhost:8080/users -> [save use in postgres DB]

# Resources
https://www.youtube.com/watch?v=BrlQthcUHGw
https://www.youtube.com/watch?v=jYFyLLqvHy8
