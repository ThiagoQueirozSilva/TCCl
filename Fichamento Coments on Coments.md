# Comments on Comments: Where Code Review and Documentation Meet

Rao, N., Tsay, J., Hirzel, M., & Hellendoorn, V. J. (2022). Comments on Comments: Where Code Review and Documentation Meet. arXiv preprint arXiv:2204.00107. https://arxiv.org/abs/2204.00107 

## 1.Fichamento de Conteúdo

O artigo em questão trata sobre a documentação em code reviews. O objetivo dos autores seria fazer uma análise sobre os comentários realizados em code reviews e assim encontrar a frequência em que aparecem avaliações a respeito da documentação do código e também classificar estas avaliações. Foram feitas 3 categorias para as avaliações coletadas sendo elas: CRC, CRN e NRC. Para a coleta de dados foi feita a busca de <em>pull requests(PRs)</em> pertencentes a 1000 projetos nas linguagens Python e Java entre janeiro de 2017 e novembro de 2020. Cada <em>pull request</em> foi subdividido em pequenas partes relacionadas às alterações realizadas totalizando aproximadamente 3,5 milhões de partes. Em seguida estas partes coletadas foram filtradas afim de obter apenas aquelas que possuíam algum tipo de comentário de revisão e que também possuíam algum tipo de comentário dentro do código podendo ser em bloco ou entre linhas de código, restando assim 370 mil partes para estudo. Por fim as partes foram divididas em 2 categorias sendo elas: Comentários relacionados a documentação e comentário perto de comentário. Na primeira é alvejado casos em que revisores de código mencionam documentação de maneira explícita e na segunda é buscado comentários de revisores que se encontram próximos ao código, demonstrando assim uma relação entre o código e o comentário. Ao fim restaram um total de 110.317 partes para serem analisadas que foram por fim divididas entre as 3 categorias citadas anteriormente (CRC, CRN e NRC). A partir dos dados coletados foram respondidas 3 questões de pesquisa sendo elas: RQ1: com que frequência comentários de avaliações dizem sobre comentários de código? RQ2: Os comentários do avaliador afetam a documentação do código da contribuição? RQ3: Quais são as intenções ao se revisar documentação? 

## 2.Fichamento Bibliográfico
- comment on comment (comentários sobre comentários): se trata do tema principal do artigo, esse termo diz respeito aos comentários que avaliadores de código que tratam sobre comentários dentro do código a ser contribuído. (Página 1)
- chunk (parte): é uma parte de uma contribuição, ou seja, é um trecho de código e comentários que foram alterados ou adicionados em um <em> pull request </em>. (Página 2)
- diff (diferença): é aquilo que foi alterado em uma contribuição no repositório de código do GitHub. (Página 2)

## 3.Fichamento de Citações
- "Based on a casual inspection of 30 randomly chosen samples fromthe comments on comments data (10 per category), we observed thatreviewers talked about documentation in several different ways"
- "We find that reviewers are much more likely to comment on a diff chunk when the contributor had already made some change to a code comment (50.8%) compared to diff chunks that only made changes to the code (15.8%)"
- "Reviewers frequently consider documentation when reviewing code"
- "Review comments in response to a code comment change often result in the code comment getting updated."
- "Most reviewer comments seek some form of clarification to increase or enshrine their understanding of the change made to the code, followed by fixing issues in the comments themselves."
- "The results from our analysis suggest that when reviewers and authors discuss documentation, it is mostly to clarify the code or documentation changes"
- "Our results clearly show that discussing documentation not only helps to achieve ashared understanding between reviewers and authors, but also benefits the understanding of other, future readers."
- "our findings may offer a path forward for supporting tool-based understanding of code changes."


