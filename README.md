# Desafio de ciência de dados do processo seletivo da empresa indicium
## Análise exploratória de dados e regressão - Precificação de anúncios de quartos em NYC

### Descrição do projeto

Desafio de ciência de dados para o processo seletivo da empresa Indicium. O desafio é relativo à análise exploratória de dados e regressão de um dataset de precificação de anúncios de quarto em NYC. Ele foi baseado em 5 perguntas a responder, mostradas a seguir, dadas ao candidato com relação ao dataset fornecido.

1. Faça uma análise exploratória dos dados (EDA), demonstrando as principais características entre as variáveis e apresentando algumas hipóteses de negócio relacionadas. Seja criativo!

2. Responda também às seguintes perguntas:
    a. Supondo que uma pessoa esteja pensando em investir em um apartamento para alugar na plataforma, onde seria mais indicada a compra?
    b. O número mínimo de noites e a disponibilidade ao longo do ano interferem no preço?
    c. Existe algum padrão no texto do nome do local para lugares de mais alto valor?

3. Explique como você faria a previsão do preço a partir dos dados. Quais variáveis e/ou suas transformações você utilizou e por quê? Qual tipo de problema estamos resolvendo (regressão, classificação)? Qual modelo melhor se aproxima dos dados e quais seus prós e contras? Qual medida de performance do modelo foi escolhida e por quê?

4. Supondo um apartamento com as seguintes características:

<code>
{'id': 2595,
 'nome': 'Skylit Midtown Castle',
 'host_id': 2845,
 'host_name': 'Jennifer',
 'bairro_group': 'Manhattan',
 'bairro': 'Midtown',
 'latitude': 40.75362,
 'longitude': -73.98377,
 'room_type': 'Entire home/apt',
 'price': 225,
 'minimo_noites': 1,
 'numero_de_reviews': 45,
 'ultima_review': '2019-05-21',
 'reviews_por_mes': 0.38,
 'calculado_host_listings_count': 2,
 'disponibilidade_365': 355}
</code>

    Qual seria a sua sugestão de preço?

5. Salve o modelo desenvolvido no formato .pkl

### Como instalar e rodar o projeto

Para utilizar o projeto, as seguintes bibliotecas de Python devem estar disponíveis no seu ambiente de desenvolvimento:

* pandas
* numpy
* matplotlib
* seaborn
* collections
* wordcloud
* sklearn

### Como utilizar o projeto

Para utilizar o projeto, basta executá-lo em um ambiente de desenvolvimento de Jupyter Notebook que já contenha as bibliotecas mencionadas instaladas.