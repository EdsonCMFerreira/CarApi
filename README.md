Projeto de uma minimal API com os métodos GET, POST e DELETE usando por base uma lista JSON.
 
Endpoint's implementados no projeto:
- GET cars que possibilita listar dos registros name, year
- GET car que possibilita consultar um registro por name
- POST car que possibilita incluir um registro 
- DELETE cars que possibilita remover todos registros
 
Documentação MinimalApis: https://learn.microsoft.com/en-us/aspnet/core/fundamentals/minimal-apis?view=aspnetcore-7.0

Para consumir os dados desta API foi criado o projeto ClientApiChampionsDevs que tem interface prompt e que consome os endpoints da API.

O Projeto que consome a API ClientApiChampionsDevs está em https://github.com/EdsonCMFerreira/ClientApiChampionsDevs
