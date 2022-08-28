# House of Cards: Code Smells in Open-source C# Repositories

T. Sharma, M. Fragkoulis and D. Spinellis, "House of Cards: Code Smells in Open-Source C# Repositories," 2017 ACM/IEEE International Symposium on Empirical Software Engineering and Measurement (ESEM), 2017, pp. 424-429, doi: 10.1109/ESEM.2017.57. https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8170129

## 1.Fichamento de Conteúdo

O artigo trata sobre <em> code smells </em> em repositórios C# de código aberto do GitHub. O trabalho visa explorar os relacionamentos entre as <em> code smells </em> 
e fornecer uma compreensão maior sobre a expansão das <em> code smells </em> em códigos C# e auxiliar em estudos para a detecção das mesmas. Para a coleta dos dados  primeiramente foi inicialmente feita uma classificação dos repositórios utilizando a ferramenta RepoRepear utilizada para avaliar em diversos aspectos o repositório como qualidade, comunidade, integração continua, documentação, história, licensa e estado. Somente repositórios com uma determinada pontuação na ferramenta seriam avaliados. Foram coletados 2400 repositórios e analisados 1988, excluindo código relacionado a testes, com a ferramenta Designite. Foram análisadas um total de 19 <em> design smells </em> e 11 <em> implementation smells </em> No trabalho foram respondidas 4 questões de pesquisa na primeira foi feita uma distribuição a respeito de cada <em> code smell </em> analisada e a frequência em que apareceram. Para a segunda foi analisada qual a relação entre a ocorrência de <em> implementation </em> e <em> design smells</em> para isso foi utilizado o coeficiente de correlação de Spearman entre os 2 tipos de <em> code smells </em> para cada repositório. Na terceira pergunta foi análisada a correlação entre as <em> code smells </em> utilizando uma formula de co-ocorrencia criada por Connor e como resultado obteve-se que <em> unutilized abstraction </em> e <em> deep hierarchy </em> apresentaram a maior e menor co-ocorrencia respectivamente. Por fim, a quarta pergunta foi questionada se o tamanho do repositório (número de linhas de código) influencia na densidade de ocorrencias de <em> code smells </em> e chegou-se ao resultado de que o tamanho não impacta signativamente na quantidade de <em> code smells </em>. 

## 2.Fichamento Bibliográfico

- "Implementation smells" (cheiros de implementação) se trata de más práticas ao se implementar o código. (Página 1)
- "Design smells" (cheiros de design) se trata de estruturas no código que violam princípios de design, ou seja, acontecem quando se tem um design pouco trabalhado o que o torna frágil e difícil de evoluir. (Página 1) 
- "Maintainability" (manutenabilidade) se trata de um dos atributos utilizados para avaliar a qualidade de um software, neste é verificado a capacidade do software de sofrer alterações ao longo do seu ciclo de vida. (Página 1) 

## 3.Fichamento de Citações
- "By exploring relationships between smell types we seek to find and comprehend models of smell occurrence and expansion"
- "Knowing the commonly occurring smells together may also be used to improve accuracy of smell detection mechanisms. This study can benefit software developers to help them understand the characteristics of relatively a wide range of smells and their potential implications"
- "From the implementation smells side, IMN (magic number) and ILS (long statement) are the most frequently occurring smells."
- "Interestingly, DDA (duplicate abstraction) is one of the most frequently occurring design smells but IDC (duplicate code) is one of the least frequently occurring implementation smells. It is because the scope of both the smells differs significantly;"
- "It implies that whenever unutilized abstraction or magic number smells are found in C# code, it is very likely to find other smells from the same smell category in the project."
- "According to the current study no strong correlation is evident between the number of smell occurrences and project size."
