# Docker + Tomcat 10: Configuração de Servidor

Construir uma imagem com **Docker** para rodar um aplicação Web Java com **AS Tomcat 10.0**.
<br>Projeto gerado pela IDE Eclipse.


### Requisitos

<p align="center">
	<img loading="lazy" src="https://img.shields.io/badge/Eclipse-v2023--06-blue?logo=eclipse"/>
	<img loading="lazy" src="https://img.shields.io/badge/Tomcat-v10.0.34-blue?logo=apachetomcat"/>
	<img loading="lazy" src="https://img.shields.io/badge/Java-v17-blue?logo=openjdk"/>
	<img loading="lazy" src="https://img.shields.io/badge/Git-v2.43.0-blue?logo=git"/>
	<img loading="lazy" src="https://img.shields.io/badge/Docker-v27.3.1-blue?logo=docker"/>
</p>

### Criando imagem Docker

```
docker compose -p servidor_mysql -f compose-db.yaml up -d
```
### Ativando Container 

```bash
docker compose -f compose-db.yaml down
```


# Referências

**Docker Hub - Tomcat**. Disponível em: <https://hub.docker.com/_/tomcat>. Acesso em: 06 jan. 2025.