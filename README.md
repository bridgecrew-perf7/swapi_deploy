# SISGR - POC

Projeto conceito para utilizaçáo de Serviço Rest com Spring Boot

## Iniciando o Projeto

O projeto contém alguns exemplos de serviço REST com integração com DB2 através de Stored Procedure. O projeto já está configurado para Rodar no Servidor Jboss.

### Pré requisitos

Para rodar no modo dev, é necessário adicionar o  Argumento spring.profiles.active

```
-Dspring.profiles.active=dev
```

## Rodando os Testes

Para rodar o serviço, é necessário rodar a classe ApiKeyHashGen para gerar a Hash

Utilize o postman (em anexo) e cole a hash gerada no parametro x-api-key na Aba Headers.

```
x-api-key : tJxjdeccaGKg...
```

## Rodando o SWAGGER

 Para rodar o Swagger, utilize o endpoint abaixo.
GET:/swapi/swagger-ui.html


## Deploy no JBoss

O projeto já está configurado para gerar o pacote compatível com o JBoss EAP 7.x. Basta executar o comando maven install



## Autores

* **Clayton Morais de Oliveira** 
