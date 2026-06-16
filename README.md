# Projetos Acadêmicos — 1º Semestre de 2026

Este repositório reúne os principais trabalhos desenvolvidos durante o 1º semestre de 2026 no curso de **Análise e Desenvolvimento de Sistemas — Fatec Lins**.

Os projetos abordam conteúdos de **algoritmos, engenharia de software, levantamento de requisitos, modelagem UML, backlog, análise de sistemas, front-end, back-end e desenvolvimento web**.

## Sobre o repositório

Durante o semestre, os trabalhos tiveram como foco principal o desenvolvimento e a documentação de um **Sistema Web para Gestão de Pesquisas por Questionários**, além de atividades complementares relacionadas à programação, análise de sistemas e tecnologias web.

O sistema proposto tem como objetivo permitir que instituições criem, apliquem e analisem pesquisas de forma organizada, segura e anônima. Um dos principais diferenciais do projeto é o uso de **senhas aleatórias e de uso único**, que permitem ao respondente acessar o questionário sem ter sua identidade diretamente associada às respostas.

## Projetos desenvolvidos

## 1. Sistema Web para Gestão de Pesquisas por Questionários

Este foi o projeto principal do semestre. A proposta consiste em uma aplicação web voltada para a criação, aplicação e análise de pesquisas institucionais.

O sistema foi pensado para atender instituições que precisam aplicar questionários para diferentes grupos, como alunos, professores, funcionários e colaboradores, mantendo o controle da participação e preservando o anonimato dos respondentes.

### Principais funcionalidades

* Cadastro e gerenciamento de pesquisas;
* Cadastro de categorias de participantes;
* Criação de questionários;
* Cadastro de perguntas;
* Definição de tipos de questão, como múltipla escolha, escala de avaliação e resposta aberta;
* Geração de senhas anônimas;
* Exportação de senhas em PDF ou CSV;
* Acesso do respondente por senha válida;
* Validação da senha de acesso;
* Registro anônimo das respostas;
* Bloqueio de reutilização de senha;
* Monitoramento da participação;
* Geração de relatórios estatísticos;
* Exportação de resultados em PDF ou CSV.

### Atores do sistema

* **Administrador:** responsável pelo controle geral da plataforma, usuários, pesquisas, questionários, senhas, relatórios e permissões.
* **Coordenador/Pesquisador:** responsável por criar e acompanhar pesquisas específicas.
* **Respondente:** usuário que acessa a pesquisa de forma anônima por meio de uma senha válida.
* **Responsável pela Distribuição das Senhas:** usuário responsável por exportar, imprimir ou distribuir os lotes de senhas gerados.

## 2. Documento de Visão e Escopo

Também foi desenvolvido um documento de visão e escopo para organizar a proposta do sistema.

Esse documento apresenta:

* O problema que o sistema busca resolver;
* Os objetivos gerais e específicos;
* A visão geral do projeto;
* O escopo inicial;
* As funcionalidades previstas;
* Os requisitos funcionais;
* Os requisitos não funcionais;
* Os requisitos de segurança;
* A arquitetura prevista;
* Uma análise comparativa com outras ferramentas de formulários.

O documento serviu como base para entender melhor o sistema antes da implementação, deixando claro o que faria parte do projeto e quais funcionalidades ficariam fora do escopo inicial.

## 3. Lista de Requisitos e Backlog Inicial

Foi criada uma lista de requisitos organizada em formato de backlog, utilizando histórias de usuário, prioridades e critérios de aceitação.

O backlog foi dividido em épicos:

* **Épico 1:** Gestão de acesso e perfis;
* **Épico 2:** Gestão de pesquisas e categorias;
* **Épico 3:** Questionários e perguntas;
* **Épico 4:** Geração e distribuição de senhas;
* **Épico 5:** Coleta de respostas;
* **Épico 6:** Monitoramento e relatórios.

Esse trabalho ajudou a transformar os requisitos do sistema em tarefas mais organizadas, facilitando o planejamento do desenvolvimento.

## 4. Modelagem UML e Fluxos

Também foram elaborados diagramas UML e fluxos do sistema, principalmente diagramas de caso de uso.

A modelagem foi utilizada para representar visualmente como os atores interagem com as funcionalidades do sistema.

Entre os casos de uso trabalhados estão:

* Cadastrar pesquisa;
* Gerenciar categorias;
* Criar questionário;
* Cadastrar perguntas;
* Definir tipo de questão;
* Gerar senhas anônimas;
* Exportar senhas;
* Acessar pesquisa com senha;
* Validar senha de acesso.

