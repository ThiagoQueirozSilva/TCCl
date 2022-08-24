# Are Code Smell Co-occurrences Harmful to Internal Quality Attributes? A Mixed-Method Study

 Martins, Julio; Bezerra, Carla; Uchôa, Anderson; Garcia, Alessandro. "Are Code Smell Co-occurrences Harmful to Internal Quality Attributes? A Mixed-Method Study",
  in XXXIV Brazilian Symposium on Software Engineering (SBES): https://www.researchgate.net/publication/343849798_Are_Code_Smell_Co-occurrences_Harmful_to_Internal_Quality_Attributes_A_Mixed-Method_Study

## 1.Fichamento de Conteúdo

O artigo trata sobre um assunto que é de bastante relevância para a área da Engenharia de Software que são as <em> code smells </em>. Ele visa estudar a co-ocorrência entre
as <em> code smells </em> no contexto de repositórios de sistemas privados, fazendo a análise de 11 <em> releases </em> de 3 diferentes repositórios. O objetivo do trabalho
é analisar o impacto da correlação das <em> code smells </em> nestes sistemas fazendo um estudo sobre quais são as co-ocorrencias mais frequentes, como a remoção destas
co-ocorrencias impacta na qualidade do código e por fim quais são as co-ocorrências mais dificeis de se remover do código. Foi feita a detecção de 7 <em> code smells </em> diferentes
a partir da ferramenta JSpIRIT, dentre os <em> code smells </em> detectados estão: <em> Future Envy, God Class, Disperse Coupling, Intensive Coupling, Refused Parent Bequest,
Shotgun Surgery, Long Method </em>. Foi feito então o cálculo da co-ocorrencias destas pelos autores sem o auxílio de ferramentas. Com isso já era possível saber quais eram
as co-ocorrencias mais frequentes que foram: <em> God Class–Long Method, Disperse Coupling–Long Method</em> e também chegou-se a conclusão que quanto mais os projetos evoluiam
maior era a ocorrência de co-ocorrências de <em> code smells </em>. Para se responder o restante das questões foi feito um treinamento com as pessoas que participariam do 
experimento demonstrando como identificar as co-ocorrencias, qual a maneira correta de se remover e qual o propósito do estudo. Sendo assim foi possível que os sistemas estudados
evoluissem e passassem por refatorações pelos próprios desenvolvedores afim de remover co-ocorrencias de <em> code smells </em>. Por fim foi possível responder as duas últimas questões ao se 
fazer uma relação entre o que foi produzido e a qualidade a partir das métricas de qualidade CK(Chidamber & Kemerer object-oriented metrics suite). Com foi concluído que 
a remoção das co-ocorrencias não teve impacto em métricas de coesão e acoplamento mas obteve um grande impacto em se tratando da complexidade do sistema que obteve um decrescimo
com a remoção das mesmas. Para projetos futuros os autores propuseram a análise de mais sistemas(tanto de código aberto quanto privados) para a identificação de co-ocorrencias, a empregação de mais <em> code smells </em>
no estudo e por fim a identificação de qual a co-ocorrencia mais prejudicial para a qualidade de um sistema.


## 2.Fichamento Bibliográfico
- <em> Code Smell Co-occurrences </em> se trata de como <em> code smells </em> aparecem de maneira simultânea dentro de um método ou classe
- <em< code smell </em> se trata de "problemas" que aparecem em um código computacional que remetem a práticas ruins e que impactam na clareza e qualidade do código


## 3.Fichamento de Citações

- "We summarize our study goal as follows [53]: (i) analyze the code smells co-occurrences; for the purpose of understating their impact on internal attributes of software quality; with respect to
which code smells tend to co-occur together, (ii) the removal of code smell co-occurrences before and after software refactoring, and (iii) which are the most difficult co-occurrences to refactoring; from the
viewpoint of researchers and software developers; in the context of three closed-source systems."
- "The main findings of our study were: (i) God Class–Long Method nd Disperse Coupling–Long Method are the most frequent cooccurrences in the three systems and also the most difficult cooccurrences to refactor in developers’ perspective; (ii) co-occurrences
increase during the development of the system; (iii) the removal of hese anomalies has a negative impact on the cohesion and coupling attributes; and (iv) the removal of code smells co-occurrences suggests a significant decrease in the complexity of the systems."
- "God Class–Long Method and Disperse Coupling– Long Method co-occurrences were the most difficult to remove from the developers’ point of view"
- "As a result of study [12], the authors identified that code smells co-occurrences can cause maintenance and design problems and that more empirical studies are needed to
investigate the impact of these anomalies on the source code."