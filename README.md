# csv2htm
Csv2htm converte um arquivo de formato csv para outro de formato htm. Basta rodar o programa com os argumentos usando a sintaxe mostrada no parágrafo "Sinatxe do executável".
Csv2htm foi desenvolvido usando Python. Para que o aplicativo se tornasse um programa executável para rodar no sistema operacional Windows, foi necessário converter o código fonte (.py) em arquivo exe usando o "auto-py-to-exe" (https://pypi.org/project/auto-py-to-exe).
Para rodar o programa usando apenas o arquivo com o código fonte (csv2htm.py), é necessário, além de ter o Python instalado, instalar a biblioteca Pandas (https://pandas.pydata.org/). O arquivo "csv2htm.py" possui apenas 2 Kb, entretando quando compilado para o executável do Windows, ele ultrapassa os 34 Mb de tamanho, pois durante o processo de compilação, é compilada também a biblioteca do Pandas e suas dependências juntamente com a biblioteca sys nativa do Python.

Sintaxe do executável:

~~~
csv2htm.exe [--help] [csv_file] [html_file]

--help: mostra na tela essa ajuda.
csv_file: caminho onde esta o arquivo com extensao csv.
htm_file: caminho onde o arquivo htm gerado sera salvo.
Exemplo:
csv2htm.exe c:/temp/arquivo.csv c:/saida/htm_file.htm
~~~
