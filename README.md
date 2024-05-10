# Roots/Bedrock with Docker Training Repository

This repository serves as a training resource for getting started with [Roots/Bedrock](https://roots.io/bedrock/) using Docker. Roots/Bedrock is a WordPress boilerplate that helps you manage your WordPress project's dependencies with Composer and provides a modern directory structure for your WordPress project.

## Getting Started

To use this repository for training purposes, follow the steps below:

### Prerequisites

- Docker Desktop: [Install Docker Desktop](https://www.docker.com/products/docker-desktop) for your operating system.
- Docker Compose: [Install Docker Compose](https://docs.docker.com/compose/install/) for your operating system.
- Git: [Install Git](https://git-scm.com/) for version control.


### Start the Docker Containers

Navigate into the cloned repository directory and start the Docker containers using Docker Compose:

```
cd bedrock-docker-training
cd wp
make config
cd ..
docker-compose up -d
```

This command will spin up the necessary Docker containers for running Roots/Bedrock.

### Access WordPress

Once the containers are up and running, you can access WordPress by visiting [http://localhost:80](http://localhost:80) in your web browser. Follow the WordPress installation instructions to set up your WordPress site.

### Development Workflow

You can develop your WordPress site by making changes to the files in the `web/app/themes` directory for themes and `web/app/plugins` directory for plugins. Any changes you make will be reflected in real-time as the Docker containers are running.

### Stopping the Containers

To stop the Docker containers, run the following command:

```docker-compose down ```


### Further Resources

- [Roots/Bedrock Documentation](https://roots.io/bedrock/docs/)
- [Docker Documentation](https://docs.docker.com/)

## Contributing

Contributions to this repository are welcome. If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This repository is provided for training purposes without any specific license. Feel free to use, modify, and distribute it as needed for your training sessions.



