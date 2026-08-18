# Questões 4, 5, 10 e 11

## 4 - Fortran: desempenho, custo e adoção

O projeto Fortran precisou convencer os programadores de que a abstração proporcionada por uma linguagem de alto nível não significaria necessariamente perda significativa de desempenho.

A estratégia foi demonstrar que o compilador poderia gerar código próximo da qualidade do código escrito à mão, enquanto a linguagem reduzia muito o esforço, o tempo e o custo de desenvolvimento.

---

## 5 - Fortran e Lisp

### Domínios diferentes

O **Fortran** foi desenvolvido para atender principalmente cientistas e engenheiros que precisavam realizar cálculos numéricos. Por isso, a linguagem foi projetada para expressar fórmulas matemáticas de maneira relativamente direta e produzir código eficiente.

O **Lisp**, por outro lado, surgiu a partir das pesquisas de **John McCarthy** em inteligência artificial. Seu objetivo estava relacionado ao processamento de informações simbólicas, uma necessidade diferente daquela encontrada na computação científica. Em vez de trabalhar principalmente com números, Lisp precisava manipular conceitos, expressões e estruturas simbólicas.

### Representação de dados

No **Fortran**, números são fundamentais. A linguagem oferece tipos e operações apropriados para cálculos científicos, além de estruturas como **arrays**, importantes para representar vetores e matrizes.

No **Lisp**, a **lista** é uma estrutura fundamental. Uma expressão Lisp pode ser representada como uma lista e, ao mesmo tempo, programas Lisp também podem ser tratados como estruturas de dados. Essa característica foi especialmente importante para a inteligência artificial, porque permitia construir, analisar e modificar estruturas simbólicas de maneira bastante flexível.

### Estilo de computação

O **Fortran** favorece um estilo voltado para cálculos e transformação de valores numéricos. O programador descreve operações matemáticas e algoritmos que serão executados sobre números, normalmente seguindo uma sequência de instruções.

O **Lisp** favorece a computação simbólica, com forte utilização de funções, listas e recursão. Em vez de simplesmente calcular números, um programa pode manipular uma expressão como uma estrutura, examinando seus componentes e construindo novas estruturas.

---

## 10 - Ortogonalidade, regularidade e simplicidade

Uma linguagem é **ortogonal** quando há poucas restrições sobre como seus recursos podem ser combinados. Por exemplo, se um determinado tipo de dado pode ser usado em uma construção, seria desejável que também pudesse ser usado em outras construções de maneira consistente.

Isso aumenta a regularidade da linguagem e facilita prever o comportamento de programas.

O **ALGOL 68** é um exemplo importante porque buscou um alto grau de ortogonalidade e regularidade. Seus projetistas procuraram construir uma linguagem na qual conceitos pudessem ser combinados de maneira sistemática, evitando muitas exceções e casos particulares.

Por exemplo, o ALGOL 68 tinha um sistema de tipos bastante geral, permitindo que diferentes tipos de dados fossem utilizados em várias construções da linguagem. Essa abordagem produzia uma linguagem regular, pois seus recursos obedeciam a princípios relativamente uniformes.

Porém, essa mesma generalidade tornou o ALGOL 68 complexo. O usuário precisava compreender muitas regras e possibilidades de combinação.

Assim, uma linguagem pode ser **regular**, isto é, consistente e com poucas exceções, sem ser necessariamente **simples** de aprender ou utilizar.

### Regularidade

Os recursos da linguagem seguem regras uniformes e previsíveis.

### Simplicidade

Existem poucos conceitos e regras que o programador precisa aprender.

### Uma linguagem muito ortogonal é automaticamente fácil de usar?

**Não.**

A ortogonalidade tende a facilitar o aprendizado porque reduz exceções e torna o comportamento da linguagem mais previsível. Porém, uma ortogonalidade excessiva pode aumentar a complexidade quando permite muitas combinações possíveis entre os recursos.

Portanto, existe uma relação de equilíbrio.

Uma linguagem com **baixa ortogonalidade** pode ser difícil porque possui muitas exceções e regras especiais.

Uma linguagem **extremamente ortogonal**, por outro lado, pode ser difícil porque oferece um grande número de combinações e conceitos gerais que o programador precisa compreender.

---

## 11 - Cadeia de influência: ALGOL, Pascal e C

### ALGOL 60 → Pascal → C

O **ALGOL 60** foi uma das principais referências para o desenvolvimento das linguagens imperativas estruturadas. Introduziu uma organização mais sistemática para estruturas de controle e influenciou fortemente linguagens posteriores.

