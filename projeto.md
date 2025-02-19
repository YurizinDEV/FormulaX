
# PROJETO DE SOFTWARE

## *Stakeholders*
|NOME|CARGO|E-MAIL|
|:---|:---|:---|
|Matheus Lucas Batista|Gerente de projeto/Analista|matheusifro2020@gmail.com|
|Marco Antonio Augusto de Andrade|Cliente/Professor|marco.andrade@ifro.edu.br|
|Luis Felipe Lopes|Analista|luis.felipe.lopes1275@gmail.com|
|Thiago Hens Suchi|Analista|thiagohenssuchi@gmail.com|
|Yuri Ribeiro Zetoles|Analista|yurizetoles0123@gmail.com|


# Sumário

* [RESUMO DO PROJETO](#resumo-do-projeto)
* [INTRODUÇÃO](#introdução)
  * [PROPÓSITO DESTE DOCUMENTO](#propósito-deste-documento)
  * [CONCEPÇÃO DO SISTEMA](#concepção-do-sistema)
* [DESCRIÇÃO GERAL](#descrição-geral)
  * [USUÁRIOS DO SISTEMA](#usuários-do-sistema)
  * [ABRANGÊNCIA E SISTEMAS SIMILARES](#abrangência-e-sistemas-similares)
  * [SUPOSIÇÕES E DEPENDÊNCIAS](#suposições-e-dependências)
* [ESTUDO DE VIABILIDADE](#estudo-de-viabilidade)
* [METODOLOGIA ADOTADA NO DESENVOLVIMENTO](#metodologia-adotada-no-desenvolvimento)
* [REQUISITOS DO SOFTWARE](#requisitos-do-software)
  * [REQUISITOS FUNCIONAIS](#requisitos-funcionais)
  * [REQUISITOS NÃO FUNCIONAIS](#requisitos-não-funcionais)
* [PROTOTIPAGEM](#prototipagem)
* [DIAGRAMA DE CASOS DE USO](#diagrama-de-casos-de-uso)
  * [ESPECIFICAÇÃO DOS CASOS DE USO](#descrição--especificação-dos-casos-de-uso)
* [DIAGRAMA DE CLASSES](#diagrama-de-classes)
* [DIAGRAMA DE SEQUÊNCIAS](#diagrama-de-sequências)
* [ DIAGRAMA DE ATIVIDADES](#diagrama-de-atividades)
* [REFERÊNCIAS](#referências)


# RESUMO DO PROJETO

|XX| XX|
|:---|:---|
| NOME|Fórmula X|
| Lider do Projeto|Matheus Lucas Batista|
| PRINCIPAL OBJETIVO |Prototipar uma plataforma de gerenciamento de cursos|
| BENEFÍCIOS ESPERADOS |Redução de custos com licenças de cursos, Autonomia de criação de conteúdo, Democratização do ensino|
| INÍCIO E TÉRMINO PREVISTOS |01/10/2024 - 11/03/2025|


# INTRODUÇÃO
A plataforma "Fórmula X" nasceu da necessidade de disponibilizar conteúdos extras e promover a continuidade do aprendizado, principalmente para alunos que precisam de aprofundamento em disciplinas específicas. Utilizamos como referência a ideia de MOOC (Massive Open Online Courses) para atingir um maior número de pessoas, oferecendo flexibilidade e escalabilidade.  


## PROPÓSITO DESTE DOCUMENTO

O objetivo deste documento é descrever a concepção do sistema, seus requisitos, escopo e metodologia de desenvolvimento adotada, servindo como base para a equipe na implementação e sustentação do projeto.  

## CONCEPÇÃO DO SISTEMA

Métodos utilizados para a obtenção dos requisitos do sistema:
Métodos utilizados para a obtenção dos requisitos do sistema:  
  * Brainstorming e discussões entre os stakeholders;  
  * Análise de necessidades e expectativas de alunos;  
  * Protótipos iniciais no Figma;  
  * Definição de prioridades e funcionalidades-chave por meio de Kanban.
    
---  

# DESCRIÇÃO GERAL


## Usuários do sistema
|USUÁRIO|DESCRIÇÃO|
|:---|:---|
|**Usuário Padrão:**|Alunos e interessados em cursos online|



### Sistemas similares:
O projeto se assemelha a plataformas como Coursera e Udemy, cujos objetivos incluem a hospedagem, organização e disponibilização de cursos de diversos temas. No entanto, a “Fórmula X” busca oferecer uma experiência mais direcionada a conteúdos complementares de acordo com as necessidades de cada aluno na instituição.  


## Suposições e dependências

Os clientes (alunos e professores) devem utilizar um computador com a seguinte configuração mínima:  

* Processador Dual Core 2GHz ou superior;
* 2Gb de memória RAM;
* 5Gb de armazenamento em disco;
* Para uso do sistema é preciso ter instalado o Java para Web browsers.

---  

# ESTUDO DE VIABILIDADE

Após identificar a demanda por material de apoio em formato virtual, analisou-se a viabilidade técnica e financeira do projeto, considerando os recursos necessários para hospedagem, desenvolvimento e manutenção. Concluiu-se que a criação de uma plataforma MOOC é viável, trazendo benefícios de acessibilidade e flexibilidade na aprendizagem.  

--- 

# Metodologia Adotada no Desenvolvimento
Foi adotado um modelo de desenvolvimento baseado em Kanban, contemplando análise de Throughput, Lead Time e Cycle Time para monitorar o progresso do projeto. Também foram utilizados protótipos no Figma para validação prévia da interface, além de revisões e ajustes contínuos com a equipe.  


[ [INÍCIO](#projeto-de-software) ]

---  

# Requisitos do Software

A especificação dos requisitos deste projeto segue as recomendações da norma IEEE Std-830-1998, considerando as boas práticas para definição de requisitos.  

## Requisitos Funcionais

A tabela a seguir contém a relação dos Requisitos Funcionais elicitados, com as colunas: identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME                    | DESCRIÇÃO                                                                                                                                          |  
|:-------------|:------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------|  
| **RF-001**   | Gerenciar Cursos        | Permite ao administrador criar, atualizar e remover cursos, bem como incluir módulos e conteúdos extras para disponibilizar aos alunos.             |  
| **RF-002**   | Inscrição em Cursos     | Possibilita que os alunos se inscrevam nos cursos disponíveis, visualizem o material e acompanhem seu progresso dentro da plataforma.             |  



## Requisitos Não Funcionais
A tabela a seguir contém a relação com os Requisitos Não Funcionais identificados, contendo identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME                           | DESCRIÇÃO                                                                                                |  
|:-------------|:-------------------------------|:----------------------------------------------------------------------------------------------------------|  
| **RNF-001**  | Desempenho                      | O sistema deve suportar simultaneamente pelo menos 500 usuários ativos sem degradação perceptível de desempenho. |  
| **RNF-002**  | Usabilidade                     | A interface deve ser intuitiva e responsiva, garantindo acessibilidade em diferentes dispositivos e tamanhos de tela. |  

---  


# Prototipagem
Os protótipos de telas foram desenvolvidos no Figma, representando o fluxo de navegação, a apresentação de cursos e as funcionalidades de gerenciamento de conteúdo.  

Tela Inicial
![Tela Inicial Protótipo Figma](https://github.com/YurizinDEV/FormulaX/blob/main/img/Frame%2014.png)

[ [INÍCIO](#projeto-de-software) ]


# Diagrama de Casos de Uso

![Diagrama de Casos de Uso](https://github.com/YurizinDEV/FormulaX/blob/752af0460d4a95fc92624afef62fc172d57d6cd4/img/DiagramUseCase%20F%C3%B3rmulaX.png)

## Descrição / Especificação dos Casos de Uso

### UC-01 - Acessar Conteúdos  

| **UC-01 - Acessar Conteúdos**       |  
|:------------------------------------|  
| **Descrição/Objetivo:** Permitir que o aluno visualize e estude os conteúdos dos cursos disponíveis na plataforma. |  
| **Atores:** Aluno (Usuário Padrão)  |  
| **Pré-condições:** O aluno deve estar autenticado na plataforma e inscrito em pelo menos um curso. |  
| **Pós-condições:** O sistema deve registrar o progresso do aluno no curso. |  
| **Fluxo Principal / Básico:**       |  
| 1. O aluno acessa o sistema e efetua login. |  
| 2. O aluno seleciona o curso desejado. |  
| 3. O sistema exibe os módulos e conteúdos do curso. |  
| 4. O aluno pode abrir qualquer unidade, assistir vídeos e ler materiais. |  
| 5. O sistema registra o progresso de leitura ou visualização. |  
| **Fluxos Alternativos / Exceções:** |  
| **A1: Erro de conexão ou servidor indisponível** |  
| 1. O aluno recebe uma mensagem de erro e aguarda a restauração do serviço. |  

[ [INÍCIO](#projeto-de-software) ]  

---  


# Diagrama de Classes

![Diagrama de Classes](https://github.com/YurizinDEV/FormulaX/blob/752af0460d4a95fc92624afef62fc172d57d6cd4/img/DiagramClass%20F%C3%B3rmulaX.png)

---  


# Diagrama de Sequências

*(Apresentar o diagrama de sequência ilustrando a interação entre o aluno e o sistema para acessar conteúdos, por exemplo.)*  

--- 

# Diagrama de Atividades
*(Expor o diagrama de atividades descrevendo o processo de inscrição em cursos ou outro fluxo relevante.)*  

---  


# REFERÊNCIAS

Esta subseção apresenta as referências aos documentos que utilizamos no auxílio à construção deste documento.
* [UML](https://www.omg.org/spec/UML/2.5/About-UML/)
* [Práticas para Especificação de Requisitos IEEE-830](https://ieeexplore.ieee.org/document/720574)
---  

[ [INÍCIO](#projeto-de-software) ]  
