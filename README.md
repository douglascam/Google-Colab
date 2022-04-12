# Google-Colab
## processo-seletivo-myra
# Introdução
Notebook criado para o processo seletivo da empresa Myra

### Problema proposto:
Desenvolvimento de uma análise coerente do feedback de clientes sobre determinados produtos e um estudo das categorias mais lucrativas destes produtos.

### Solução:
* Foi implementado a criação de dataframes utilizando pyspark. Depois, ao consolidar todos os Datafrmaes em um unico cruzando seus id's, foi gerado uma coluna com um nivel mais abstrato de criticas recebidas dos clientes,buscando palavras-chaves relacionadas com a positividade dos feedbacks.
* para entender quais as categorias mais lucrativas de produtos, foi soamdo o valor individual de cada compra e separado por categoria de produto, retornando o top 6
###  Visualização
   Para a visualização dos resultados, os dataframes pyspark para dataframes pandas, de modo a permitir melhor controle de plotagem dos gráficos
# Ponto de consideração
   Com o retorno baixo das palavras chaves propostas, foi adicionado algumas outras opçoes de palavras chaves para melhor amostragem e criação dos gráficos.
