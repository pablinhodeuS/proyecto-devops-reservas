# SaludConecta – Proyecto DevOps

Aplicación web estática que simula un sistema de reserva de horas médicas, desarrollada mediante HTML, CSS, Nginx y Docker.

## Objetivo

Implementar una aplicación web utilizando prácticas DevOps relacionadas con control de versiones, construcción de imágenes, despliegue mediante contenedores y monitoreo básico.

## Metodología ágil

El proyecto utiliza Kanban para organizar las actividades de planificación, desarrollo, construcción, pruebas, despliegue y documentación.

Las tareas se registran mediante GitHub Issues, permitiendo visualizar los requisitos y mantener un seguimiento de las actividades.

## Estrategia de control de versiones

La rama `main` contiene el código principal del proyecto.

Las modificaciones se realizan mediante ramas independientes, que permiten desarrollar cambios sin alterar directamente la versión principal.

Los cambios se registran mediante commits descriptivos y posteriormente pueden incorporarse mediante pull requests.

## Tecnologías utilizadas

- HTML5 y CSS3.
- JavaScript básico.
- Nginx Alpine.
- Docker Desktop y Docker Compose.
- Git y GitHub.

## Ejecución del proyecto

Para construir y ejecutar el sistema:

```bash
docker compose build
docker compose up -d
```

La aplicación se encuentra disponible en:

http://localhost:8080

Para revisar el estado:

```bash
docker compose ps
```

Para detener el servicio:

```bash
docker compose down
```

## Seguridad

La plataforma tiene fines exclusivamente académicos. No almacena información personal ni genera reservas reales. No requiere base de datos ni API.

## Versión

Primera versión identificada mediante la etiqueta `v1.0.0`.