**Pascal**, criada por **Niklaus Wirth**, recebeu forte influência do ALGOL. Seu objetivo incluía oferecer uma linguagem estruturada, relativamente simples e adequada ao ensino de programação. Pascal manteve a orientação **imperativa**, baseada em comandos que alteram o estado do programa.

**C** também pertence a essa linhagem. Foi influenciada por linguagens anteriores da família ALGOL, especialmente por sua estrutura sintática e pelo conceito de programação estruturada, embora tenha incorporado características próprias, como maior proximidade com o hardware e operações sobre memória.

### Contraste com Prolog

O **Prolog** segue uma proposta bastante diferente. Enquanto ALGOL, Pascal e C pertencem predominantemente ao paradigma **imperativo**, Prolog é uma linguagem **lógica/declarativa**.

Nas linguagens imperativas, o programador descreve **como** o computador deve realizar uma tarefa. Um programa é composto por comandos, atribuições, estruturas de repetição e decisões que determinam uma sequência de ações e modificam o estado da memória.

Em **Prolog**, o programador descreve principalmente **o que é verdadeiro sobre o problema**, por meio de fatos e regras. A linguagem utiliza mecanismos de inferência e busca para encontrar respostas que satisfaçam as relações especificadas pelo programa.

Assim, o programador não precisa indicar explicitamente uma sequência de passos equivalente àquela encontrada em uma linguagem imperativa.

### Exemplo simples

**Imperativo:**

> "Pegue X, compare X com Y, faça uma atribuição e repita enquanto determinada condição for verdadeira."

**Declarativo/Prolog:**

> "X e Y possuem determinada relação; estas são as regras que definem essa relação."

Questões 1, 2 e 6

1 - Genealogia das linguagens e influência histórica

A genealogia das linguagens não é uma escada de progresso porque as novas linguagens não são necessariamente criadas para substituir completamente as anteriores. Elas podem surgir para solucionar limitações específicas, melhorar desempenho, facilitar a programação ou atender a novas necessidades.

A maioria das linguagens recebe influência de linguagens que já existiam, seja na sintaxe, na organização dos elementos ou nos conceitos utilizados. Por isso, uma linguagem nova pode coexistir com a anterior e ser escolhida de acordo com a necessidade do projeto e com o conhecimento dos programadores sobre cada linguagem.

Dois fatores históricos que permitem que uma linguagem influencie outra sem substituí-la são:

Necessidades diferentes: uma nova linguagem pode ser criada para atender a um domínio ou problema específico, enquanto a linguagem anterior continua sendo adequada para outras aplicações.

Herança de conceitos: linguagens novas frequentemente aproveitam características, estruturas e ideias de linguagens anteriores, mantendo parte de sua influência mesmo quando deixam de ser amplamente utilizadas.

Com base no livro Conceitos de Linguagens de Programação, capítulo 2, páginas 50 e 51, podemos observar essa influência através de exemplos como Caml, que possui um dialeto que suporta programação orientada a objetos. Como evolução, foi criado o OCaml, que possui relação com a família de linguagens funcionais derivadas de ML. Da mesma forma, F# é uma linguagem tipada que recebeu influência de OCaml.

Objetivos: obj01, obj05 · Referência: Sebesta, cap. 2, páginas PDF 50, 51.

2 - Plankalkül e sua importância histórica

Mesmo não tendo sido implementada em sua época, Plankalkül é relevante para a história das linguagens de programação porque seu projeto antecipou recursos que posteriormente seriam utilizados em outras linguagens.

Três recursos antecipados por seu projeto foram:

Apenas variáveis que não fossem de ponto flutuante precisarem ser explicitamente declaradas.

A ideia de sentenças compostas.

A possibilidade de utilizar qualquer número de dimensões em um vetor.

Um desses recursos que merece destaque é a possibilidade de utilizar vetores com qualquer número de dimensões. Isso é relevante porque permite representar estruturas de dados mais complexas, como matrizes e estruturas multidimensionais, proporcionando maior flexibilidade ao programador.

Dessa forma, mesmo sem ter sido implementada naquele período, Plankalkül demonstrou conceitos que estavam à frente de seu tempo e que posteriormente apareceriam em linguagens de programação mais modernas.

Objetivos: obj01, obj02 · Referência: Sebesta, cap. 2, páginas PDF 52, 53.

6 - ALGOL 60: influência além da adoção comercial

Três contribuições de ALGOL 60 ultrapassaram sua adoção comercial:

Estrutura de blocos: ALGOL 60 introduziu uma organização estruturada do código por meio de blocos, permitindo definir escopos para variáveis e facilitando a organização de programas complexos. Esse conceito influenciou diversas linguagens posteriores.

Recursividade: a linguagem permitiu que procedimentos chamassem a si mesmos, tornando possível resolver problemas de forma mais natural, principalmente em estruturas hierárquicas e algoritmos matemáticos.

