# resumoApiREST


# Api REST e RESTFul

   A arquitetura de API REST (Representational State Transfer) é um conjunto de princípios orientadores para o desenvolvimento de interfaces web em sistemas. Ela segue um estilo de comunicação padronizado, baseado em recursos.

As APIs RESTful utilizam métodos HTTP para operações em recursos:

- **GET:** Recupera dados.
- **POST:** Cria novos recursos.
- **PUT:** Atualiza recursos existentes.
- **DELETE:** Remove recursos.
  Essa abordagem possibilita a criação de serviços web que são flexíveis, escaláveis e interoperáveis. Ela promove uma comunicação eficiente e simplificada entre sistemas.
 
  ## Diferenças entre REST e RESTFul

    REST é um conjunto de princípios e restrições para arquiteturas distribuídas, enquanto RESTful descreve a aplicação desses princípios na prática, especialmente em APIs e serviços web, garantindo que sigam as     diretrizes e restrições do REST para melhorar a interoperabilidade e a escalabilidade dos sistemas.

  **REST (Representational State Transfer):**
    - Define um estilo arquitetural para sistemas distribuídos.
    - Baseia-se em recursos, identificadores de recursos, métodos HTTP e hipermedia.
    - Não é uma especificação, mas um conjunto de princípios para design de sistemas escaláveis e flexíveis.

  **RESTful:**
    - Refere-se à aplicação dos princípios REST na construção de serviços web ou APIs.
    - Uma API é considerada RESTful quando segue os princípios do REST.
    - Utiliza métodos HTTP para operações CRUD, URIs para identificação única de recursos e códigos de status HTTP apropriados.

  ## HTTP verbs

  - **GET:** Recupera dados de um recurso específico.
  - **POST:** Cria um novo recurso.
  - **PUT:** Atualiza um recurso existente por completo.
  - **PATCH:** Atualiza parcialmente um recurso existente.
  - **DELETE:** Remove um recurso.

  ## HTTP Status Code

   O Status code é um número inteiro de 3 dígitos, onde o primeiro dígito define a classe da resposta, e os dois últimos dígitos não têm nenhuma função de categorização. Existem 5 valores para o primeiro dígito.    Sendo eles:
 
| S.N. | Code and Description                                     |
|------|----------------------------------------------------------|
| 1    | **1xx: Informational**                                   |
|      |Isso significa que a solicitação foi recebida e o processo continua. |
| 2    | **2xx: Success**                                         |
|      | Significa que a ação foi recebida, compreendida e aceita com sucesso.|
| 3    | **3xx: Redirection**                                     |
|      | Isso significa que outras ações devem ser tomadas para concluir a solicitação.|
| 4    | **4xx: Client Error**                                    |
|      | Isso significa que a solicitação contém sintaxe incorreta ou não pode ser atendida. |
| 5    | **5xx: Server Error**                                    |
|      | Isso significa que o servidor não atendeu a uma solicitação aparentemente válida. |

   Alguns códigos comuns são :

* **200 OK**: Indica que a requisição foi bem-sucedida.
* **201 Created**: Indica que a requisição foi bem-sucedida e resultou na criação de um novo recurso.
* **400 Bad Request**: Indica que a requisição foi malformada ou não pôde ser processada pelo servidor.
* **404 Not Found**: Indica que o recurso solicitado não foi encontrado no servidor.
* **500 Internal Server Error**: Indica que ocorreu um erro no servidor durante o processamento da requisição.

  Autor do resumo: Jordão Moura - 01567032

