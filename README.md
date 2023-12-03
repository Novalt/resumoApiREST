# resumoApiREST

# Api REST e RESTful
Uma API REST (Representational State Transfer) é um conjunto de princípios arquiteturais para projetar redes de comunicação baseadas em web. O principal objetivo é permitir a comunicação eficiente entre sistemas distribuídos. As APIs REST utilizam os princípios do protocolo HTTP (Hypertext Transfer Protocol) para criar serviços web padronizados e interoperáveis. Se tornando modos de desenvolvimento de interfaces web que seguem os padrões arquiteturais REST. As Api's RESTful são implementações mais próxima do modelo REST elas fornecem interfaces padronizadas. 

## Diferenças entre REST e RESTful
RESTFul é uma extensão do conceito de API REST, adicionando alguns princípios e práticas adicionais para melhorar a flexibilidade e a escalabilidade. Enquanto as APIs REST seguem os princípios do REST, as APIs RESTFul incorporam boas práticas adicionais, como a utilização de URI (Uniform Resource Identifier) para identificar recursos de maneira mais semântica e a utilização de verbos HTTP de maneira adequada.
A diferença do Api REST e RESTful está na aderência aos princípios do REST pois o APIs REST seguem princípios mais básicos enquanto o RESTful adotam uma implementação mais completa.
Enquanto o REST é uma arquitetura de software de dados
e comunicação na web, o RESTful se basea aos padrões do REST, que segue regras de comunicação cliente/servidor possui metodos e interfaces bem definidas baseadas em protocolo HTTP e HTTPs, portanto a pricipal diferença entre REST e RESTful está na contrção da aplicação seguindo boas praticas.

## HTTP verbs
São verbos HTTP, também conhecidos como métodos HTTP, são ações que podem ser realizadas em recursos identificados. Alguns dos principais verbos HTTP são:

GET: Recupera dados de um recurso.
POST: Cria um novo recurso.
PUT: Atualiza um recurso existente.
DELETE: Remove um recurso.
PATCH: Aplica modificações parciais a um recurso.
OPTIONS: Retorna os métodos HTTP suportados em um recurso.

## HTTP status code
Indica se uma solicitação HTTP foi concluida com exito.Por exemplo mandando alguma resposta se foi bem sucedida 200 que é status OK e o famoso 404 que é um tipo de resposta do erro do lado do cliente em que o servidor não consegue precossar o que foi feito, um erro de sitaxe por exemplo ou seja o status HTTP indicam o resultado da solicitação feita ao servidor. 

Alguns códigos comuns são:

200 OK: A solicitação foi bem-sucedida.
201 Created: A solicitação foi bem-sucedida e resultou na criação de um novo recurso.
204 No Content: A solicitação foi bem-sucedida, mas não há conteúdo para enviar.
400 Bad Request: A solicitação não pôde ser entendida ou estava faltando parâmetros obrigatórios.
401 Unauthorized: A solicitação requer autenticação.
404 Not Found: O recurso solicitado não foi encontrado no servidor.
500 Internal Server Error: Indica um erro interno no servidor.



<br><br>
Autor do resumo : Rodin Sarmento Bezerra - 01507133
