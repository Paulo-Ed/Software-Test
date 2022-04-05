# Teste de Software
Conceitos e aplicação de testes no desenvolvimento de software.

## INTRODUÇÃO

### Definição
* Teste de software é o processo ou o conjunto de processos que tem por objetivo examinar o software em busca de informações sobre
a sua qualidade em relação ao contexto no qual ele deve ser executado. O teste de software tem como objetivo encontrar defeitos ou falhas no software e assim corrigi-los,
evitando que tais falhas cheguem ao usuário final e possam gerar prejuízos.

### Histórico
* No modelo de desenvolvimento em cascata ou sequêncial, a realização de testes se dava em uma fase separada, posterior as fases de levantamento, análise, projeto e implementação do sistema. O comum era que existisse uma equipe específica responsável por verificar se a implementação estava de acordo com as especificações dos requisitos.
* O teste mais comuns realizados eram os chamados testes manuais, que consistiam do uso do sistema, com entrada de dados por um testador, que após isso verificava se o resultado da saída era o esperado. O objetivo desses teste era apenas o de encontrar possíveis bugs, antes que o software entrasse em produção.

### Atualmente
* Com o avanço dos métodos ágeis de desenvolvimento, a implementação de testes de software foi totalmente reformulada. A maior parte dos testes passou de manual para testes automatizados, ou seja, implementação de código responsável por testar o funcionamento das entidades do sistema, tornando assim o código auto-testável.
* A realização dos testes passou a ser incremental, em que de acordo com a elaboração dos componentes, os mesmos são testados. 
* A implementação de testes passou de equipes específicas, para o próprio desenvolvedor, que fica responsável por elaborar e executar unidades de código de teste a fim de verificar o código que ele implementou.
* Além de detectar bugs, testes passaram a ter a função de verificar a integridade dos componentes, classes e ou entidades do sistema após a correção de um ou mais erros em outras partes do sistema. Testes também passaram a ser utilizados como documentação para o código de produção.