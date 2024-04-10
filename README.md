# Sprint1-BD

Caso o grupo opte por um banco de dados relacional a entrega será: 

Projeto de Banco de Dados Relacional (até 50 pontos):

Diagramas:

Modelo Entidade-Relacionamento (MER) – Modelo Físico: Utilize o Oracle Data Modeler para construir o MER, seguindo a notação de Barker. Garanta que o modelo esteja na 3ª Forma Normal (3FN), otimizando a organização dos dados e evitando redundâncias.

Diagrama Entidade-Relacionamento (DER) – Modelo Lógico: Com base no MER, desenvolva o DER, também utilizando a notação de Barker. O DER deve refletir fielmente a estrutura lógica do banco de dados planejado.

Modelo Físico e Criação de Esquema:

Gere o Modelo Físico a partir do seu projeto lógico e utilize os scripts SQL para criar os objetos do esquema no banco de dados, incluindo tabelas, chaves primárias, chaves estrangeiras, e outros objetos necessários. (10 pontos)

Preenchimento de Dados:

Para cada tabela, insira no mínimo 5 registros, que devem ser coerentes com a especificação do projeto. Esses dados servirão como base para as consultas e análises subsequentes. (20 pontos)

Consultas e Blocos Anônimos:

Desenvolva dois blocos anônimos PL/SQL que demonstrem a utilização dos dados inseridos, incluindo no mínimo 3 consultas de junções (JOINs). Cada consulta deve demonstrar o uso de agrupamento (GROUP BY) e ordenação (ORDER BY) de dados. (20 pontos)

Entregável:

Um arquivo zipado contendo:

O PDF do Projeto de Banco de Dados Relacional.

Arquivos .sql com os scripts organizados por tabela.

PDFs dos modelos lógico e físico.

Observação:

A clareza e organização dos arquivos entregues são essenciais para a avaliação. É importante que os scripts SQL, modelos e documentos estejam bem organizados e sejam facilmente acessíveis para garantir uma avaliação adequada. Falhas na organização do conteúdo podem resultar em uma redução da nota.





Caso o grupo opte por um banco de dados não relacional, a entrega será:

Projeto de Banco de Dados Não Relacional (até 40 pontos):

Documento de Projeto:

Apresente uma descrição detalhada do projeto e a justificativa para a escolha de um Banco de Dados NoSQL.

Explique qual tipo de banco de dados NoSQL foi escolhido (documentos, colunas, grafos, chave-valor) e por que ele é o mais adequado para as necessidades do projeto.

Esquema/Modelo de Dados e Justificativas:

Forneça uma descrição ou esquema dos modelos de dados usados, incluindo como as estruturas de dados se alinham com os requisitos do projeto.

Discuta qualquer índice proposto, operações de consulta otimizadas e como o esquema contribui para a performance e escalabilidade.

Construção de Dados e Operações (até 60 pontos):

Dependendo do banco de dados escolhido, realize as seguintes tarefas:

Para MongoDB: Crie 5 documentos em .JSON (ou BSON), cada um com no mínimo 10 atributos. Implemente operações de agregação, buscas textuais e/ou geoespaciais, documentando cada operação.

Para Redis: Crie 5 chaves com valores de exemplos preenchidos, utilizando diferentes tipos de dados oferecidos pelo Redis. Descreva como transações ou padrões de design avançados são aplicados.

Para Neo4j: Desenvolva um conjunto de pelo menos 5 tipos de nós com relações entre eles, demonstrando como as conexões modelam os relacionamentos do domínio de seu projeto. Inclua exemplos de consultas Cypher que demonstrem buscas complexas e padrões de relacionamento.

Para Cassandra: Projete e implemente pelo menos 5 tabelas, levando em consideração a modelagem baseada em consulta para otimizar a leitura e a escrita. Documente as decisões de modelagem, incluindo a escolha de chaves primárias e índices secundários.

Análise de Performance e Escalabilidade:

Para o banco de dados escolhido, forneça uma breve análise sobre as expectativas de performance para as operações de consulta implementadas e discuta como o sistema pode ser escalado.

Segurança e Integração:

Elabore sobre medidas de segurança recomendadas para proteger os dados. Descreva também como o banco de dados pode ser integrado a outras aplicações ou sistemas.

Entregável:

Um arquivo zipado contendo o PDF do Projeto de Banco de Dados Não Relacional e os arquivos de script referentes ao banco de dados escolhido.

Observação:

A boa organização do conteúdo dos arquivos é de suma importância para apontamento da nota, caso haja falha nesta organização a correção pode vir a ser comprometida acarretando diminuição da nota.
