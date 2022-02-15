# padroes_projeto
Exemplos de padrões de projeto

Os padrões de projeto podem ser separados em 3 categorias: Estrututal, Criacional e Comportamental.
Esse projeto apresenta a implementação de alguns desses padrões.

Strategy
O Strategy é um padrão de projeto comportamental que permite que 
você defina uma família de algoritmos, coloque-os em classes separadas, 
e faça os objetos deles intercambiáveis.

Chain of Responsability
O Chain of Responsibility é um padrão de projeto comportamental que 
permite que você passe pedidos por uma corrente de handlers. 
Ao receber um pedido, cada handler decide se processa o pedido ou o 
passa adiante para o próximo handler na corrente.

Template Method
O Template Method é um padrão de projeto comportamental que define o esqueleto de um 
algoritmo na superclasse mas deixa as subclasses sobrescreverem etapas específicas do 
algoritmo sem modificar sua estrutura.

Decorator
O Decorator é um padrão de projeto estrutural que permite que você acople novos 
comportamentos para objetos ao colocá-los dentro de invólucros de objetos que 
contém os comportamentos.
Sempre que percebemos que temos comportamentos que podem ser compostos por 
comportamentos de outras classes envolvidas em uma mesma hierarquia, como 
foi o caso dos impostos, que podem ser composto por outros impostos. 
O Decorator introduz a flexibilidade na composição desses comportamentos, 
bastando escolher no momento da instanciação, quais instancias serão utilizadas 
para realizar o trabalho.

State
A principal situação que faz emergir o Design Pattern State é a necessidade 
de implementação de uma máquina de estados. Geralmente, o controle das possíveis 
transições são vários e complexos, fazendo com que a implementação não seja simples.
 O State auxilia a manter o controle dos estados simples e organizados através da 
criação de classes que representem cada estado e saiba controlar as transições.

Builder
O Builder é um padrão de projeto criacional que permite a você construir objetos 
complexos passo a passo. O padrão permite que você produza diferentes tipos e 
representações de um objeto usando o mesmo código de construção.



Mais referencias em: https://refactoring.guru/pt-br <br>
Curso: https://cursos.alura.com.br/course/design-patterns-dotnet
