# DIO - Trilha .NET - API e Entity Framework
Desafio de projeto para conclusão do bootcamp .NET developer fornecido pela [DIO](www.dio.me).

## Desafio de projeto
Para este desafio, foram utilizados os conhecimentos adquiridos no módulo de API e Entity Framework, da trilha .NET da DIO para desenvolver um sistema de gerenciamento de tarefas utilizando Swagger, C# e SQL Server.

## Contexto
Foi solicitado aos alunos finalizarem um sistema que está pela metade de cadastramento de tarefas. 
 
A classe principal, a classe de tarefa, deve ser a seguinte:

![Diagrama da classe Tarefa](diagrama.png)

**Endpoints**


| Verbo  | Endpoint                | Parâmetro | Body          |
|--------|-------------------------|-----------|---------------|
| GET    | /Tarefa/{id}            | id        | N/A           |
| PUT    | /Tarefa/{id}            | id        | Schema Tarefa |
| DELETE | /Tarefa/{id}            | id        | N/A           |
| GET    | /Tarefa/ObterTodos      | N/A       | N/A           |
| GET    | /Tarefa/ObterPorTitulo  | titulo    | N/A           |
| GET    | /Tarefa/ObterPorData    | data      | N/A           |
| GET    | /Tarefa/ObterPorStatus  | status    | N/A           |
| POST   | /Tarefa                 | N/A       | Schema Tarefa |

Esse é o schema (model) de Tarefa, utilizado para passar para os métodos que exigirem

```json
{
  "id": 0,
  "titulo": "string",
  "descricao": "string",
  "data": "2022-06-08T01:31:07.056Z",
  "status": "Pendente"
}
```


## Solução
O código foi finalizado conforme solicitado e está dispónível no repositório. Este repositório será arquivado e caso deseje alterações ou conversar sobre o projeto, faça um Pull request ou entre com contato comigo via [LinkedIn](https://www.linkedin.com/in/hugo-cs-souza/).
