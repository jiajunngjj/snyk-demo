# nodejs-express-helloworld 

A simple Hello World node.js application using Express framework:

  * A simple Express `Hello World!` on port 8000
  * A Dockerfile to deploy with Docker
  * Kubernetes YAML files for creating a service and a load balancer.

## Run application with Docker container

### Build the Docker image

```
docker build . -t jiajunngjj/nodejs-sample-app
```

### Run the Docker container

```
docker run -p 8000:8000 -d jiajunngjj/nodejs-sample-app
```

## Run application with Node.js

### Packaging the application

```
npm install
```

### Starting the application

```
npm start
```
