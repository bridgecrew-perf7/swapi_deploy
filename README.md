# SISGR - POC

Projeto conceito para utiliza��o de Servi�o Rest com Spring Boot

## Iniciando o Projeto

O projeto cont�m alguns exemplos de servi�o REST com integra��o com DB2 atrav�s de Stored Procedure. O projeto j� est� configurado para Rodar no Servidor Jboss.

### Pr� requisitos

Para rodar no modo dev, � necess�rio adicionar o  Argumento spring.profiles.active

```
-Dspring.profiles.active=dev
```

## Rodando os Testes

Para rodar o servi�o, � necess�rio rodar a classe ApiKeyHashGen para gerar a Hash

Utilize o postman (em anexo) e cole a hash gerada no parametro x-api-key na Aba Headers.

```
x-api-key : tJxjdeccaGKg...
```

## Rodando o SWAGGER

 Para rodar o Swagger, utilize o endpoint abaixo.
GET:/swapi/swagger-ui.html


## Deploy no JBoss

O projeto j� est� configurado para gerar o pacote compat�vel com o JBoss EAP 7.x. Basta executar o comando maven install



## Autores

* **Clayton Morais de Oliveira** 
