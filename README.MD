This repository tracks the deployment of the lime survey application implemented for a client.
The application mostly consists of Kubernetes manifests available at infrastructure/ directory.

The stack consists of the following:
- Lime Survey Application
- Mysql Database
- Superset Database

Deploy with "kubectl apply -f infrastructure/overlays/prod"
