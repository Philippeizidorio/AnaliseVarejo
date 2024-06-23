# Analisando E Criando Métricas Usando Python - Loja Varejista 📊🔍
![Alt ou título da imagem](https://github.com/Philippeizidorio/AnaliseVarejo/assets/145637595/694d2fe6-fa44-466d-83c5-7e750994a170)

### ◾Contexto:

O dataset que temos em mãos é composto por informações de vendas de uma loja varejista que atua em todo território nacional, vendendo produtos de diferentes departamentos bem como possui diferentes canais de venda, como marketplace, loja própria, entre outros. A gestão do negócio está precisando acompanhar os resultados para traçar melhores estratégias e tomar decisões bem informadas juntamente a outros times de negócio, para isso, realizaremos análises e criaremos métricas utilizando a linguagem Python em conjunto com algumas bibliotecas que serão cruciais para essa finalidade. 

### ◾Premissas do negócio:

A primeira delas é que, devido a um erro no sistema, algumas compras não possuem informações de UF(Unidade Federativa). Para solucionar esse problema, foi decidido que essas compras serão consideradas como pertencentes ao estado de Mato Grosso do Sul(MS). A segunda premissa é que o preço final de um produto não pode ser maior do que a preco com frete.

### ◾Métricas:

Com base nesse contexto e nas premissas de negócio estabelecidas, podemos avaliar as seguintes métricas ↓

**1.Departamentos mais vendidos:** Analisando os dados de vendas, podemos identificar quais são os departamentos mais populares entre os clientes. Essa informação pode ser útil para entender quais são os produtos mais procurados pelos clientes e ajustar a estratégia de venda da loja em conformidade.

![Qtd. De Vendas Por DPT.](https://github.com/Philippeizidorio/AnaliseVarejo/blob/main/Qtd.%20vendas%20por%20departamento.png)

**2.Média de preço com frete por departamento:** Para entender o comportamento de preço por departamento, podemos calcular a média de preço com frete por nome de departamento. Essa métrica pode ajudar a identificar quais são os departamentos mais rentáveis e ajustar a precificação de produtos de acordo com a margem de lucro desejada.

![Qtd. De Vendas Por DPT.](https://github.com/Philippeizidorio/AnaliseVarejo/blob/main/M%C3%A9dia%20de%20pre%C3%A7o%20com%20frete%20por%20DPT.png)

