# Hello World with JBoss EAP 8

This Helm chart packages an application with [JBoss EAP 8](https://www.redhat.com/en/technologies/jboss-middleware/application-platform).

The Jakarta EE application is at [https://github.com/jboss-developer/jboss-eap-quickstarts/tree/8.0.x/todo-backend](https://github.com/jboss-developer/jboss-eap-quickstarts/tree/8.0.x/todo-backend).

## Use the todobackend Web Frontend

Once the backend is deployed on OpenShift, it can be accessed from the route `todo-backend`.
This value will be different for every installation of the backend.

We can verify that this application is properly working as a ToDo Backend by running its https://todobackend.com/specs/index.html[specs] on it.

Once all tests passed, we can use the https://todobackend.com/client/index.html[todobackend client] to have a Web application connected to the backend.
