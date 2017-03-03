# vuejs-vertx-keycloak-example

## Pré Requisitos

- Java 8
- NodeJS
- Docker

## Setup

### Install Keycloak

docker run -e KEYCLOAK_USER=admin -e KEYCLOAK_PASSWORD=admin -p 9080:8080 jboss/keycloak


npm install keycloak-js --save