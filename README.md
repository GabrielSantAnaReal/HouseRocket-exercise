# HouseRocket-exercise

🇧🇷🇵🇹 Usando o caso fictício da HouseRocket para exercitar minhas habilidades em Ciência &amp; Análise de Dados.
Esse repositório usa como base dados disponíveis publicamente em:
-> https://youtu.be/VlYDWOfiFuc
-> https://www.kaggle.com/code/lucascapovilla/house-rocket

🇬🇧🇺🇸 Using the HouseRocket fictitious case to exercise my Data Science &amp; Analysis skills.
This repository uses data available publicly in:
-> https://youtu.be/VlYDWOfiFuc
-> https://www.kaggle.com/code/lucascapovilla/house-rocket


========================================================================================


🇧🇷🇵🇹
Atriubutos e definições:
|    Atributos    |                         Significado                          |
| :-------------: | :----------------------------------------------------------: |
|       id        |       Numeração única de identificação de cada imóvel        |
|      date       |                    Data da venda da casa                     |
|      price      |    Preço que a casa está sendo vendida pelo proprietário     |
|    bedrooms     |                      Número de quartos                       |
|    bathrooms    | Número de banheiros (0.5 = banheiro em um quarto, mas sem chuveiro) |
|   sqft_living   | Medida (em pés quadrado) do espaço interior dos apartamentos |
|    sqft_lot     |     Medida (em pés quadrado)quadrada do espaço terrestre     |
|     floors      |                 Número de andares do imóvel                  |
|   waterfront    | Variável que indica a presença ou não de vista para água (0 = não e 1 = sim) |
|      view       | Um índice de 0 a 4 que indica a qualidade da vista da propriedade. Varia de 0 a 4, onde: 0 = baixa  4 = alta |
|    condition    | Um índice de 1 a 5 que indica a condição da casa. Varia de 1 a 5, onde: 1 = baixo \|-\| 5 = alta |
|      grade      | Um índice de 1 a 13 que indica a construção e o design do edifício. Varia de 1 a 13, onde: 1-3 = baixo, 7 = médio e 11-13 = alta |
|  sqft_basement  | A metragem quadrada do espaço habitacional interior acima do nível do solo |
|    yr_built     |               Ano de construção de cada imóvel               |
|  yr_renovated   |                Ano de reforma de cada imóvel                 |
|     zipcode     |                         CEP da casa                          |
|       lat       |                           Latitude                           |
|      long       |                          Longitude                           |
| sqft_livining15 | Medida (em pés quadrado) do espaço interno de habitação para os 15 vizinhos mais próximo |
|   sqft_lot15    | Medida (em pés quadrado) dos lotes de terra dos 15 vizinhos mais próximo |


Perguntas a serem respondidas:
1) Quantas casas tem 1 quarto?
2) Quantas casas de mais de um andar?
3) Quantas casas estão em boas ou más condições?
4) Quantos quartos, em média, as casas possuem?
5) Qual o preço médio das casas?
6) Qual o desvio padrão dos preços?
7) Existem casas com preços outliers? (apresentar id e zipcode)
8) Quais são os 1Q e 3Q dos preços?
9) Quais as dez casas mais antigas a venda e seus respectivos anos de construção? (apresentar id e zipcode)
10) Qual o valor médio das 10 casas mais novas à venda?
11) Qual o valor médio das 10 casas mais antigas à venda?
12) Qual as 10 casas com as melhores vistas? (apresentar id e zipcode)


========================================================================================


🇬🇧🇺🇸
Attributes and defintions:
|    Atributos    |                         Definition                          |
| :-------------: | :----------------------------------------------------------: |
|       id        |                 Unique ID for each home sold                 |
|      date       |                    Date of the home sale                     |
|      price      |                   Price of each home sold                    |
|    bedrooms     |                     Number of bedrooms                       |
|    bathrooms    |   Number of bathrooms (where .5 accounts for a room with a toilet but no shower) |
|   sqft_living   |     Square footage of the apartments interior living space   |
|    sqft_lot     |                 Square footage of the land space             |
|     floors      |                        Number of floors                      |
|   waterfront    |  A dummy variable for whether the apartment was overlooking the waterfront or not (0 = não e 1 = sim) |
|      view       | An index from 0 to 4 of how good the view of the property was, where: 0 = bad  4 = good |
|    condition    |  An index from 1 to 5 on the condition, where: 1 = bad \|-\| 5 = good |
|      grade      | An index from 1 to 13, where 1-3 falls short of building construction and design, where: 1-3 = low, 7 = medium e 11-13 = high |
|  sqft_basement  | The square footage of the interior housing space that is below ground level |
|    yr_built     |          The year the house was initially built             |
|  yr_renovated   |          The year of the house’s last renovation            |
|     zipcode     |            What zipcode area the house is in                |
|       lat       |                          Lattitude                          |
|      long       |                          Longitude                          |
| sqft_livining15 | The square footage of interior housing living space for the nearest 15 neighbors |
|   sqft_lot15    | The square footage of the land lots of the nearest 15 neighbors |


Questions to be answered:
1) How many houses has 1 bedroom?
2) How many houses has more than one floor?
3) How many houses are in good or bad condition?
4) How many rooms, on average, do the houses have?
5) What is the average price of houses?
6) What is the standard deviation of prices?
7) Are there houses with outliers prices? (show id and zipcode)
8) What are the 1Q and 3Q prices?
9) What are the ten oldest houses for sale and their respective years of construction? (show id and zipcode)
10) What is the average value of the 10 newest houses for sale?
11) What is the average value of the 10 oldest houses for sale?
12) What are the 10 houses with the best views? (show and zipcode)