Além dos diagramas, também foram desenvolvidos fluxos principais e alternativos, descrevendo o comportamento esperado do sistema em situações normais e em casos de erro.

## 5. Módulo de Geração de Senhas em VisualG

Outro projeto importante foi o desenvolvimento de um algoritmo em **VisualG** para gerar senhas aleatórias por categoria de usuário.

O algoritmo solicita a categoria do usuário, aceitando apenas:

* **P** para Professor;
* **A** para Aluno;
* **F** para Funcionário.

Depois disso, o programa gera senhas com exatamente **8 caracteres**, sendo o primeiro caractere a letra da categoria e os outros sete caracteres sorteados a partir de letras maiúsculas, números e símbolos especiais.

### Conceitos utilizados

* Entrada de dados;
* Validação de categoria;
* Estruturas condicionais;
* Laços de repetição;
* Vetores;
* Manipulação de strings;
* Geração aleatória de caracteres;
* Fluxograma;
* Testes e validação.

Esse módulo serviu como base lógica para a futura implementação da geração de senhas dentro do sistema web.

## 6. Análise Comparativa de Sistemas de Questionários

Foi desenvolvido um relatório técnico comparando o sistema proposto com plataformas já existentes de questionários, como:

* Google Forms;
* SurveyMonkey;
* LimeSurvey;
* Microsoft Forms.

A análise considerou critérios como:

* Criação de questionários;
* Tipos de perguntas;
* Segurança;
* Controle de respostas;
* Relatórios;
* Exportação de dados;
* Anonimato;
* Uso de senhas ou tokens.

A conclusão foi que o sistema proposto se diferencia por ter como foco principal o uso de **senhas anônimas, únicas e descartáveis**, algo que não é o objetivo central das ferramentas mais genéricas de formulários.

## 7. Atividade sobre Front-end e Back-end

Também foi realizada uma atividade de pesquisa sobre os conceitos de front-end e back-end.

### Front-end

O front-end representa a parte visual de um sistema, ou seja, aquilo que o usuário vê e utiliza diretamente.

Foram estudadas tecnologias como:

* HTML;
* CSS;
* JavaScript;
* React;
* Vue.js;
* Angular.

### Back-end

O back-end representa a parte interna do sistema, responsável por regras de negócio, banco de dados, login, segurança e processamento das informações.

Foram estudadas linguagens e tecnologias como:

* PHP;
* JavaScript com Node.js;
* Python;
* Java;
* C#;
* Ruby;
* Go.

Essa atividade ajudou a entender melhor como uma aplicação web é dividida entre interface, regras de negócio e armazenamento de dados.

## Tecnologias e conceitos estudados

Ao longo dos projetos, foram utilizados ou estudados os seguintes conceitos:

* VisualG;
* Algoritmos;
* Vetores;
* Estruturas de repetição;
* Condicionais;
* Manipulação de strings;
* Fluxogramas;
* Requisitos funcionais;
* Requisitos não funcionais;
* Requisitos de segurança;
* Backlog;
* Histórias de usuário;
* Critérios de aceitação;
* Diagramas UML;
* Casos de uso;
* Sistemas web;
* Banco de dados relacional;
* Segurança em aplicações web;
* HTML, CSS e JavaScript;
* Front-end e back-end.

## Estrutura sugerida do repositório

```text
/
├── README.md
├── docs/
│   ├── documento-visao-escopo.md
│   ├── backlog-requisitos.md
│   ├── engenharia-software.md
│   └── analise-comparativa.md
├── algoritmos/
│   └── gerador-senhas-visualg.alg
├── diagramas/
│   └── casos-de-uso/
└── atividades/
    └── front-end-back-end.md
```

## Objetivo acadêmico

O objetivo deste repositório é registrar os trabalhos desenvolvidos durante o semestre, demonstrando a evolução dos estudos em análise e desenvolvimento de sistemas.

Os projetos mostram desde a lógica inicial de programação até a documentação e planejamento de um sistema web mais completo, passando por requisitos, segurança, modelagem, análise comparativa e organização de backlog.

## Autor

**Richard de Oliveira Barra Junior**
Curso: Análise e Desenvolvimento de Sistemas
Instituição: Fatec Lins
Período: 1º semestre de 2026

## Status

Projetos desenvolvidos para fins acadêmicos durante o 1º semestre de 2026.
