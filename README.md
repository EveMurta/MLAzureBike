## Machine Learning Azure Bikes
Repositorio com modelo de previsao aluguel bikes

##Como criar um modelo preditivo 

#Passo 1: Configuração do Ambiente
Acessando o portal Azure, se faz nescessaria a criacao de um novo recurso do Azure Machine Learning e um Workspace. Preencha todos os dados nescessarios referentes a configuracao de onde os dados serao armazenados, como nome, regiao, sorage account, acesso publico ou privado, dentre outros. Apos configurar e finalizar a preparacao do ambiente podemos seguir para o studio.

#Passo 2: Preparação dos Dados:
Apos ser redirecionado ao https://ml.azure.com/ estaremos criando nosso work studio.
Na sessao ML automatizado, crie um novo trabalho e siga o passo a passo preenchendo todos os dados.

Nesse projeto utilizei o regressao como tarefa para obter uma previsao continua a respeito do aluguel de bicicletas. 
A fonte de dados utilizados podem ser encontrados apartir da url: https://aka.ms/bike-rentals

Carregue o conjunto de dados de aluguel de bicicletas no Azure Machine Learning Studio.
Realize a limpeza e transformação necessárias nos dados, como tratamento de valores ausentes e codificação de variáveis categóricas.

#Passo 3: Treinamento do Modelo
Escolhendo o Algoritmo de Machine Learning:

Escolhi os algoritmo de regressão como metrica raiz do erro quadratico medio normalizadocom e modelos Random Forest e LightGBM.

Divisão dos Dados:
Escolhi como tipo de validacao divisao e treinamento com percentual de 10%.

Apos todo o processamento do job valide suas metricas! Assim foi possivel verificar principalmnete o valor previsto e o valor real dentro das metricas estabelecidas.

