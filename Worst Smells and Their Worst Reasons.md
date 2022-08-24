# Worst Smells and Their Worst Reasons

## 1.Fichamento de Conteúdo

O artigo apresentado trata sobre <em> code smells </em>. Foi feita uma pesquisa com um grupo de desenvolvedores e também analisados repositórios da Apache afim de 
descobrir qual a pior <em> code smell </em>. Este estudo torna-se relevante dado o fato de que ao se desenvolver um projeto de software deve-se preocupar sempre com a 
qualidade do produto mas deve-se ter um limite entre o quão exigente se é em relação ao código que está sendo produzido pois pode impactar negativamente na produtividade
da equipe de desenvolvimento. Visto isso as <em> quality gates </em> devem ser pensadas de maneira a buscar apenas <em> code smells </em> que afetarão de maneira mais drástica
na qualidade do código. Sendo assim o objetivo do trabalho é identificar quais são as piores <em> code smells </em> que um código pode conter, indicando assim quais
<em> code smells </em> devem ser mais rigorosamente evitadas em projetos de software. Para se chegar em tais respostas primeiro foi feito uma pesquisa com desenvolvedores
que integram a comunidade a IEEE Technical Council on Software Engineering (TCSE) apresentando a eles um total de 133 <em> code smells </em> a partir de questionários 
que perguntavam sobre quais eram as piores para se ter em um código e o por que, ao final foram definidas 80 <em> code smells </em> como as piores das 314 que são analisadas
pela ferramenta SonarCloud indicando que estas devem ser fortemente evitadas e não trazem beneficio algum. Foi feita também uma análise sobre 24 repositórios da Apache
e a partir de um total de 667 análisando a frequencia em que as piores <em> code smells </em> aparecem em comparação com as outras, foi feito também uma análise sobre as 
mudanças nas releases e a propagação das <em> code smells </em>. Como resultado teve-se que as <em> code smells </em> mais prejudiciais aparecem na mesma frequencia que as 
não prejudicias, e que não há uma influencia direta destes 2 tipos de <em> code smells </em> nas mudanças de linhas de código. Por fim foi questionado com cada desenvolvedor
participante do questionário os motivos de 4 das 80 <em> code smells </em> (escolhidas de maneira aleatória para cada participante) serem consideradas as piores e assim por
fim encontrando um conjunto de 7 razões principais que tornam estas as piores <em> code smells </em>. 

## 2.Fichamento Bibliográfico
<em> code smells </em> se trata de uma lista de práticas que são prejudiciais ao código de um sistema e que afetam diretamente a sua qualidade, principalmente em questões de manutenção.

<em> quality gates </em> (portões de qualidade) se tratam de uma tecnologia que validam os <em> pushes </em> dos desenvolvedores ao repositório do sistema, sendo assim estes <em> quality gates </em> podem ser utilizados para verificar a presença de code smells dentro do código e assim impedir que códigos de má qualidade componham o sistema.

<em> weighted occurrences </em> (peso de ocorrencias) se trata da quantidade que uma <em> code smell </em> aparecia no texto, tratando assim não somente da frequencia 
em que ela aparecia durante as releases analisadas mas também como eram recorrentes dentro de uma mesma classe por exemplo.



## 3.Fichamento de Citações
"In conclusion, on one hand we know that fewer smells are “better”, but on the other hand we know that in the end, this is a matter of compromises driven by practical, often extraneous concerns"

"That is to say, these smells are just as frequent and just as damaging as other smells, but there is never any justifiable reason to introduce them."

" Our results show that 80 out of 314 catalogued code smells were considered as worst; i.e., the surveyed developers agreed that these 80 smells should never exist in any code base"


