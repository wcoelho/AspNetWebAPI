# Tutorial ASP.NET Web API  
Passo a passo para a criação de uma aplicação com uma API mínima utilizando a tecnologia ASP.NET Core 2.1, com publicação através do Swagger e plugin Swashbuckle.

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
