# How Gamification Affects Software Developers: Cautionary Evidence from a Natural Experiment on GitHub

L. Moldon, M. Strohmaier and J. Wachs, "How Gamification Affects Software Developers: Cautionary Evidence from a Natural Experiment on GitHub," 2021 IEEE/ACM 43rd International Conference on Software Engineering (ICSE), 2021, pp. 549-561, doi: 10.1109/ICSE43902.2021.00058: https://ieeexplore.ieee.org/document/9402097

## 1.Fichamento de Conteúdo

O artigo em questão trata sobre a influência da gamificação sobre desenvolvedores de software durante o processo de desenvolvimento. 
Para isso é feita uma análise de dados de uma plataforma de hospedagem de código e versionamento, o GitHub. Os dados analisados dizem a respeito do
impacto da retirada de dois contadores, feita pela plataforma em 2016, que rastreavam a atual e a maior sequência de contribuições diárias de um
desenvolvedor. Para a coleta dos dados foi acessado a base de dados GHTorrent que se trata de um banco de dados atualizado com os dados retirados 
do GitHub REST API. Os dados acessados foram disponibilizados no ano de 2019 com uma quantidade total de 32.5 milhões de desenvolvedores 125 milhões 
de projetos, 100 milhões de <em> issues </em> abertas. Foram considerados apenas desenvolvedores que estavam ativos durante a mudança nos contadores e também aqueles
que possuem mais de 100 <em> commits </em> com <em> timestamps </em> inválidos para retirar desenvolvedores que fizeram alguma manipulação em suas atividades e contas bot. Ainda 
sobre a coleta de dados foram mantidos apenas os desenvolvedores que continham pelo menos 100 <em> commits </em> totais, que continham um tipo “USR” e por fim que  continham
uma geolocalização associada ao GHTorrent para que fosse possível calcular a sequência de contribuições diárias do usuário de acordo com a data local. Em seguida 
foram tabuladas as atividades de cada desenvolvedor para que fosse feita a contagem da sequência de contribuições, para contar como uma contribuição estas atividades 
deveriam estar associadas a um projeto <em> standalone </em>. Foi feita também uma filtragem para cada tipo de contribuição sendo elas <em> commits </em>, <em> pull requests </em> e <em>issues</em>. Por fim restaram 433.138 desenvolvedores, 290 milhões de contribuições. A partir dos dados coletados foram respondidas 4 RQs(<em> Research Question </em>) que foram estabelecidas
sendo elas: RQ1: O comportamento dos desenvolvedores mudou significativamente após a retirada dos contadores? RQ2: O tempo e distribuição das atividades do desenvolvedor
foram alterados? RQ3: Os desenvolvedores utilizam os contadores para definir e atingir metas pessoais? RQ4: Houve uma mudança significativa na correlação do comportamento
das sequencias na rede social?

## 2.Fichamento Bibliográfico
- Gamification (Gamificação) aplicação das estratégias de jogos em atividades relacionadas ao desenvolvimento de software como contador de contribuições em uma plataforma de hospedagem de código
- associated geolocation from GHTorrent (geolocalização associada do GHTorrent) o armazenamento da geolocalização do usuário que realizou a contribuição para que seja feito o cálculo de sequência de contribuições diárias 
- streaking (acumular) se trata de uma sequência de contribuições diárias, ou seja, quando o desenvolvedor realiza contribuições em uma sequência de dias ininterruptos 

## 3.Fichamento de Citações

- "We interpret this as a population of developers giving up their streaks gradually in response to the design change."
- "In summary, we found evidence that long streaks were abandoned following the design change, and that new streaks be came significantly less common"
- "If this is the case, we expect that users on long streaks before the change are significantly more likely to have days in which they do the minimum activity to extend their streak"
- "We have seen evidence that many developers stopped streaking after the counters were removed, and that this reflected changing patterns of contribution."
- "This suggests that some developers did not need the counters to achieve their goals."
- "The first is that user responses to gamification can be highly varied."
- "This suggests that the signals provided by the streak counters were indeed a conduit for peer effects in the social network of GitHub developers."
- "Long streaks of uninterrupted contributions may lead to burnout."
