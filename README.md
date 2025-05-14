# taskapp

Idea de organización de archivos (se puede como deseen pero es una idea inicial)

- frontend/ - Aplicación web construida en React
- api-gateway/ - Configuración de Nginx como API Gateway
- users-service/ - Microservicio de autenticación (registro y login)
- tasks-service/ - Microservicio de gestión de tareas (CRUD)
- notifications-service/ - Microservicio de notificaciones (recordatorios)
- docker/ - Archivos Dockerfile y docker-compose.yml
- k8s/ - Archivos YAML de configuración de Kubernetes
- .github/workflows/ - Workflows para CI/CD con GitHub Actions

## Tecnologías Principales

- **Frontend:** React, Nginx (API Gateway)
- **Backend:** Firebase (Firestore + Auth), Python (alternativa), REST API
- **Contenedores:** Docker
- **Orquestación:** Kubernetes
- **CI/CD:** GitHub Actions
- **Testing:** Jest / Vitest, Postman