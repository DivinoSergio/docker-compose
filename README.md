# docker-compose
Estudos com Docker.

# Docker + Tomcat + MySQL: Configuração de Servidor e Carregamento Automático de Dados

O processo de **automação**
da inicialização e configuração de bancos de dados **MySQL** em contêineres Docker é facilitado por meio de uma abordagem que permite a execução automática de **scripts SQL** durante o processo de inicialização. Esses scripts, que podem conter comandos para criação de esquemas, inserção de dados iniciais e configuração de parâmetros do banco de dados, são executados de forma automática e ordenada.

Essa funcionalidade é particularmente útil em ambientes onde é necessário configurar e manter bancos de dados de maneira eficiente e padronizada, como em ambientes de desenvolvimento, teste e produção baseados em contêineres. Além disso, essa abordagem promove a consistência e a **reaproveitamento** nas configurações de bancos de dados, garantindo que as mesmas configurações possam ser aplicadas de forma confiável em diferentes instâncias do MySQL em contêineres Docker.

Em resumo, essa abordagem **simplifica** o processo de inicialização e **configuração** inicial de bancos de dados MySQL em contêineres Docker, oferecendo uma maneira conveniente e confiável de **automatizar tarefas** comuns de configuração.


### Requisitos

<p align="center">
	<img loading="lazy" src="https://img.shields.io/badge/Tomcat-10.0.34-blue?logo=apachetomcat"/>
	<img loading="lazy" src="https://img.shields.io/badge/Java-17-blue?logo=openjdk"/>
	<img loading="lazy" src="https://img.shields.io/badge/MySql-8.0-blue?logo=mysql"/>
	<img loading="lazy" src="https://img.shields.io/badge/Git-2.43.0-blue?logo=git"/>
	<img loading="lazy" src="https://img.shields.io/badge/Docker-27.3.1-blue?logo=docker"/>
	<img loading="lazy" src="https://img.shields.io/badge/Maven-3.9.3-blue?logo=apachemaven"/>
</p>

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

Initializing a fresh instance, **Docker Hub - Tomcat**. Disponível em: <https://hub.docker.com/_/tomcat>. Acesso em: 06 jan. 2025