Formalização da sintaxe: ALGOL 60 teve grande importância na definição formal da sintaxe das linguagens de programação. A utilização da BNF (Backus-Naur Form) para descrever sua gramática tornou-se uma referência para a especificação de outras linguagens.

Uma linguagem pode ser muito influente sem dominar o mercado porque sua importância não depende apenas de sua adoção comercial ou da quantidade de usuários. ALGOL 60, por exemplo, teve adoção comercial limitada, mas seus conceitos foram incorporados ou serviram de inspiração para linguagens posteriores, como Pascal, C e outras linguagens estruturadas.

Assim, uma linguagem pode não ser comercialmente dominante, mas ainda moldar a evolução da programação e influenciar o projeto de várias gerações de linguagens.

Objetivos: obj02, obj04 · Referência: Sebesta, cap. 2, páginas PDF 66, 71.





12. Modele em linguagem natural uma pequena base Prolog com dois
fatos, uma regra e uma consulta. Explique por que isso representa
programação lógica, não apenas armazenamento de dados.

% Fatos
pai(joao, maria).
pai(joao, pedro).

% Regra
irmao(X, Y) :-
    pai(P, X),
    pai(P, Y),
    X \= Y.

% Consulta
?- irmao(maria, pedro).

Fato 1:  João é pai de Maria
Fato 2: João é pai de Pedro
Regra: Duas pessoas são irmãs se tem o mesmo pai e são pessoas diferentes.
Consulta: Maria e Pedro são irmãos?
Isso é programação lógica porque não contem explicitamente o fato "Maria é irmã de Pedro", ela contém conhecimento na forma de fatos e regra, e o mecanismo de inferência do Prolog procura uma solução para a consulta.


13. Ada resultou de requisitos e projeto em grande escala. Analise como
confiabilidade, tipos, pacotes e concorrência se relacionam ao domínio
de sistemas críticos.

Ada foi projetada para atender principalmente sistemas de alta confiabilidade, como aplicações militares, aeroespaciais, ferroviárias e de controle industrial. Por isso, suas características de linguagem estão diretamente relacionadas às necessidades de sistemas críticos.

Confiabilidade: Ada procura detectar erros o mais cedo possível. Verificações de tipos, limites de arrays e outras checagens em tempo de execução reduzem a possibilidade de falhas silenciosas. Além disso, a linguagem favorece código estruturado e explícito, facilitando testes, revisão e certificação.
Tipos: seu sistema de tipagem é muito forte e permite criar tipos específicos para representar conceitos do domínio. Isso desloca parte da detecção de erros do teste em execução para a compilação.
Pacotes: os pacotes permitem separar especificação e implementação e organizar sistemas grandes em módulos. Essa separação favorece encapsulamento, reutilização e manutenção, além de permitir que equipes diferentes trabalhem em componentes bem definidos.
Concorrência: Ada possui mecanismos próprios para tarefas concorrentes e comunicação entre elas, incluindo tasks e mecanismos de sincronização. Isso é importante em sistemas de tempo real, nos quais sensores, controladores e atuadores podem precisar operar de maneira coordenada e previsível.


15. A primeira aplicação de Java não foi a Web, mas a Web impulsionou
sua adoção. Explique como mudanças de contexto podem reposicionar
uma linguagem.

Java foi projetada inicialmente, por volta de 1990, pela Sun Microsystems para dispositivos eletrônicos de consumo, como eletrodomésticos e sistemas de TV interativa. A equipe buscava uma linguagem mais simples, confiável e adequada à programação orientada a objetos do que C e C++. Entretanto, os produtos para os quais Java foi inicialmente utilizada não chegaram a ser comercializados.

A situação mudou com a popularização da World Wide Web a partir de 1993, especialmente com o surgimento dos navegadores gráficos. As características de Java passaram a ser úteis para um novo domínio: a programação Web. Os applets Java, pequenos programas que podiam ser executados no navegador e ter sua saída incorporada às páginas Web, tornaram-se populares durante a segunda metade da década de 1990. Segundo Sebesta, nos primeiros anos de popularidade do Java, a Web foi sua aplicação mais comum.

Portanto, o caso do Java demonstra que o sucesso de uma linguagem depende não apenas de suas características técnicas, mas também do contexto em que essas características são utilizadas. Uma linguagem pode ser criada para um determinado domínio e não encontrar mercado inicialmente; posteriormente, uma mudança tecnológica pode criar um novo domínio no qual suas características se tornam extremamente valiosas. No caso do Java, a Web transformou uma linguagem inicialmente destinada a eletrônicos de consumo em uma das principais linguagens para aplicações Web de sua época.