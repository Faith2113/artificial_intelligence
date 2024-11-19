<p> </p>Gustavo Aragão Guedes RA:10376534 <br>
<p> </p>Gustavo Fernandes Costa RA:10390377 <br>
<p> </p>Júlia Rampani RA:10395600 <br>

<p> </p>Este script coleta artigos da Wikipedia por categorias, pré-processa o texto e treina um modelo de aprendizado para classificar os artigos em suas respectivas categorias. <br>

<p> Requisitos: <br>
Python 3.10 ou superior (versões anteriores podem não funcionar)
pip 24.1.2 </p>

<p>Bibliotecas: <br>
-requests
-pandas
-numpy
-tensorflow
-scikit-learn
-matplotlib
-seaborn </p>

<p> </p>Mude a url da wikipedia conforme a necessidade, por padrão, "https://en.wikipedia.org/w/api.php" <br>

<p> </p>Recomendamos rodar no ambiente jupyter ou google colab <br>

<p>No código, edite a lista "categories" para incluir as categorias de interesse. Por padrão, as categorias são: <br>
categories = ["Science", "History", "Technology", "Art", "Sports", "Literature", "Movies", "Music"] </p>

<p> </p>Após isso, é só executar que irá aparecer a quantidade de artigos por categoria selecionada sendo positivos e negativos. <br>

<p> </p>Logo abaixo irá aparecer somente os verdadeiros. <br>

<p> </p>Será apresentado 2 gráficos, um contendo os acertos e o outro contendo os erros. <br>

<p> </p>Após isso será mostrado uma matriz de confusão com os dados. <br>
