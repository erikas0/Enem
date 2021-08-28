# Enem
Análise Exploratória das notas de Matemática do Enem dos anos de 2017 a 2019

👩‍🎓 Nesse trabalho foi analisado as notas de 1.020.953 estudantes que realizaram o Exame Nacional do Ensino Médio (ENEM) entre 2017 a 2019.

‼ A média das notas de matemática desses estudantes foi **506,84 pontos**.

‼ No intervalo entre **0 pontos**, nota mínima entre os estudantes analisados, e **994,40 pontos**, nota máxima de matemática entre os estudantes analisados, as notas variaram em média **142,73 pontos**. Com o auxílio do gráfico da frequência é possível identificar que **37.469 alunos tiraram notas próximo de 0**.

<p align="center">
  <img src="/images/frequencia.png" width="500" title="hover text">
</p>

‼ Com o auxílio do Box-Plot das notas de Matemática, percebe-se que alguns alunos tiraram notas próximas de 0, e foram considerados como valores discrepantes, assim como alunos com notas acima de 819,84 pontos. Ainda com auxílio do Box-Plot, observa-se que 25%, primeiro quartil, dos estudantes tiraram **notas entre 0 e 435,60 pontos**. 50%, mediana, dos estudantes tiraram **notas abaixo de 502 pontos**. 75%, terceiro quartil, dos estudantes analisados tiraram **notas abaixo de 589,3 pontos** e 25% dos estudantes tiraram **notas entre 589,4 e 994,40 pontos**. 

<p align="center">
  <img src="/images/boxplot.png" width="500" title="hover text">
</p>

🌎 Em relação a nota média, **os estados que obtiveram maior descaque foram estados do Sul e Sudeste do país**: Santa Catarina com 532,7 pontos, Minas Gerais com 527,94 pontos, São Paulo com 527,78 pontos, Rio de Janeiro com 524,04 pontos e o Espiríto Santo com 520 pontos. **Os 5 estados que tiveram as piores médias foram os estados do Norde e Nordeste do país**: Amapá com 468,68 pontos, Acre com 469,53 pontos, Amazonas com 471,59 pontos, Maranhão com 472,55 pontos e o Pará com 476,29 pontos. A distância das notas médias do Amapá, que obteve a pior nota média entre os estados, e Santa Catarina, com a melhor nota entre os estados, foi de 64,02 pontos.

<p align="center">
  <img src="/images/uf.png" width="500" title="hover text">
</p>

🏫 Em relação ao tipo de escola frequentado pelo estudante, **estudantes que frequentaram escolas no exterior tiveram a melhor média na nota de matemática**, com 618.89 pontos, os estudantes que frequentaram o ensino privado no país obtiveram a média 574,28 na nota de matemática e os estudantes da escola pública obtiveram a menor média da nota de matemática, 487.31 pontos.

👀 665.924 estudantes não responderam qual o tipo de escola frequentou, o que corresponde a 65.25% dos estudantes analisados


<p align="center">
  <img src="/images/escola.png" width="500" title="hover text">
</p>

♦ A correlação entre as notas de Linguagens e Código, Ciências Humanas, Ciências da Natureza e Redação com a nota de matemática **apresenta uma baixa correlação**, o que indica que as notas de Linguagens e Código, Ciências Humanas, Ciências da Natureza e Redação **não influenciam tanto na nota de Matemática**. Em relação a essas notas, a nota de Redação é a que apresenta uma correlação mais alta, de 0,34, contudo ainda é uma correlação muito baixa, por isso não apresenta uma influência na nota de Matemática. A correlação entre a idade e a nota de Matématica é negativa, o que indicaria que quanto mais novo o estudante é, melhores são as suas notas, porém a correlação é muito baixa, -0,096, por isso não podemos afirmar isso, pois a idade também não influencia nas notas de matemática

<p align="center">
  <img src="/images/cor.png" width="800" title="hover text">
</p>

‼ Esses gráficos apresentam diagramas de dispersão das notas em relação a nota de matemática (eixo y de cada gráfico).

♦ Observando o diagrama de dispersão da nota de Linguagens e Códigos (LC) com a nota de Matemática (MT), constata-se que **um conjunto de alunos teve notas muito baixa em LC e em MT**, **outro conjunto tirou notas muito baixas em MT, entretanto suas notas de LC foram relativamente positivas**, **outro conjunto teve notas muito baixas em LC, contudo suas notas em MT foram relativamente boas**. Olhando a parte central do diagrama, observa-se que **um grupo majoritário de estudantes tiveram notas acima de 300 pontos em LC e MT**. Pode-se observar que o grupo de alunos que tirou, por exemplo, 400 pontos, varia entre 380 pontos em MT até notas acima dos 800 pontos, portanto a variabilidade da outra nota em um determinado ponto é alta. O mesmo vale para as notas de MT em comparação com as de LC. **Em relação ao diagrama de dispersão da nota de Ciências Humanas (CH) e MT, pode-se dizer que o comportamento é semelhante ao diagrama de dispersão de LC**.

<p align="center">
  <img src="/images/dispersao.png" width="500" title="hover text">
</p>

♦ Observando o diagrama de dispersão da nota de Ciências da Natureza (CN) e MT, constata-se que **um conjunto de alunos teve notas muito baixa em CN e em MT, outro conjunto tiraram notas muito baixas em MT, entretanto suas notas de CN foram relativamente positivas, outro conjunto teve notas muito baixas em CN, contudo suas notas em MT foram relativamente boas**. Olhando a parte central do diagrama, observa-se que um grupo majoritário de estudantes tiveram notas acima de 300 pontos em CN e MT. Pode-se observar que o grupo de alunos que tiraram 800 pontos em CN obteve notas altas em MT, acima de 700 pontos, **portanto, com a exceção do grupo que obteve 0 em MT e notas altas em CN, pode-se dizer que estudantes que têm notas altas em CN, têm notas altas em MT*.

♦ Observando o diagrama de dispersão da nota de Redação com a nota de MT, constata-se que existe o conjunto de estudantes que tiveram notas muito baixas em MT, tem uma variabilidade muito grande em relação as notas de Redação, pois alguns tiraram notas muito baixas, outros tiraram notas razoavelmente boas e outros tiraram notas excelentes. Em relação ao grupo majoritário, percebe-se que **alunos que tiraram notas de Redação entre 0 e 200 pontos, não tiveram um bom desempenho em matemática, ficando com notas entre 400 e 600 pontos**. **A medida que a nota de Redação aumenta, aumenta, também, a variabilidade das notas de MT**. Notas de Redação próximas de 1000 pontos, tiveram estudantes que tiraram notas entre 300 pontos e próximas de 1000 pontos, sendo assim tiveram uma alta variabilidade.
