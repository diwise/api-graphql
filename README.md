# api-graphql
A GraphQL API to provide IoT-Hub data to clients

# Build and tag with Docker

```bash
docker build -f deployments/Dockerfile -t diwise/api-graphql:latest .
```

# Build and run with Docker Compose

```bash
docker compose -f deployments/docker-compose.yaml build
docker compose -f deployments/docker-compose.yaml up
```
