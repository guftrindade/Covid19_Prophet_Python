# Covid19_Prophet_Python
Utilizando a biblioteca Prophet para predição de dados da Covid-19

# Conforme visto no próprio site oficial em: https://facebook.github.io/prophet/
"Prophet é um procedimento para prever dados de série temporal com base em um modelo aditivo em que tendências não lineares são ajustadas com sazonalidade anual, semanal e diária, além de efeitos de feriados. Funciona melhor com séries temporais que têm fortes efeitos sazonais e várias temporadas de dados históricos. 

# Realizei este projeto hoje 06/05/2021 e conforme os resultados encontrados, foi previsto os seguintes números de mortes:
Colunas:
*ds* = Data, *yhat_lower* = Previsão mínima, *yhat* = Previsão efetiva, *yhat_upper* = previsão máxima


![image](https://user-images.githubusercontent.com/67704261/117239389-0e204f00-ae05-11eb-969c-2ddf6a7d75b2.png)


## Até o momento, não estou conseguindo visualizar os números inteiros, portanto, entendi que:
## Por exemplo na linha 495 -> 2021-05-31 o resultado seria 3,882007 X 10 ^ 6 = 3.882.007 (3.88 milhões)
## Sendo assim um resultado bem arpoximado de realidade atual

# De forma gráfica, estou melhorando ainda a visualização, mas por enquanto temos este:

![image](https://user-images.githubusercontent.com/67704261/117239928-1927af00-ae06-11eb-83c8-f2c3f1aeea99.png)

## Fonte de dados: https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset
