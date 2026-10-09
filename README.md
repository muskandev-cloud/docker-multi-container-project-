# Docker Multi-container Environmnet 

## Project Overview 

This project demonstrates a prectical multi-caotainter Docker environment using Docker Compose It integrates an Nginx web server, Alpine Linux container, custom Docker networking, and persistent Docker volumes.

## Ojectives 

- Deploy multiple container using Docker Compose 
- Configure a Custom Docker network 
- Enable container-to-container communication 
- Deploy an Nginx web server 
- Implement persistent storage using Docker volume 
- Verify container and sevice funtionality 

## Technologies used 

- Docker 
- Dokcer compose 
- Nginx 
- Alpine linux 
- Docker Bridge Network 
- Docker volumes 
- Rocky Linus 

## Architecure 

```text 
                Docker Compose
                      |
             +--------+--------+
             |                 |
             v                 v
        Nginx Container    Alpine Container 
             |                 |
             +--------+--------+
                      |
             Docker Compose Network 
                      |
               persistent Volume 
