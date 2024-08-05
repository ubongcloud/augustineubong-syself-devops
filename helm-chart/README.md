# Sample Backend Helm Chart

This Helm Chart deploys a sample backend application using Nginx.

## Components
- Deployment
- Service

## Configuration
The following table lists the configurable parameters of the chart and their default values.

| Parameter          | Description                  | Default            |
|--------------------|----------------------------- |--------------------|
| `replicaCount`     | Number of replicas           | `1`                |
| `image.repository` | Image repository             | `nginx`            |
| `image.tag`        | Image tag                    | `latest`           |
| `service.type`     | Service type                 | `ClusterIP`        |
| `service.port`     | Service port                 | `80`               |
