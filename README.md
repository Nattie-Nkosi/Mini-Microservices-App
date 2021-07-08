# Mini-Microservices-App
A Mini Microservices app done in React and node Js on the backend. Used Docker to create containers and Images for each service and push them to Docker Hub. Used Kubernetes for deployment. 

## Technolodies used
- React Js
- Node Js
- Docker
- Kubernetes
- Skaffold

## Lessons from the App
- The big challenge in microservices is data
- Different ways to share data between services. Async communication.
- Async communication focuses on communicating changes using events sent to an event bus.
- Async communication encourages each service to be 100% self-sufficient. Relatively easy to handle temporary downtime or new service creation.
- Docker makes it easier to package up services.
- Kubernetes is a pain to setup, but makes it easy to deploy + scale services
