# Buildx Docker Compose Example
This is a basic example of a use case for Buildx with Docker Compose

## Requirements:
- Docker Engine Version >= 19.03
- Docker Compose Version >= 2
- Docker Buildx Enabled

## Commands to Build

#### Localhost:
```bash
docker buildx bake --pull
```

or

#### Push to Container Registry
```bash
docker buildx bake --push
```

## Reference
- https://docs.docker.com/reference/cli/docker/buildx/bake/
- https://docs.docker.com/build/bake/reference/
- https://docs.docker.com/compose/compose-file/build/