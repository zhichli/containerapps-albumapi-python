# Azure Container Apps Album API

This is the companion repository for the [Azure Container Apps code-to-cloud quickstart](https://docs.microsoft.com/en-us/azure/container-apps/quickstart-code-to-cloud?tabs=bash%2Ccsharp&pivots=acr-remote).

This backend Album API sample is available in other languages:

| [C#](https://github.com/azure-samples/containerapps-albumapi-csharp) | [Go](https://github.com/azure-samples/containerapps-albumapi-go) | [JavaScript](https://github.com/azure-samples/containerapps-albumapi-javascript) | [Java](https://github.com/azure-samples/containerapps-albumapi-java) |
| -------------------------------------------------------------------- | ---------------------------------------------------------------- | ------------------------------------------------------------------------ | ---------------------------------------------------------------- |

## Running with Docker

### Prerequisites
- Docker
- Docker Compose (optional)

### Build and Run with Docker

Build the Docker image:
```bash
docker build -t albumapi-python .
```

Run the container:
```bash
docker run -p 8000:8000 albumapi-python
```

### Using Docker Compose

Run with Docker Compose:
```bash
docker compose up
```

Stop the services:
```bash
docker compose down
```

### Testing the API

Once running, the API will be available at `http://localhost:8000`:

- Root endpoint: `http://localhost:8000/`
- Albums endpoint: `http://localhost:8000/albums`
