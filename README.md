# DashboardProducao:zap:

### Dashboard de Produção em Power BI

O Dashboard abaixo refere-se a uma base de Produção. Contendo informações sobre a quantidade Produzida, Rejeitada, Horas Produtivas, Horas Paradas, Quantidade de Produção por Ano e Mês, Disponibilidade (percentual de horas produtivas) e Qualidade (percentual de produção sem rejeição).

No primeiro momento foi necessário realizar algumas alterações no Power Query, sendo essas o tipo de cada coluna, limpeza de dados desnecessários, desmembramento da base para criação de tabelas de dimensão afim de diminuir a quantidade de dados/informações repetitivas e melhorar o desempenho do Dashboard. Automaticamente, com o desmembramento da base foi necessário realizar o gerenciamento das relações entre a tabela fato e suas dimensões:

<img width="425" alt="Relacionamentos" src="https://user-images.githubusercontent.com/98985401/224125016-2c114133-8d5d-491a-9e93-da1b715b9f76.png">

Em seguida, foram criadas as medidas para cálculo da quantidade de Produção, Rejeição, Horas, Disponibilidade e Qualidade:

<img width="130" alt="Medidas" src="https://user-images.githubusercontent.com/98985401/224126473-17c0e75f-9050-47fc-b09f-2ea7ccc82969.png">

No layout, foi usado Cartões para apresentar a Quantidade Produzida, Rejeitada, Horas Produtivas e Paradas. Filtros para cada Operador e Mês. Gráfico de Área com a quantidade de produção por mês e ano. Indicador contendo a Disponibilidade que é o percentual de Horas Produtivas e a Qualidade que é o percentual da quantidade Produzida:

<img width="425" alt="Dashboard" src="https://user-images.githubusercontent.com/98985401/224126719-45051ce5-5145-4c56-aaaf-5390b2340689.png">

Diante das informações apresentadas podemos gerar os seguintes Insights:

  :heavy_check_mark: Temos 77,69% de Disponibilidade de Horas com produção eficiente;

  :heavy_check_mark: Temos 99,32% de Qualidade na produção dos produtos;

  :heavy_check_mark: Os meses de Setembro e Outubro tiveram menor quantidade de produção. 

Esses Insights são de grande valia, pois por meio deles podemos nos aprofundar nas informações identificando pontos que precisam de atenção, como por exemplo:

  :heavy_check_mark: O motivo de determinado funcionário produzir abaixo da média;
  
  :heavy_check_mark: Elaborar um estudo de caso e plano de meta sobre a causa raiz das horas paradas e produções rejeitadas, afim de melhorar o desempenho produtivo.
