# api-graphql
A GraphQL API to provide IoT-Hub data to clients

# Build and tag with Docker

`docker build -f deployments/Dockerfile -t diwise/api-graphql:latest .`

# Run with Docker

`docker run -it -p 8080:8080 diwise/api-graphql:latest`
