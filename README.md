# Kubernetes Demo Project: MongoDB and Mongo Express

This is a demo project to deploy MongoDB and Mongo Express using Kubernetes. The project includes two pods: one for MongoDB and another for Mongo Express. MongoDB is an open-source NoSQL database, and Mongo Express is a web-based MongoDB admin interface.

## Prerequisites

- Kubernetes cluster
- `kubectl` command-line tool configured to interact with the cluster
- Docker (to build images if necessary)

## Project Structure

- `mongodb-deployment.yaml`: Deployment for MongoDB
- `mongo-express-deployment.yaml`: Deployment for Mongo Express
- `mongodb-service.yaml`: Internal service for MongoDB
- `mongo-express-service.yaml`: Internal service for Mongo Express
- `mongo-secret.yaml`: Secret for MongoDB credentials
- `mongo-configmap.yaml`: ConfigMap for MongoDB configuration

## Deployment Instructions

1. **Clone the repository**

   ```sh
   git clone <repository-url>
   cd <repository-folder>
