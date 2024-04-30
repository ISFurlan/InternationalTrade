#Dashboard disponível em português e inglês

#Dashboard available in Portuguese and English

Português | Portuguese:

O arquivo fonte utilizado foi baixado por meio do link: https://www.kaggle.com/datasets/nayanack/shipping?resource=download

Alguns pontos principais sobre o projeto:

1 — O tratamento dos dados .csv foi realizado utilizando o Power Query do Excel. Você pode acessar a planilha com os dados tratados ao reexibir a aba oculta na pasta de trabalho.

2 — Procurei responder às seguintes perguntas de negócio:

	2.1 —  Dos três modais de transporte disponíveis, quais são os mais eficientes, considerando a razão da quantidade de entregas no prazo dividida pela quantidade total de entregas;
 
			2.1.1 — Dentro deste tópico, é possível subdividir por galpões, classificados de “A” a “F”, para determinar os mais eficientes em termos de entrega.
	
	Para responder a essa questão, criei uma Tabela Dinâmica e adicionei Segmentação de Dados para facilitar o filtro e tornar a leitura dos dados mais interativa.
	Também criei uma medida personalizada no Power Pivot para calcular a eficiência de entrega de cada modal de transporte.
	
	2.2 — Em relação aos clientes, adicionei uma Segmentação de Dados relacionada ao gênero. Isso permite entender como as avaliações de serviço estão relacionadas ao gênero dos clientes. Também incluí um quadro demonstrando o total de chamadas.
	
	2.3 — Ainda no contexto das entregas, separei os produtos por importância para determinar se a eficiência de entrega varia de acordo com a importância do produto.
	
	2.4 — Muitas vezes é necessário correlacionar o peso do produto com o custo para determinar se o aumento do peso resulta em um aumento do custo. Utilizei um gráfico de dispersão para representar visualmente essa relação de forma didática.

	2.5 — Por fim, em relação à precificação dos produtos, utilizei um histograma para identificar os intervalos de preços com maior quantidade de produtos.
	
Inglês | English:

The source .csv file was downloaded from the following link: https://www.kaggle.com/datasets/nayanack/shipping?resource=download

1 — Data preprocessing for the .csv file was performed using Power Query in Excel. The workbook containing the preprocessed data can be accessed by unhiding the hidden sheet in the workbook.

2 — The project aims to answer the following business questions:

	2.1 — Which of the three available transportation modes are the most efficient, considering the ratio of on-time deliveries to total deliveries?
 
		2.1.1 — Within this topic, it is possible to break down by warehouses, classified from “A” to “F”, to determine the most efficient in terms of delivery.
	
	 To answer this question, a PivotTable was created and Data Slicers were added to facilitate filtering and make data reading more interactive. A custom measure was also created in Power Pivot to calculate the delivery efficiency of each transportation mode.
	 
	2.2 — For customers, a Data Slicer related to gender was added. This allows understanding how service ratings are related to customer gender. A chart showing the total number of calls was also included.
	
	2.3 — Still in the context of deliveries, the products were separated by importance to determine if the delivery efficiency varies according to the importance of the product.
	
	2.4 — It is often necessary to correlate the weight of the product with the cost to determine if an increase in weight results in an increase in cost. A scatter plot was used to visually represent this relationship in a instructive way.
	
	2.5 — Finally, regarding product pricing, a histogram was used to identify the price ranges with the highest number of products.
