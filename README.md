# Projeto: Deploy Contínuo

## Desafio Final
Imagem publicada no Docker Hub:

**[https://hub.docker.com/r/alleycarvalho/desafio-final](https://hub.docker.com/r/alleycarvalho/desafio-final)**

Executando container localmente para testes:
```
docker run -d --name desafio-final -p 8000:80 --rm alleycarvalho/desafio-final
```

Verificar aplicação no browser (Local):

**[http://localhost:8000/](http://localhost:8000/)**

### Print da execução (CI) no Cloud Build:
![CI](/desafio-final-ci.png)

### Print da execução (CI/CD) no Cloud Build:
![CI](/desafio-final-ci-cd.png)

Verificar aplicação no browser (Web):

**[http://35.193.73.44/](http://35.193.73.44/)**
