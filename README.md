# Virtual Library API
Implementação de uma API para a gestão de uma livraria virtual.

## Autores  
* Dalmo Melo
* Walter Coelho

## End Points  
* GET /api/Todo = Recupera todos os items
* GET /api/Todo/{id} = Recupera o item identificado pelo id
* POST /api/Todo = Cria novo item.
Payload:
{
  "name":"String",
  "isComplete":boolean
}
* PUT /api/Todo/{id} = Atualiza item existente.
Payload:
{
  "id":number
  "name":"String",
  "isComplete":boolean
}
* DELETE /api/Todo/{id} = Apaga registro existente.

## Documentação  
https://localhost:5001/swagger/v1/swagger.json
