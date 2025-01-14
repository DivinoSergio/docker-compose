# Docker + MySQL: Configuração de Servidor

Construir uma imagem com **Docker** para rodar um servidor de banco de dados **MySQL 8.0**.
<br>Projeto gerado pela IDE Eclipse.


### Requisitos

<p align="center">
	<img loading="lazy" src="https://img.shields.io/badge/Eclipse-v2023--06-blue?logo=eclipse"/>
	<img loading="lazy" src="https://img.shields.io/badge/MySQL-v8.0-blue?logo=mysql"/>
	<img loading="lazy" src="https://img.shields.io/badge/Java-v17-blue?logo=openjdk"/>
	<img loading="lazy" src="https://img.shields.io/badge/Git-v2.43.0-blue?logo=git"/>
	<img loading="lazy" src="https://img.shields.io/badge/Docker-v27.3.1-blue?logo=docker"/>
</p>

### Criando imagem Docker

```
docker compose -p servidor_mysql -f compose-db.yaml --env-file .env up -d
```
### Ativando Container 

```bash
docker compose -f compose-db.yaml down
```


# Referências

**Docker Hub - MySQL**. Disponível em: <https://hub.docker.com/_/mysql>. Acesso em: 06 jan. 2025.