# KinoroomProject
Repository containing all microservices + gateway I made for my 6th semester of Software Engineering of Fontys University of Applied Sciences

## Technologies used
- .NET Core 6 (C#)
- Docker
- Kubernetes
- Docker
- Snyk
- Sonarcloud
- Azure
- KrakenD
- RabbitMQ
- Grafana
- InfluxDB


## API Endpoints (from gateway)
SearchQuery has the following endpoints:
HTTP method | API endpoints             | Description
------------|---------------------------|---------------------------
 GET        | /api/v1/Movies            | Get all movies
 GET        | /api/v1/Movies/{id}       | Get movie by ID
 POST       | /api/v1/Movies            | Create movie
 PUT        | /api/v1/Movies            | Update movie
 DELETE     | /api/v1/Movies/{id}       | Delete movie
 GET        | /api/v1/Forums            | Get all forums
 GET        | /api/v1/Forums/{id}       | Get forum by ID
 POST       | /api/v1/Forums            | Create forum
 PUT        | /api/v1/Forums            | Update forum
 DELETE     | /api/v1/Forums/{id}       | Delete forum
 GET        | /api/v1/Threads           | Get all threads
 GET        | /api/v1/Threads/{id}      | Get thread by ID
 POST       | /api/v1/Threads           | Create thread
 PUT        | /api/v1/Threads/{id}      | Update thread
 DELETE     | /api/v1/Threads/{id}      | Delete thread
