# TERA Desafio3 - Classificação

Dentre os modelos experimentados, os que envolvem árvores foram superiores ao logístico.

Analisando as matrizes, os modelos de árvores foram bastante superiores acredito que seriam necessárias medidas complementares para que pudessem ser evitadas as fraudes até mais simples computacionalmente como um histórico da conta, se a conta já foi usada em fraudes, tanto ativa como passiva, seria importante ter essa informação para agregar ao modelo.

Eu queria ter uma resposta definitiva sobre o treinamento dos modelos. Porém não tive os recursos necessários para explorá-los melhor, como uma GPU para acelerar os processos. Então, com base no que eu consegui experimentar, o melhor modelo foi o de Árvore de Decisão. Não explorei muito os parâmetros pelos altos tempos de processamento.

Acredito que as features utilizadas foram boas o suficiente para a situalçao. Eu criei uma feature que diz se a conta está sendo utilizada pela primeira vez.

### Edit:

Ao conseguir rodar um notebook utilizando GPU, o XGBoost foi o melhor modelo de todos. Ultra rápido e com as melhores métricas. Fiquei bastante surpreso.

<center> <img src="https://media.giphy.com/media/izspP6uMbMeti/giphy.gif" width=500>


