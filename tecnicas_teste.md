# Técnicas de Testes de Software

 Adotar técnicas de teste de software é fundamental para o desenvolvimento de um projeto. Os testes precisam ser aplicados constantemente ao longo do processo para evitar que um produto chegue com problemas e falhas às mãos do consumidor ou cliente.
 
 Além disso, utilizar técnicas de teste de software faz com que o projeto seja ajustado e passe por manutenções em etapas em que isto ainda não é um problema, ou seja, antes de chegar ao mercado. 

 Se os erros aparecem quando o software já estiver sendo comercializado, é possível que uma parte do trabalho tenha que ser refeita. E isto pode levar a atrasos na implantação do novo sistema para o cliente e trazer prejuízos se houver suspensão de procedimentos. 
 
## Importância dos testes no desenvolvimento

 Para isto, existem diversas ferramentas de teste que podem ser utilizadas no processo. Assim, a equipe de desenvolvimento pode se dedicar a outras tarefas relacionadas ao programa, sem a necessidade de realizar testes demorados e repetitivos manualmente. 

 Isso porque é necessário testar, fazer os ajustes, testar novamente, reajustar e assim sucessivamente até que o sistema não apresente mais erros.

Aqui está uma visão geral dos três principais tipos: teste unitário, teste de integração e teste de aceitação.
### 1. Teste Unitário
 Definição: O teste unitário se concentra na verificação de partes individuais do código, como funções ou métodos, para garantir que funcionem conforme o esperado.

 Objetivo: Identificar erros em componentes isolados antes de integrá-los ao sistema maior.

 Ferramentas Comuns: JUnit (Java), NUnit (.NET), PyTest (Python).

 Práticas: Geralmente automatizados e escritos pelos desenvolvedores. Um bom teste unitário deve ser rápido e focado em uma única unidade de código.
### 2. Teste de Integração
 Definição: O teste de integração verifica a interação entre diferentes módulos ou serviços de um sistema para garantir que funcionem corretamente juntos.

 Objetivo: Detectar problemas que podem surgir quando os componentes interagem, como falhas de comunicação ou dados inconsistentes.

Tipos:

 -Integração de Módulos: Testa a integração entre diferentes partes do código.
 
 -Integração de Sistema: Verifica a integração de sistemas externos ou serviços.

 Ferramentas Comuns: Postman (para APIs), TestNG (Java), JUnit (para testes de integração em Java).

Práticas: Pode ser realizado em diferentes níveis, desde integração simples até testes mais complexos de sistemas completos.
### 3. Teste de Aceitação
 Definição: O teste de aceitação é realizado para validar se o software atende aos requisitos e expectativas dos usuários finais e partes interessadas.
 
 Objetivo: Garantir que o produto final está pronto para uso e atende aos critérios de aceitação definidos.

Tipos:

 -Teste de Aceitação do Usuário (UAT): Conduzido pelos usuários finais em um ambiente que simula o ambiente de produção.

 -Teste de Aceitação Funcional: Avalia se as funcionalidades estão de acordo com os requisitos especificados.

 Ferramentas Comuns: Cucumber, FitNesse.

 Práticas: Envolve usuários reais e é focado em cenários do mundo real, garantindo que o software é utilizável e atende a expectativas.