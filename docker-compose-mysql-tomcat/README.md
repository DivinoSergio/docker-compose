# Docker + Tomcat 10: Configuração de Servidor

Construir uma imagem com **Docker** para rodar um aplicação Web Java com **AS Tomcat 10.0**.
<br>Projeto gerado pela IDE Eclipse.


### Requisitos

<p align="center">
	<img loading="lazy" src="https://img.shields.io/badge/Eclipse-v2023--06-blue?logo=eclipse"/>
	<img loading="lazy" src="https://img.shields.io/badge/Tomcat-v10.0.34-blue?logo=apachetomcat"/>
	<img loading="lazy" src="https://img.shields.io/badge/MySQL-v9.0-blue?logo=mysql"/>
	<img loading="lazy" src="https://img.shields.io/badge/Java-v17-blue?logo=openjdk"/>
	<img loading="lazy" src="https://img.shields.io/badge/Git-v2.43.0-blue?logo=git"/>
	<img loading="lazy" src="https://img.shields.io/badge/Docker-v27.3.1-blue?logo=docker"/>
</p>

### Criando imagem Docker

```
docker compose -p app_mysql -f compose-db-war.yaml --env-file .env up -d --build
```
### Derrubar o Container 

```bash
docker compose -f compose-db-war.yaml down
```


# Referências

**Docker Hub - Tomcat**. Disponível em: <https://hub.docker.com/_/tomcat>. Acesso em: 06 jan. 2025.
**Docker Hub - MySQL**. Disponível em: <https://hub.docker.com/_/mysql>. Acesso em: 06 jan. 2025.