# Web Scraping e base de dados MySql utilizando o Python

Nesse projeto, as bibliotecas Requests e BeautifulSoup do Python são utilizadas para coletar informações dos livros mais vendidos no site das Livrarias Cultura. Um DataFrame é então criado contendo os títulos, categorias, autores e preços dos livros.

Em seguida, uma base de dados MySql é criada com as informações coletadas. Nessa etapa, o driver MySql Connector do Python é utilizado para conectar na base de dados. 

A base criada é composta por 3 tabelas: livros_preços, autores e categorias. Os relacionamentos são definidos de tal maneira que a tabela de títulos e preços faz referência às tabelas de autores e categorias.

![mysql](https://github.com/gandreguetto/web-scraping-mysql/assets/88217999/b85744ec-c6e1-4d45-97b5-6a51b3b0bbd8)

Apesar de bastante simples, esse projeto é um excelente exercício de duas tarefas importantes quando se trabalha com dados: a coleta de dados na web e criação de bancos sql. 
