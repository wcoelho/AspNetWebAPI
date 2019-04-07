# ASP.NET Web API  
Código feito a partir de tutorial para a criação de uma aplicação com uma API mínima utilizando a tecnologia ASP.NET Core 2.1, com publicação através do Swagger e plugin Swashbuckle.

**Fontes:**  
* [ASP Net] (https://docs.microsoft.com/pt-br/aspnet/core/web-api/?view=aspnetcore-2.1)
* [Swashbuckle/Swagger] (https://docs.microsoft.com/pt-br/aspnet/core/tutorials/getting-started-with-swashbuckle?view=aspnetcore-2.1&amp;tabs=visual-studio-code%2Cvisual-studio-xml)


## End Points  
* GET /api/Todo = Recupera todos os items.  
* GET /api/Todo/{id} = Recupera o item identificado pelo id.  
* POST /api/Todo = Cria novo item.  
Payload:  
{  
  "name":"String",  
  "isComplete":boolean  
}  
* PUT /api/Todo/{id} = Atualiza item existente.  
Payload:  
{  
  "id":number,  
  "name":"String",  
  "isComplete":boolean  
}  
* DELETE /api/Todo/{id} = Apaga registro existente.  

## Documentação  
Estando a aplicação em execução, acesse a URL:  
https://localhost:5001/swagger/v1/swagger.json
