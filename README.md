# ![RealWorld Crizmas MVC](crizmas.png)

> ### crizmas-mvc codebase containing real world examples (CRUD, auth, advanced patterns, etc) that adheres to the [RealWorld](https://github.com/gothinkster/realworld) spec and API.


This codebase was created to demonstrate a fully fledged fullstack application built with **[crizmas-mvc](https://github.com/raulsebastianmihaila/crizmas-mvc)** including CRUD operations, authentication, routing, pagination, and more.


## To run it locally  with Dockerfile:

1. Clone repo
2. `cd crizmas-mvc-realworld-example-app` 
3. `docker build . -t mbnism/crizmas`
4. `docker run -p 8080:8080 -d mbnism/crizmas`
4. open http://localhost:8080/


## To run it in your local kubernetes cluster:

1. Clone repo
2. `cd crizmas-mvc-realworld-example-app` 
3. `docker build . -t mbnism/crizmas`
4. `kubectl apply -f sw-deployment.yaml`
5. `kubectl apply -f sw-service.yaml`
6. open http://localhost:8080/


