# Infra generica com Websphere + DB2 + Jenkins

Este projeto visa fazer um deploy básico e padrão para uma infra com Websphere + DB2 automatizado com Jenkins. Para projetos desenvolvidos em Java.

> Este projeto visa faciliar o setup inicial de projetos do meu portifólio

Requisitos:

* Docker
* Docker compose

Basta iniciar com

```bash
docker compose -f docker-compose.jenkins.yml up --build
```

ou

```bash
docker compose -f docker-compose.jenkins.yml up -d
```
