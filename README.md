Distribuição Gaussiana resolvendo problemas práticos


A distribuição normal, também conhecida como gaussiana (em homenagem a seu criador Carl Friedrich Gauss) caracteriza-se por ser perfeitamente simétrica, com a média, a mediana e a moda sendo iguais.


No entanto, encontrar uma distribuição que seja exatamente normal é raro. Por isso, em estatística, é prática comum avaliar o quão próxima uma distribuição real está da normal. No mercado financeiro, por exemplo, analisamos frequentemente os retornos diários de ações.


Ao traçar um histograma desses retornos, podemos observar a distribuição de probabilidade. Normalmente, retornos diários de ações não seguem uma distribuição normal perfeita, mas podemos analisar quão próximos estão dessa forma idealizada. Isso nos ajuda a entender melhor o comportamento dos retornos e aplicar técnicas estatísticas apropriadas.


Neste estudo temos a análise dos retornos diários das ações da Tesla, utilizando a distribuição normal como referência para avaliar o comportamento e o risco associado a esses retornos.


Seguem abaixo 3 exemplos de problemas comuns, juntamente com as soluções aplicadas a cada um deles (confira o anexo):


Problema 1 - Avaliação de risco de retornos diários:

Investidores precisam entender a distribuição dos retornos de suas ações para avaliar o risco associado aos seus investimentos. Essa análise pode ajudar a identificar se os retornos seguem uma distribuição normal ou não.


Solução:

Utilizar ferramentas de EDA para analisar a distribuição dos retornos diários.


Prob. 2 - Identificação de outliers nos retornos diários:

Outliers podem distorcer a análise dos retornos diários, afetando decisões de investimento. Identificar e tratar esses outliers é de grande importância para obter uma visão mais clara dos dados.


Solução:

Usar boxplots para identificar outliers nos retornos diários e analisar seu impacto na análise. A análise desses outliers nos informam sobre eventos extremos que impactaram o preço da ação.


Prob. 3 - Avaliação da normalidade dos retornos diários:

Muitos modelos financeiros assumem que os retornos seguem uma distribuição normal. Verificar a normalidade dos retornos diários ajuda a validar ou questionar essas suposições.


Solução:

Realizar testes de normalidade e utilizar Q-Q plots para avaliar a distribuição dos retornos diários.


Conclusão:

Foram identificados outliers, assimetria, dispersão, e se a distribuição dos retornos se aproxima de uma normal. A curtose, especificamente, ajuda a entender a "pontualidade" dos retornos diários e se a distribuição se compara com a distribuição normal.


O "p-valor de 1.571" indica que a hipótese nula (de que os dados seguem uma distribuição normal) pode ser rejeitada com um alto nível de confiança. Isso reforça a conclusão de que os retornos diários da Tesla não seguem uma distribuição normal e que há uma presença significativa de outliers.
