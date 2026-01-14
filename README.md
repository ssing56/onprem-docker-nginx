
# On-Prem Docker NGINX Deployment

## Overview
This project demonstrates deploying a simple NGINX web service using Docker and Docker Compose in an on-prem style setup. The service is managed using systemd and includes log rotation configuration.

---

## Features
- Custom NGINX Docker image
- Docker Compose with restart policy
- Bind-mounted logs
- systemd service to manage docker-compose
- Log rotation using logrotate
- Application exposed on port 8080

---

## Components
- Docker
- Docker Compose
- systemd
- logrotate
- NGINX

---

## Service Access
The application is exposed on port **8080** and can be accessed using:

```bash
curl http://localhost:8080
