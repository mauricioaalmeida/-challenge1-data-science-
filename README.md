<h1> CHALLENGE: ONE Data Science - Alura Store | Trello </h1>

<p align="left">
  <img src="https://img.shields.io/static/v1?label=&message=Python&color=blue&style=for-the-badge&logo=python"/>
  <img src="https://img.shields.io/static/v1?label=&message=Pandas&color=blue&style=for-the-badge&logo=pandas"/>
  <img src="https://img.shields.io/static/v1?label=&message=matplotlib&color=blue&style=for-the-badge&logo=matplotlib"/>
  <img src="https://img.shields.io/static/v1?label=&message=folium&color=blue&style=for-the-badge&logo=folium"/>
  <img src="https://img.shields.io/static/v1?label=&message=Colab&color=blue&style=for-the-badge&logo=googlecolab"/>
  <img src="http://img.shields.io/static/v1?label=STATUS&message=CONCLUIDO&color=GREEN&style=for-the-badge"/>
</p>

<h2>Resumo do projeto</h2>

<p>Projeto realizado para atender o Challenge do curso ONE Data Science G8</p>
<p>Realizado na Alura, visando o desenvolvimento das habilidades em análise de dados com Python.</p>

<h2>❔ Objetivo</h2>
O objetivo desse projeto é analisar os dados disponíveis das 4 lojas fictícias do Sr. João, para auxiliar na decisão sobre qual loja vender para levantar fundos para investir em um novo negócio.
<p></p>
<p></p>

<h2>📸 Alguns gráficos disponíbilizados na análise:</h2>

- Faturamento trimestral por loja:<p></p>
![Faturamento trimestral por loja](Assets/Faturamento_Loja_trimestre.jpg)

- Mapa de Vendas por localidade:<p></p>
![Heat-map](Assets/Heat-Map.jpg)

- Vendas por categoria de produto:<p></p>
![Gráfico de Vendas por Categoria](Assets/Qtd_Fat_Categoria.jpg)

<p></p>

<h2>🔨 ## Metodologia</h2>

Os dados foram disponibilizados em 4 arquivos CSV, correspondentes à cada loja, com os seguintes campos:
- Produto 	
- Categoria do Produto 
- Preço 
- Frete 
-	Data da Compra 
- Vendedor 
-	Local da compra 
-	Avaliação da compra 
-	Tipo de pagamento 
-	Quantidade de parcelas 
-	lat 
-	lon

Carreguei cada arquivo em um dataset Pandas separado e verifiquei a existência dos mesmos campos e tipos de dados. Como os dados estavam consistêntes, criei uma coluna adicional 'Loja' em cada dataset e uni os quatro em um único dataset chamado 'Lojas'.
Criei series de dados agrupando os dados pelos campos a serem analisados, somando ou contando os valores e preparando gráficos com MatPlotLib.
Criei um mapa interativo com Folium utilizando as informações geográficas disponíveis.
<p></p>
<p></p>
<h2>✔️ Técnicas e tecnologias utilizadas</h2>

   - Para realizar a análise, foi utilizado o ambiente do Google Colab, com a linguagem Python e as bibliotecas Pandas, Matplotlib, Folium entre outras. 
<p></p>
<p></p>
<h2>📁 Acesso ao projeto</h2>

   - Você pode acessar o projeto no Colab clicando [aqui](https://colab.research.google.com/drive/1RY37fQDHHL0mn87SUq85KhkbBPaNdmaa?usp=sharing)

<p></p>

<h2> Autor </h2>

[<img loading="lazy" src="https://avatars.githubusercontent.com/u/195226841?v=4" width=115><br><sub> Mauricio Andre de Almeida</sub>](https://github.com/mauricioaalmeida) 
