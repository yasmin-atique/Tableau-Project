# Tableau-Project
Esse projeto teve como objetivo exercitar habilidades em extração, mineração e apresentação de dados para análise de dados.
# Objetivos específicos
- Avaliar relação entre pluviometria na cidade de São Paulo e o destamameno da Amazônia;
- Avaliar relação entre pluviometria na cidade de São Paulo e os fenômenos La niña e El niño.
# Fontes de dados
- Pluviometria: INMET
- Desmatamento da Amazônia: INPE
- La niña e El niño: National Weather Service
https://origin.cpc.ncep.noaa.gov/products/analysis_monitoring/ensostuff/ONI_v5.php
# Tecnologias
- Python 3.9.7
- Tableau public
- SQL
# Bibliotecas python
- requests
- BeautifulSoup
- pandas
- os
- glob
- sqlalchemy
- load_dotenv
# Resultados
Os resultados não foram conclusivos.
Através da figura 1 é possível observar que os anos com maior área destamada são 1988, 1995 e 2004. Em 2004 iniciou-se queda do desmatamento até atingir seu pico
mais baixo em 2012, a partir do qual iniciou-se tendência de incremento.

### Figura 1 - Área desmatada da Amazônia por ano
![Story 1](https://user-images.githubusercontent.com/101889306/189498343-24ce7d6b-6e24-4c1e-94c8-69dfef646bbd.png)

A Figura 2 apresenta os dados pluviométricos extraidos do INMET, entretanto os mesmos começaram a ser gerados em  2006, portanto, não foi possível avaliar a relação
dos das variáveis nos anos em que houve maior área desmatada (1988, 1995 e 2004).
É possível observar que no ano em que houve maior desmatamento do período avaliado (2006) também foi o ano com menor índice pluviométrico acumulado.
Entretanto, não é possível observar tendência relativa a área destamada acumulada ou com os fenômenos de La niña e El niño.

### Figura 2 - Desmatamento (km²), pluviometria acumulada (mm) e fenômenos La niña e El niño.
![Story 1 (1)](https://user-images.githubusercontent.com/101889306/189498811-9841f04c-0d1b-442b-bb62-e72f56ae165b.png)

# Próximos passos
- Avaliar dados pluviométricos do Estado de São Paulo inteiro, com objetivo e diminuir a influência climática local nos dados;
- Avaliar se a mata desmatada que voltou a crescer e qual a influencia dela no montante de água bombeada para a atmosfera;
- Incluir demais interferêntes na pluviometria do Estado de São Paulo na análise.

# Link Tableau
https://public.tableau.com/views/Project2-Final_16628235383790/Story1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

