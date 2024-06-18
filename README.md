# Jenkins Pipeline for Java Application

This Jenkins pipeline automates the build, Docker image creation, and deployment process for a Java application using Maven and Docker.

## Prerequisites

1. **Jenkins**: Ensure you have Jenkins installed and running.
2. **Maven**: Maven should be installed and configured in Jenkins (`maven3.9` in this case).
3. **Docker**: Docker should be installed and running on the Jenkins agent.
4. **Docker Hub Credentials**: Create a Jenkins credential with the ID `dockerhub` containing your Docker Hub username and password.

## Pipeline Overview

The pipeline consists of three main stages:

1. **Build JAR**: Compiles the Java application and creates a JAR file.
2. **Build Docker Image**: Builds a Docker image from the JAR file and pushes it to Docker Hub.
3. **Deploy**: Placeholder stage for deploying the application.
