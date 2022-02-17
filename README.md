# Microservice - Spring Cloud

Micro serviço desenvolvido para o armazenamento de configurações globais em repositórios no GitHub. O servidor gerencia essas configurações (que podem ser em arquivos .properties ou .yml) e as distribui para os clientes. 


## Linguagens e tecnologias utilizadas

- Spring Boot
- Spring Cloud


## Dependências

No [inicializador spring](https://start.spring.io/), as dependências adicionadas foram:
**App Servidor**
- Config Server

**App Cliente**
- Spring Web
- Devtools
- Actuator
- Config Client

## Importante
A aplicação do cliente utiliza uma configuração presente [nesse repositório](https://github.com/claramartins2002/spring-cloud-configuration) para enviar uma mensagem inicial em http://localhost:9080/hello. Outro ponto importante: Primeiramente, o servidor precisa ser inicializado, para depois o cliente, senão ocorre erro de compilação. 



