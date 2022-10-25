# Engenharia de Software

1) Uma equipe de testadores foi designada para aplicar testes em um produto de software recém implementado. Depois de estabelecer um planejamento que entenderam adequado para o caso, a equipe o executou e, assim que o procedimento foi concluído, fizeram a entrega do produto ao cliente. Poucos dias depois, o cliente fez contato com a equipe relatando uma série de erros observados durante a execução do produto que acabara de adquirir. Você, então, foi destacado para descobrir os motivos (ou o motivo) da manifestação destes erros.

Considerando o contexto apresentado, assinale a alternativa que contém a providência adequada para saneamento do problema.

Alternativas:

    a) Proposição da revalidação dos requisitos levantados.
    b) Troca da linguagem de programação utilizada na implementação.
    c) Troca do ambiente integrado de desenvolvimento utilizado na implementação.
    d) Checagem dos casos de teste utilizados no procedimento.
    e) Proposição de mudança na metodologia de desenvolvimento.

**Gabarito: d) Checagem dos casos de teste utilizados no procedimento.**

>Um caso de teste é o par formado por uma entrada possível a ser dada no programa e a correspondente saída esperada, também dada pelo programa e de acordo com os requisitos previamente especificados. Nesse caso, devemos entender o conceito de entrada como o conjunto de dados necessários para uma execução do programa e o de saída esperada como o resultado daquela execução ou de função específica.<br><br> A boa escolha dos casos de teste é fator crítico para o sucesso da atividade. Um conjunto de casos de teste de baixa qualidade pode não exercitar partes críticas do programa e, em consequência disso, acabar não revelando defeitos no código.

---

2) Considerando recursos usados para descobrir erros em um programa, complete as lacunas da sentença que segue:

O fato de saber que parte do código não funciona não significa que necessariamente seja conhecido o trecho do código que provoca um ou mais erros.  Assim, enquanto a atividade de ___________ consiste em executar sistematicamente o software para encontrar erros __________, a _______________ é a atividade que consiste em buscar a causa do erro e sua localização no código.

Assinale a alternativa que completa as lacunas corretamente

Alternativas:

    a) verificação - desconhecidos - validação.
    b) validação - desconhecidos - verificação.
    c) teste - recorrentes - depuração
    d) teste - desconhecidos - depuração.
    e) teste - recorrentes - compilação.

**Gabarito: d) teste - desconhecidos - depuração.**

>Um teste não é um procedimento isolado que pode ser concluído por um único membro da equipe. Embora seja comum tratá-lo por “teste”, sua execução depende de um conjunto de ações e procedimentos executados por vários elementos da equipe de desenvolvimento. Por isso, melhor seria chamá-lo de processo de teste, já que formalmente ele representa uma sequência de ações executadas com o objetivo de encontrar problemas no software, o que aumenta a percepção da qualidade geral dele e garante que o usuário final tenha um produto que atenda às suas necessidades (PINHEIRO, 2015).<br><br> IEEE (2014) nos oferece o seguinte conceito: o teste de software consiste na verificação dinâmica de que um programa, de fato, fornece comportamentos esperados em um conjunto finito de casos de teste adequadamente selecionados do domínio de execução geralmente infinito.<br><br> Enquanto testar significa executar o software para encontrar defeitos desconhecidos, a depuração (ou debug) é a atividade que consiste em buscar a localização desses defeitos no código. A depuração ocorre como consequência de um teste bem-sucedido, ou seja, quando um caso de teste descobre um defeito. Nesse caso, a depuração é o processo que encontra e remove o erro. Embora não seja um teste, ela ocorre como um desdobramento dele e começa com a execução de um caso de teste.

---

3) Considerando conceitos e aplicações da depuração (debug), avalie as afirmativas que seguem:

I. A necessidade da depuração decorre de um teste mal-sucedido.

II. Um dos recursos da depuração inclui a inspeção de variáveis.

III. A depuração equivale à aplicação de um teste menos complexo.

Considerando o contexto apresentado, assinale a alternativa correta.

Alternativas:

    a) Apenas a afirmativa II é correta.
    b) Apenas as afirmativas I e II são corretas.
    c) Apenas as afirmativas II e III são corretas.
    d) As afirmativas I, II e III são corretas.
    e) Apenas a afirmativa I é correta.

**Gabarito: a) Apenas a afirmativa II é correta.**

>I está errada pois a depuração decorre de um teste bem sucedido.<br><br>
III - a depuração não é um teste e sim um desdobramento do mesmo.

---

4) Considerando o conceito e as aplicações do teste estrutural, avalie as afirmativas a seguir:

I.  O teste estrutural dispensa a utilização de ferramenta de teste, já que o desenvolvedor deve estar de posse do código-fonte da ferramenta.

II. O teste estrutural é também chamado caixa branca por sua estrutura e seu código serem previamente conhecidos pelo testados.

III. Em um teste estrutural, o caso de teste mais adequado é aquele capaz de percorrer, em uma única execução, todos os caminhos do código.

Considerando o contexto apresentado, assinale a alternativa correta.

Alternativas:

    a) Apenas a afirmativa II é correta.
    b) Apenas as afirmativas II e III são corretas.
    c) Apenas as afirmativas I e II são corretas.
    d) As afirmativas I, II e III são corretas.
    e) Apenas a afirmativa I é correta.

**Gabarito: a) Apenas a afirmativa II é correta.**

>I - está errada pois o testador não dispensa a ferramenta automatizada de testes. Apesar disso ele precisa ter o código-fonte.<br><br>
II - CORRETA - Os testes estruturais (também chamados de caixa branca) são assim conhecidos por serem baseados na arquitetura interna do programa. Contando com o código-fonte e com a estrutura do banco de dados, o testador poderá submeter o programa a uma ferramenta automatizada de teste. Vale aqui a menção de que um teste funcional também pode (e deve) ser realizado de forma automática.<br><br>
III - Por mais que seja interessante cobrir mais caminhos ao longo do teste (e evitar outros possíveis erros) pode ser que os casos de teste sejam infinitos e portanto seria impraticável realizar esse teste. Com isso não é necessário percorrer todos os caminhos mas sim deve atender à alguns critérios de cobertura do código que foram previamente definidos.

---