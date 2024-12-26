# Validação de modelos e métricas de avaliação

Esse é um projeto de classificação com Machine Learning para identificar clientes inadimplentes em uma empresa de empréstimo de automóveis. Escrevemos num notebook do Google Colab e usamos a biblioteca Scikit-Learn com a seguinte [tabela de dados](https://github.com/mths-andrade/validacao/blob/18081a2b18d2980f325446f2f4391990c1762efb/emp_automovel.csv). Nela, temos as colunas de receita do cliente, anuidade do empréstimo, os anos de casa proprietário e assim por diante. A última coluna dessa base de dados é a coluna "inadimplente" que informa se o cliente pagou o empréstimo ou não.

O valor 0 indica que o cliente pagou o empréstimo no tempo devido. E o valor 1 significa que o cliente é inadimplente, ou seja, não pagou o empréstimo do veículo.

Em nosso projeto, vamos começar desde o início, realizando a leitura da base de dados, criando um modelo de classificação e focando principalmente na etapa de validação de modelos.

O que faremos no projeto?

Leitura da base de dados

Criação de modelo de classificação

Validação de modelos

Como podemos saber se o nosso modelo está realmente aprendendo com os dados?

Vamos utilizar estratégias de divisão dos dados, como treino, validação e teste, e a validação cruzada. Além disso, vamos nos concentrar na etapa de avaliação dos modelos. Vamos conhecer as principais métricas para entender se o nosso modelo está indo bem ou quão bem ele está se saindo. Aprenderemos a utilizar a Acurácia, o o Recall, a Precisão e a matriz de confusão.

Por fim, vamos explorar formas de aprimorar o desempenho do nosso modelo e selecionar aquele que teve o melhor desempenho.
