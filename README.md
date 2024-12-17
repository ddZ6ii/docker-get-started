# First Steps with Docker

This project setups the minimal configuration to run a fullstack application containerized with Docker.

The application is shipped with the following container:

- app: javascript
- client: react + typescript (vite)
- server: express + mongodb

## Get started

First make sure both Docker and Docker Compose are properly installed in your machine by running the following commands:

```sh
docker version
docker-compose version
```

> [!TIP]  
> Using VS Code? Make sure to have the [official Docker extension](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)

To start the application in the development environment, simply run:

```sh
docker compose -f compose.dev.yaml up -d
```

Finally open a browser and visit the URL: http://localhost:8080/

## Author

- Github - [@ddZ6ii](https://github.com/ddZ6ii)
