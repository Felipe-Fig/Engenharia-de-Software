# Engenharia de Software
## UNOPAR

1) Tomando como referência as especificidades da realização de um teste de unidade, julgue as afirmativas a seguir em (V) Verdadeiras ou (F) Falsas.

(  ) Pela localização da sua aplicação, este teste é conhecido como intra-método.

(  ) Este procedimento deve se concentrar em testar as funcionalidades do método.

(  ) Este teste consiste em chamadas para as rotinas da unidade com diferentes parâmetros.

Assinale a alternativa que apresenta a sequência CORRETA.

Alternativas:

    a) F - V - F.
    b) F - V - V.
    c) V - V - F.
    d) V - F - V.
    e) V - V - V.

**Gabarito: e) V - V - V.**

>O **teste de unidade** é um teste funcional quando aplicado para verificar funções de um módulo, função ou classe do sistema. O teste de unidade é aquele realizado sobre cada classe do sistema e que os testes de aceitação são efetuados sobre cada estória (ou funcionalidade) do sistema.

>Um teste de unidade é uma forma de verificar o funcioinamento correto das menores unidades de programas de computador. É mais um procedimento daqueles que são realizados dentro de uma metodologia de trabalho rápido.<br>
Os testes unitários consistem em isolar um pedaço de código e verificar se ele funciona perfeitamente. São pequenos testes que validam o comportamento de um objeto e a lógica.<br>
O teste de unidade é geralmente feito durante a fase de desenvolvimento de software ou aplicativos móveis.

>Teste de unidade: os autores consideram que as menores unidades a serem testadas em um programa OO são os métodos. Por isso, indicam que o teste de unidade consiste no teste de cada método de forma isolada, o que também é chamado de teste intra-método.

---

2) Considerando os conceitos e as aplicações de testes de sistema, avalie as afirmativas as seguir:

I. Os testes de sistema devem se concentrar em testar as interações entre os componentes e os objetos que compõem um sistema.

II. Uma das justificativas para a aplicação de um teste de sistema é que alguns componentes se tornam evidentes apenas quando os componentes são unidos.

III. Um teste de sistema é executado pela checagem de métodos aos pares, ou seja, a interação entre dois métodos escolhidos ao acaso.

Considerando o contexto apresentado, assinale a alternativa correta.

Alternativas:

    a) Apenas as afirmativas I e III são corretas.
    b) Apenas as afirmativas I e II são corretas.
    c) Apenas a afirmativa I é correta.
    d) Apenas a afirmativa II é correta.
    e) As afirmativas I, II e III são corretas.

**Gabarito: b) Apenas as afirmativas I e II são corretas.**

>Teste de sistema: consiste em testar a integração entre todos os módulos, o que equivale a um sistema completo. Para esta fase geralmente é usado o teste funcional.

---

3) Considerando as características de operacionalização do TDD (Test Driven Development), complete as lacunas da sentença a seguir.

Durante o TDD (Test Driven Development), o código é desenvolvido em incrementos __________ e nenhum código é escrito enquanto não houver um ________ para experimentá-lo. Cada iteração resulta em um ou mais novos testes, os quais são acrescentados a um conjunto de testes de ___________ que é executado a cada mudança. Isso é feito para garantir que o novo código não tenha gerado efeitos colaterais que causem erros no código anterior.

Assinale a alternativa que completa as lacunas corretamente.

Alternativas:

    a) grandes - desenvolvedor - regressão.
    b) pequenos - teste - regressão.
    c) médios - teste - refatoração.
    d) grandes - cliente - regressão.
    e) pequenos - teste - refatoração.

**Gabarito: b) pequenos - teste - regressão.**

>O teste de regressão é um subtipo do teste funcional, que visa garantir que uma alteração feita em uma função não tenha introduzido outros problemas no código.<br>
>A ideia central do TDD é a de fazer com que o desenvolvedor escreva testes automatizados de maneira constante ao longo do processo de desenvolvimento e antes mesmo da implementação do código.

---

4) Considerando características de testes automatizados e da ferramenta de teste JUnit, avalie as afirmativas a seguir:

I. O JUnit é uma ferramenta que realiza testes unitários, com recursos para a aplicação de Desenvolvimento Orientado a Testes.

II. Apesar de ser conhecida como uma ferramenta de automação de teste, o JUnit não é capaz de validar a saída do teste.

III. Os testes de unidade são automatizados em um formato em que de classes são criadas para testar outras classes.

Considerando o contexto apresentado, assinale a alternativa correta.

Alternativas:

    a) Apenas as afirmativas II e III são corretas.
    b) Apenas as afirmativas I e III são corretas.
    c) Apenas a afirmativa III é correta.
    d) As afirmativas I, II e III são corretas.
    e) Apenas a afirmativa I é correta.

**Gabarito: b) Apenas as afirmativas I e III são corretas.**

>JUnit é o framework de testes de unidade do Java, que funciona em conjunto com o IDE Eclipse. A adaptação do código ao JUnit é simples e atinge a parte da validação, na qual os métodos do framework serão invocados para que comparem o resultado esperado com o obtido, portanto ele é capaz de validar a saída do teste.
---

5) No desenvolvimento guiado por teste (TDD), requisitos para um componente de software servem de base para a criação de uma série de casos de teste que exercitam a interface e tentam encontrar erros nas estruturas de dados e na funcionalidade fornecida pelo componente.

Fonte: PRESSMAN, Roger; MAXIM, Bruce, Engenharia de Software: uma abordagem profissional. 8. ed. Porto Alegre: AMGH, 2016.
 
Com base no tipo de teste viável para a aplicação do TDD (Test Driven Development), avalie as seguintes asserções e a relação proposta entre elas.

I. Embora seja a forma mais usual, a efetivação da prática do TDD não está relacionada, necessariamente, apenas aos testes de unidade

PORQUE

II. É possível que o TDD seja aplicado também em procedimentos que testem o sistema segundo o ponto de vista do usuário, numa averiguação direta do seu atendimento aos requisitos do cliente.

A respeito dessas asserções, assinale a alternativa correta.

Alternativas:

    a) As asserções I e II são proposições verdadeiras e a II é uma justificativa da I.
    b) As asserções I e II são proposições verdadeiras, mas a II não é uma justificativa da I.
    c) A asserção I é uma proposição verdadeira, e a II é uma proposição falsa.
    d) A asserção I é uma proposição falsa, e a II é uma proposição verdadeira.
    e) As asserções I e II são proposições falsas.

**Gabarito: a) As asserções I e II são proposições verdadeiras e a II é uma justificativa da I.**

>O TDD contém duas partes: implementação rápida e refatoração e, na prática, o teste para implementação rápida não se limita ao teste de unidade. Pode ser um teste de aceitação também. A asertiva II também é correta pois ao realizar o teste de aceitação é necessário o atendimento à necessidade do cliente.

---