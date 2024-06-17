

# Learning Docker

## Introduction to Docker

[Docker](https://www.docker.com/) is a platform for developers to develop, deploy, and run applications with containers. Containers allow a developer to package up an application with all of the parts it needs, such as libraries and other dependencies, and ship it all out as one package.

## Basics of Docker

### What is a Container?

A container is a lightweight, standalone, executable package of software that includes everything needed to run an application: code, runtime, system tools, system libraries, and settings.

### Docker vs. Virtual Machines

Docker containers are lightweight because they share the host system's kernel and do not require a full operating system per application, unlike virtual machines.

### Key Docker Components

- **Docker Engine**: The core service that creates and runs containers.
- **Dockerfile**: A text file that contains instructions on how to build a Docker image.
- **Docker Image**: A read-only template used to create containers.
- **Docker Container**: A runnable instance of a Docker image.

## Getting Started with Docker

### Installation

Follow the official Docker installation guide for your operating system:
- [Docker Desktop for Windows](https://docs.docker.com/desktop/windows/install/)
- [Docker Desktop for Mac](https://docs.docker.com/desktop/mac/install/)
- [Docker Engine for Linux](https://docs.docker.com/engine/install/)

### Hello World Example

1. Verify Docker installation:
   ```bash
   docker --version
   ```

2. Run your first container:
   ```bash
   docker run hello-world
   ```

This command downloads the `hello-world` image from Docker Hub and runs a container based on that image.

## Further Learning Resources

- [Docker Documentation](https://docs.docker.com/)
- [Docker Hub](https://hub.docker.com/) - Repository of Docker images
- [Docker Tutorial on YouTube](https://www.youtube.com/watch?v=fqMOX6JJhGo) - Video tutorial for beginners

