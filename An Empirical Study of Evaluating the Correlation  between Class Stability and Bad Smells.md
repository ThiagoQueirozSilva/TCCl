# An Empirical Study of Evaluating the Correlation  between Class Stability and Bad Smells

M. H. Yahia, M. I. Amro and M. R. Alshayeb, "An Empirical Study of Evaluating the Correlation between Class Stability and Bad Smells," 2021 22nd International Arab Conference on Information Technology (ACIT), 2021, pp. 1-5, doi: 10.1109/ACIT53391.2021.9677443. https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9677443

## 1.Fichamento de Conteúdo

O artigo trata sobre qualidade de software onde é feita uma análise sobre a correlação entre a estabilidade de um projeto e as <em> bad smells </em> presentes no mesmo. Sendo assim o objetivo do estudo é realizar uma análise empirica sobre a influência das <em> bad smells </em> na estabilidade da classe que se trata de um dos atributos utilizados para medir a manutenibilidade de um sistema. O trabalho visa auxiliar na expansão de conhecimento sobre o design de software. Para realizar o estudo foi utilizado 2 grandes e populares repositórios Java de código aberto sendo eles o Eclipse e o Android. Destes repositórios foram coletadas código de 3 versões diferentes para cada totalizando então 504 Classes Java para análise. Para a coleta das <em> bad smells </em> foi utilizado um plugin, presente na plataforma de desenvolvimento Java Eclipse, que faz a análise das classes do sistema e retorna as suas respectivas <em> bad smells </em>. Quanto à avaliação do atributo de estabilidade do sistema foi utilizada a métrica <em> CSM(Class Stability Metric) </em>. A correlação entre as <em> bad smells </em> e a estabilidade da classe foi utilização o Microsoft Excel e Minitab. Por fim ao se utilizar 0.05 como o limite para corte de <em> P-Value </em> e observar que ao alterar de versão e o número de <em> bad smells </em> aumentarem a estabilidade da classe obteve um decréscimo indicando uma correlação negativa. Sendo assim a hipótese de que repositórios com uma boa estabilidade tendem a ter um número baixo de <em> bad smells </em>. 


## 2.Fichamento Bibliográfico

- <em> bad semlls </em> (maus cheiros) se tratam de consequências negativas no sistema decorrentes de um design, planejamento e implementação mal feitas. (Página 1)
- <em> class stability </em> (estabilidade da classe) se trata de um atributo da manutenibilidade de um software que verifica aspectos de como o sistema se comporta após a adição novo código. (Página 1).
- <em> OO Design </em> (design orientado a objetos) se trata de uma maneira de se pensar em um projeto de software (planejar, modelar) de acordo com a orientação por objetos. (Página 5)

## 3.Fichamento de Citações
- "Our objective in this research is to find empirical evidence of the association between the bad smells and class stability"
- "As we used the 0.05 as the cutoff P-value; i.e., a bad  smell that had a P-value less or equal to 0.05 in all  releases should be included in the relationship. Thus, we accept the hypothesis because, as showed in TABLE V. and TABLE VI. "
- "This correlation means that  when we move from one version to another, (e.g. from  Eclipse 2.0 to Eclipse 3.5) there is a high confidence in negative correlation and that means when the class stability increases; the bad smalls decreases."
- "Understanding how the design structures of systems evolve and where the bad smells are likely to occur may enhance the knowledge about the relationship between 
stability and bad smells."

