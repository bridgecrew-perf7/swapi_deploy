# SWAPI - POC 

Projeto conceito para utilização de Serviços Rest com Spring Boot

## Iniciando o Projeto

O projeto contém alguns exemplos de serviços REST. O projeto está configurado para rodar em standalone e deploy no wildfly

### Pré requisitos

```
Java 8 : (https://www.oracle.com/br/java/technologies/javase/javase-jdk8-downloads.html);

Wildfly 10.0.1.Final :  (https://download.jboss.org/wildfly/10.1.0.Final/wildfly-10.1.0.Final.zip)

Spring Boot na versão 2.3.12.RELEASE :  (https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-dependencies/2.3.12.RELEASE);

Eclipse NEON ou superior : (https://www.eclipse.org/downloads/packages/release/mars/r/eclipse-ide-java-ee-developers);

Postman para Testes : (https://www.postman.com/downloads/)
```

## Rodando os Testes

Utilize o postman Para rodar os testes.

Collection está na raiz do repositório.


```
SWAPI - API - LOCAL.postman_collection.json
```

## Rodando o SWAGGER

 Para rodar o Swagger, utilize o endpoint abaixo.
GET:/swagger-ui.html

## Rodando local

Para rodar no modo dev, é necessário adicionar o Argumento:

```
-Dspring.profiles.active=dev
```

Inicie com a classe Application.java


## Deploy

Basta executar o comando maven install e efetuar o deploy no wildfly pelo eclipse



## Autores

* **Clayton Morais de Oliveira** 
