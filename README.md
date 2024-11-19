#Gustavo Aragão Guedes RA:10376534
#Gustavo Fernandes Costa RA:10390377
#Julia Rampani RA:10395600

Este script coleta artigos da Wikipedia por categorias, pré-processa o texto e treina um modelo de aprendizado para classificar os artigos em suas respectivas categorias.

Requisitos:
Python 3.10 ou superior (versões anteriores podem não funcionar)
pip 24.1.2

Bibliotecas:
-requests
-pandas
-numpy
-tensorflow
-scikit-learn
-matplotlib
-seaborn

Mude a url da wikipedia conforme a necessidade, por padrão, "https://en.wikipedia.org/w/api.php"

recomendamos rodar no ambiente jupyter ou google colab

No código, edite a lista "categories" para incluir as categorias de interesse. Por padrão, as categorias são:
categories = ["Science", "History", "Technology", "Art", "Sports", "Literature", "Movies", "Music"]

Após isso, é só executar que irá aparecer a quantidade de artigos por categoria selecionada sendo positivos e negativos.

Logo abaixo irá aparecer somente os verdadeiros.

Será apresentado 2 gráficos, um contendo os acertos e o outro contendo os erros.

Após isso será mostrado uma matriz de confusão com os dados.
