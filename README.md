# Streaming Docker

Este proyecto configura una aplicación de streaming utilizando Docker y Nginx. Está diseñado para facilitar el despliegue y gestión de servicios de streaming en un entorno de desarrollo o en producción.

## Estructura del Proyecto

- `.env`: Archivo de variables de entorno (no debe compartirse públicamente).
- `.env.example`: Ejemplo para crear el archivo `.env` con variables necesarias.
- `docker-compose.yml`: Archivo de configuración para el despliegue con Docker Compose.
- `config/nginx.conf`: Configuración principal de Nginx para enrutamiento y proxy.
- `certs/`: Certificados y parámetros de seguridad, incluyendo `dhparam.pem` para SSL/TLS.
- `web/`: Carpeta principal de la aplicación web.
  - `web/config/nginx.conf`: Configuración de Nginx específica de la aplicación.
  - `web/public/index.html`: Archivo de entrada de la interfaz web.

## Requisitos

- **Docker** y **Docker Compose** instalados en tu máquina.
- Crear un archivo `.env` basado en `.env.example` y configurar las variables necesarias.

## Uso

1. **Clonar el repositorio**:

   ```bash
   git clone https://github.com/AlenSaavedra/streaming-docker
   cd streaming-docker
