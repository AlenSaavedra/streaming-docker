# Streaming Docker

This project sets up a streaming application using Docker and Nginx. It is designed to simplify the deployment and management of streaming services in both development and production environments.

## Project Structure

- `.env`: Environment variables file (should not be shared publicly).
- `.env.example`: Example file for creating the `.env` file with required variables.
- `docker-compose.yml`: Configuration file for deployment using Docker Compose.
- `config/nginx.conf`: Main Nginx configuration for routing and proxy settings.
- `certs/`: Security certificates and parameters, including `dhparam.pem` for SSL/TLS.
- `web/`: Main folder for the web application.
  - `web/config/nginx.conf`: Nginx configuration specific to the application.
  - `web/public/index.html`: Entry file for the web interface.

## Requirements

- **Docker** and **Docker Compose** installed on your machine.
- Create an `.env` file based on `.env.example` and configure the necessary variables.

## Usage

1. **Clone the repository**:

   ```bash
   git clone https://github.com/AlenSaavedra/streaming-docker
   cd streaming-docker
   ```
