# Docker + Tomcat 10: Configuração de Servidor

Construir uma imagem com **Docker** para rodar um aplicação Web Java com **AS Tomcat 10.0**.


### Requisitos

+ ![Docker](https://img.shields.io/badge/Docker-27.3.1-ce12230)

+ ![Git](https://img.shields.io/badge/Git-2.43.0-ce12230)

+ ![Tomcat](https://img.shields.io/badge/Tomcat-10.1.34-E3E3E3)

### Criando imagem Docker

```
docker build -t docker-tomcat .
```
### Ativando Container 

```bash
docker run -p 8080:8080 docker-tomcat
```

### Teste no navegador

```bash
http://localhost:8080/docker-tomcat/
```

# Referências

**Docker Hub - Tomcat**. Disponível em: <https://hub.docker.com/_/tomcat>. Acesso em: 06 jan. 2025.