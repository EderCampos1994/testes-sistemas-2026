# Plano de Ensino

## Unidade Curricular: Teste de Sistemas
### Curso Técnico em Desenvolvimento de Sistemas


---
link para página: [Acessar o site da disciplina](https://edercampos1994.github.io/testes-sistemas-2026/)



---

## 1. Identificação

| Campo | Descrição |
|---|---|
| **Unidade Curricular (UC)** | Teste de Sistemas |
| **Curso** | Técnico em Desenvolvimento de Sistemas |
| **Carga horária total** | 40 horas |
| **Número de aulas** | 26 aulas |
| **Duração de cada aula** | 1h30 |
| **Ferramentas/Tecnologias** | IntelliJ IDEA, Java, Maven, JUnit 5, Mockito, Spring Boot |
| **Pré-requisitos** | Lógica de Programação, Programação Orientada a Objetos (POO) |

---

## 2. Ementa

Fundamentos de teste de software; tipos e níveis de teste; ambiente de desenvolvimento e ferramentas de teste (IntelliJ IDEA, Maven, JUnit 5); revisão de POO aplicada a testes; escrita de testes unitários; asserções e ciclo de vida de testes; testes parametrizados e testes de exceção; test doubles (mocks, stubs, fakes) com Mockito; cobertura de código; desenvolvimento orientado a testes (TDD); testes em aplicações Spring/Spring Boot (camadas de serviço, repositório e controller); boas práticas de teste; projeto integrador prático.

---

## 3. Objetivos Gerais

Capacitar o(a) estudante a compreender a importância dos testes de software no ciclo de desenvolvimento, aplicando conceitos de Programação Orientada a Objetos na construção de testes unitários e de integração com JUnit 5, utilizando a IDE IntelliJ, e a testar aplicações construídas com o framework Spring.

## 4. Objetivos Específicos

Ao final da UC, o(a) estudante será capaz de:

- Compreender os fundamentos, tipos e níveis de teste de software;
- Configurar um projeto Maven no IntelliJ IDEA, entendendo o papel do arquivo `pom.xml` e das dependências de teste;
- Revisar e aplicar corretamente conceitos de POO (classes, atributos, métodos, encapsulamento, construtores) na criação de classes de entidade;
- Criar e organizar testes unitários com JUnit 5, utilizando anotações e asserções corretamente;
- Escrever testes parametrizados e testes de exceção;
- Utilizar test doubles (mocks/stubs) com o Mockito;
- Interpretar relatórios de cobertura de código;
- Aplicar o ciclo de TDD (Red-Green-Refactor) em pequenos problemas;
- Testar camadas de uma aplicação Spring Boot (Service, Repository e Controller);
- Desenvolver, de forma autônoma, um pequeno projeto aplicando os testes aprendidos.

---

## 5. Metodologia

- Aulas expositivo-dialogadas com apoio de slides e exemplos ao vivo;
- Demonstrações práticas com código comentado, sempre seguidas de prática guiada;
- Criação conjunta de **classes de entidade** (POO) e das respectivas **classes de teste**, reforçando a relação entre modelagem de objetos e verificação de comportamento;
- Exercícios individuais/em dupla com apresentação de gabarito comentado;
- Retomada constante de conceitos de POO ao longo das aulas, sempre que um novo conceito de teste depender deles;
- Projeto integrador nas aulas finais, consolidando os conteúdos da UC.

## 6. Recursos Didáticos

- Computador com JDK instalado, IntelliJ IDEA (Community Edition), acesso à internet;
- Repositório de exemplos de código comentado (classes de entidade + classes de teste);
- Arquivo `pom.xml` de referência com as dependências do JUnit 5 (e, nas aulas finais, do Spring Boot Test), sempre acompanhado de explicação linha a linha;
- Slides de apoio e roteiros de prática por aula;
- Banco de dados em memória H2 (para as aulas de teste de repositório com Spring).

## 7. Avaliação

| Instrumento | Peso | Descrição |
|---|---|---|
| Exercícios práticos por aula | 40% | Atividades de fixação entregues ao final de cada aula |
| Avaliação intermediária (Aula 8) | 20% | Testes unitários e uso de Mockito |
| Projeto integrador (Aulas 13–15) | 40% | Aplicação Spring com suíte de testes completa (unitários + integração) |

Critério de aprovação: nota final ≥ 6,0 (escala 0–10) e frequência mínima de 75%.

---

## 8. Conteúdo Programático (Aula a Aula)

| Aula | Carga h. | Tema | Conteúdo | Observações |
|---|---|---|---|---|
| 1 | 1h30 | Fundamentos de Teste de Software | O que é testar software, por que testar, qualidade, erros, defeitos e falhas | Diagnóstico da turma |
| 2 | 1h30 | Tipos e Níveis de Teste | Testes unitários, integração, sistema e aceitação; pirâmide de testes | Aplicação ao projeto do grupo |
| 3 | 1h30 | Qualidade e Critérios de Aceitação | Requisitos funcionais e não funcionais, critérios de aceitação e riscos | Identificação de requisitos testáveis |
| 4 | 1h30 | Planejamento de Testes | Objetivos, escopo, estratégia, recursos, responsabilidades e prioridades | Início do plano de testes |
| 5 | 1h30 | Análise Documental | Leitura de requisitos, histórias de usuário, regras de negócio e identificação de inconsistências | Registro de dúvidas e riscos |
| 6 | 1h30 | Casos de Teste | Estrutura de um caso de teste, pré-condições, passos, dados e resultado esperado | Primeiros casos do projeto |
| 7 | 1h30 | Técnicas de Elaboração de Testes | Partição de equivalência, análise de valor-limite e tabela de decisão | Ampliação dos casos de teste |
| 8 | 1h30 | Ambiente e Preparação | Configuração do IntelliJ IDEA, Java, Maven, estrutura do projeto e dependências no `pom.xml` | Ambiente preparado |
| 9 | 1h30 | Execução e Registro de Testes | Execução dos casos, evidências, resultados e rastreabilidade | Primeira execução documentada |
| 10 | 1h30 | Fundamentos de Teste de Performance | Desempenho, tempo de resposta, vazão, concorrência e disponibilidade | Definição do objetivo de performance |
| 11 | 1h30 | Tipos de Teste de Performance | Testes de carga, estresse, volume, resistência e escalabilidade | Escolha do tipo adequado |
| 12 | 1h30 | Planejamento de Cenários de Performance | Usuários, operações, dados, duração, critérios de sucesso e ambiente | Cenário de performance do projeto |
| 13 | 1h30 | Ferramentas e Avaliação Intermediária | Apresentação de ferramentas, preparação de execução e avaliação prática dos testes unitários | **Avaliação intermediária** |
| 14 | 1h30 | Execução de Testes de Performance | Preparação dos dados, execução controlada e coleta de resultados | Evidências da execução |
| 15 | 1h30 | Métricas e Análise de Resultados | Tempo de resposta, throughput, erros, percentis e interpretação de gráficos | Análise dos resultados |
| 16 | 1h30 | Identificação de Gargalos | CPU, memória, banco de dados, rede, consultas e pontos de estrangulamento | Hipóteses de causa |
| 17 | 1h30 | Relatório de Performance | Organização dos resultados, conclusão, limitações e recomendações | Entrega do relatório |
| 18 | 1h30 | Testes Funcionais | Validação das funcionalidades do próprio sistema do grupo | Seleção das funcionalidades |
| 19 | 1h30 | Execução de Testes Funcionais | Execução dos casos, comparação entre resultado esperado e obtido | Evidências funcionais |
| 20 | 1h30 | Classificação e Documentação de Falhas | Severidade, prioridade, descrição, passos para reprodução e evidências | Registro de defeitos |
| 21 | 1h30 | Reteste e Regressão | Diferenças entre reteste e regressão; validação de correções | Execução após correções |
| 22 | 1h30 | Técnicas Complementares e Boas Práticas | Testes exploratórios, negativos, fronteiras, organização e manutenção da suíte | Revisão dos casos |
| 23 | 1h30 | Introdução à Automação | Benefícios, limites, critérios de automação e estrutura de testes automatizados | Seleção dos cenários |
| 24 | 1h30 | Primeiro Teste Automatizado | JUnit 5, `@Test`, ciclo de vida, padrão AAA e asserções | Implementação no projeto |
| 25 | 1h30 | Testes Parametrizados e Negativos | `@ParameterizedTest`, `@ValueSource`, `@CsvSource`, `assertThrows` e validações | Ampliação da suíte automatizada |
| 26 | 1h30 | Consolidação, Plano de Ação e Apresentação | Organização do plano, resultados, falhas, retestes, melhorias e apresentação final | **Entrega e apresentação do projeto integrador** |

---

## 9. Bibliografia

**Básica**
- JUNIT 5 User Guide. Disponível em: https://junit.org/junit5/docs/current/user-guide/
- SPRING Framework Documentation. Disponível em: https://docs.spring.io/spring-framework/reference/
- PRESSMAN, Roger S.; MAXIM, Bruce R. *Engenharia de Software: uma abordagem profissional*. 8. ed. Porto Alegre: AMGH, 2016.

**Complementar**
- BECK, Kent. *Test Driven Development: By Example*. Addison-Wesley, 2002.
- FOWLER, Martin. *Refactoring: Improving the Design of Existing Code*. 2. ed. Addison-Wesley, 2018.
- Documentação oficial do Mockito. Disponível em: https://site.mockito.org/

---
