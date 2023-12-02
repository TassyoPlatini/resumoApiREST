# resumoApiREST

## Api REST e RESTFul

Uma API, ou interface de programação aplicativos, é um conjunto de regras que definem como aplicativos ou dispositivos podem se conectar e se comunicar uns com os outros. Uma API de REST é uma API que se adéqua aos princípios de design do REST ou o estilo de arquitetura do Representational State Transfer.  Por esta razão, as APIs de REST são muitas vezes chamadas de APIs de RESTful. REST não é um protocolo ou padrão, mas sim um conjunto de restrições de arquitetura. Os desenvolvedores de API podem implementar a arquitetura REST de maneiras variadas.
Algumas APIs, como SOAP ou XML-RPC, impõe um framework restrito para os desenvolvedores. Porém, as APIs de REST podem ser desenvolvidas usando praticamente qualquer linguagem de programação e oferecem suporte a uma variedade de formatos de dados. O único requisito é que eles devem alinhar aos seis princípios de design de REST a seguir, conhecidos como restrições de arquitetura:
- **Interface Uniforme:** Todas as solicitações para o mesmo recurso devem seguir o mesmo padrão, independente da origem.

- **Desacoplamento Cliente-Servidor:** Aplicativos cliente e servidor devem ser independentes.

- **Sem Estado Definido:** Cada solicitação contém todas as informações necessárias para ser processada.

- **Capacidade de Armazenamento em Cache:** Recursos podem ser armazenados em cache no cliente ou servidor para melhorar desempenho e escalabilidade.

- **Arquitetura de Sistema em Camadas:** Chamadas e respostas passam por diferentes camadas.

- **Código sob Demanda (Opcional):** As respostas podem, em casos específicos, conter código executável, mas isso é opcional.

A API RESTful serve como uma interface que possibilita a troca segura de informações entre dois sistemas computacionais por meio da internet. Na maioria das aplicações de negócios, é essencial estabelecer comunicação entre sistemas internos e de terceiros para realizar diversas tarefas. Por exemplo, para automatizar o processo de faturamento e gerar contracheques mensais, o sistema interno de contas precisa compartilhar dados de maneira eficiente com o sistema bancário do cliente e interagir com uma aplicação interna de registro de horas. As APIs RESTful facilitam essa troca de dados, proporcionando padrões de comunicação seguros, confiáveis e eficientes para suportar essas operações.

## Diferenças entre REST e RESTFul

REST estabelece os princípios, enquanto RESTful é a materialização desses princípios em implementações reais de APIs, proporcionando diretrizes para uma comunicação eficiente e padronizada entre sistemas distribuídos.

## HTTP verbs

Os métodos HTTP, também conhecidos como HTTP verbs, são ações padronizadas que indicam a natureza da operação que um cliente solicita a um servidor. Cada método representa uma intenção específica, contribuindo para a comunicação eficiente entre sistemas na arquitetura REST. Aqui estão alguns dos principais métodos HTTP:

- **GET:** Utilizado para recuperar dados de um recurso específico no servidor.

- **POST:** Utilizado para enviar dados ao servidor para criar um novo recurso.

- **PUT:** Utilizado para atualizar dados de um recurso ou criar um recurso se ele não existir.

- **DELETE:** Utilizado para solicitar a remoção de um recurso no servidor.

- **PATCH:** Utilizado para realizar modificações parciais em um recurso.

- **HEAD:** Similar ao GET, mas usado para obter apenas os cabeçalhos da resposta, sem o corpo.

- **OPTIONS:** Utilizado para obter informações sobre as opções de comunicação disponíveis para um recurso ou servidor.
  
- **TRACE:** Usado para testar a conectividade entre o cliente e o servidor, rastreando o caminho da requisição.

## HTTP Status Code

SN   |     Código e Descrição 
--------- | ------
1xx: Informational | Isso significa que a solicitação foi recebidae o processo continua.
2xx: Success    | Significa que a ação foi recebida, compreendida e aceita com sucesso.
3xx: Redirection | Isso significa que outras ações devem ser tomadas para concluir a solicitação.
4xx: Client Error | Isso significa que a solicitação contém sintaxe incorreta ou não pode ser atendida.
5xx: Server Error | Isso significa que o servidor não atendeu a uma solicitação aparentemente válida.

---

Autor do resumo: Tássyo Platiní de Souza Gonçalves  - 01516372
