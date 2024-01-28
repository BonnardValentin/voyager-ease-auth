# VoyagerEase-Microservice-Planning

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/voyagerease/microservice-planification)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)

[![My Skills](https://skillicons.dev/icons?i=nestjs,typescript&perline=4)](https://skillicons.dev)

## Description

This repository hosts the source code and resources for the travel planning microservice as part of the VoyagerEase project. This microservice, developed with NestJS, follows the principles of Domain-Driven Design (DDD) to ensure an efficient and modular business-oriented design.

## Repository Structure

### 1. Source Code

- **src/** : Contains the microservice's source code.
  - **modules/** : The microservice modules, organized based on business domains.
    - **voyage/** : Module responsible for travel planning.
      - **domain/** : Contains entities, value objects, and aggregates related to the travel domain.
      - **application/** : Implements use cases and application services related to travel planning.
      - **infrastructure/** : Manages implementation details specific to infrastructure (databases, external APIs, etc.).
  - **common/** : Contains shared elements between modules, such as utilities, common middlewares, etc.

### 2. Documentation

- **docs/** : Microservice documentation.
  - **api-spec.yaml** : OpenAPI specification describing the microservice's API endpoints.
  - **user-guide.md** : Usage guide for developers integrating the microservice.

### 3. Configuration

- **config/** : Microservice configuration files.
  - **config.yaml** : General configuration for the microservice (settings, API keys, etc.).

### 4. Tests

- **tests/** : Unit tests and integration tests for the microservice.

### 5. Deployment

- **deploy/** : Scripts and configurations for deploying the microservice.
  - **Dockerfile** : Docker file for creating an image containing the microservice.
  - **kubernetes/** : YAML files for deployment on Kubernetes clusters.

### 6. Dependencies

- **vendor/** : Third-party dependencies for the microservice, if not managed by a package manager.

### 7. Contributing

- **CONTRIBUTING.md** : Guide for contributors to the microservice.

## Technologies Used

- Programming Language: TypeScript (NestJS)
- Database Management System: [Name of DBMS used, e.g., PostgreSQL, MongoDB]
- Build and Dependency Management Tools: npm or yarn
- Testing Tools: Jest

## DDD Architecture

The microservice is structured following the principles of Domain-Driven Design (DDD). Each module corresponds to a specific business domain, and the code is organized according to DDD concepts such as entities, value objects, and aggregates.

## Author

Development team name or lead developer's name.

## License

License under which the microservice is distributed, for example, MIT, Apache 2.0.
