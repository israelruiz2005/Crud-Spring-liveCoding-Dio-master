# Gerenciador de salas de reunioes

## Stack utilizada:


 * Spring Web
 * Spring Data JPA
 * H2 Database
 * Java 8
 * Maven
 
## Endpoints criados na API

| Verbo 	| Endpoint      	| Descrição                	|
|-------	|---------------	|--------------------------	|
| POST  	| /api/v1/rooms 	| Cria sala de reunião     	|
| GET   	| /api/v1/rooms 	| Lista todas as salas   	|
| GET      	| /api/v1/rooms/{id}| Pesquisa sala por Id      |
| PUT      	| /api/v1/rooms/{id}| Atualiza sala por Id      |
| DELETE   	| /api/v1/rooms/{id}| Exclui sala por Id        |

# Um pouco de teoria
Você sabe o que é API? Essas três letras formam a sigla para Application Programming Interface, que pode ser traduzido como “Interface de Programação de Aplicações”.

As API são conjuntos de instruções e padrões de programação que servem para fornecer dados e informações relevantes de uma determinada aplicação.
Elas utilizam verbos para definir qual é a finalidade da requisição que está sendo enviada. Os verbos são:

**GET**: A requisição é um pedido de dados para a API. A API vai buscar os dados solicitados em algum banco e, provavelmente, vai retornar em formato JSON (formato de notação de objeto JavaScript);

**POST**: Tipo de requisição utilizada para criar um recurso em uma determinada API. São chamados de recursos o objeto que está sendo tratado naquela API.

**PUT**: Requisição utilizada para atualizar o recurso indicado com alguma informação.

**PATCH**: Requisição feita para atualização de somente uma parte de um recurso.

**DELETE**: Requisição para excluir um dado.

São acessadas por meio de Endpoints, que são as URLs nas quais são feitas as requisições. Cada requisição aos endpoints é composta por:

**O método HTTP**

**Cabeçalho requisição**,
- Que pode conter informações como dados de autenticação da API, dados de origem da requisição e formato do retorno.
  Embora o corpo da requisição e do retorno possam utilizar outros formatos, de modo geral é utilizado o formato JSON como padrão, tanto para o envio quanto para o retorno das requisições. Esse formato é escolhido, principalmente, por sua compatibilidade simples entre as linguagens e frameworks existentes, tanto de backend quanto de frontend.

### Status HTTP

o grupo padrão dos status HTTP para indicar se uma requisição teve sucesso ou não. No geral:

-**Códigos HTTP 2XX:** indicam que a requisição foi realizada com sucesso;

-**Códigos HTTP 4XX:** indicam que a requisição contém alguma informação incorreta - dados de acesso incorretos, ausência de um campo obrigatório, etc;

-**Códigos HTTP 5XX:** indicam algum erro nos servidores da API.

# Referências

[Live Digital Innovation One dessa aplicação](https://www.youtube.com/watch?v=_2gRnfJeyMM)





 
