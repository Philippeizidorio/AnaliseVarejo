# Analisando Resultados e Criando Métricas Usando Python 📊🔍
![Alt ou título da imagem](https://github.com/Philippeizidorio/AnaliseVarejo/assets/145637595/694d2fe6-fa44-466d-83c5-7e750994a170)

### ◾Contexto:

O dataset que temos em mãos é composto por informações de vendas de uma loja varejista que atua em todo território nacional, vendendo produtos de diferentes departamentos bem como possui diferentes canais de venda, como marketplace, loja própria, entre outros. A gestão do negócio está precisando acompanhar os resultados para traçar melhores estratégias e tomar decisões bem informadas juntamente a outros times da empresa, para isso, realizaremos análises e criaremos métricas utilizando a linguagem Python em conjunto com algumas bibliotecas que serão cruciais para essa finalidade. 

### ◾Premissas de negócio:

A primeira delas é que, devido a um erro no sistema, algumas compras não possuem informações de UF(Unidade Federativa). Para solucionar esse problema, foi decidido que essas compras serão consideradas como pertencentes ao estado de Mato Grosso do Sul(MS). A segunda premissa é que o preço final de um produto não pode ser maior do que a preço com frete, sendo necessário aplicar uma filtragem no dataset para que fiquem apenas aqueles que contemplem essa condição.   

### ◾Métricas:

Com base nesse contexto e nas premissas de negócio estabelecidas, podemos avaliar as seguintes métricas ↓

**1.Departamentos mais vendidos:** Analisando os dados de vendas, podemos identificar quais são os departamentos mais populares entre os clientes. Essa informação pode ser útil para entender quais são os produtos mais procurados pelos clientes e ajustar a estratégia de venda da loja em conformidade.

<p align="center">
  <img src="https://github.com/Philippeizidorio/AnaliseVarejo/blob/main/Qtd.%20vendas%20por%20departamento.png" alt="Departamento mais vendidos">
</p>

**2.Média de preço com frete por departamento:** Para entender o comportamento de preço por departamento, podemos calcular a média de preço com frete por nome de departamento. Essa métrica pode ajudar a identificar quais são os departamentos mais rentáveis e ajustar a precificação de produtos de acordo com a margem de lucro desejada.

<p align="center">
  <img src="https://github.com/Philippeizidorio/AnaliseVarejo/blob/main/M%C3%A9dia%20de%20pre%C3%A7o%20com%20frete%20por%20DPT.png" alt="Média de preço com frete por departamento">
</p>

**3.Quantidade de vendas na data:** Analisando a quantidade de vendas realizadas ao longo do tempo, podemos identificar sazonalidades no comportamento de compra dos clientes e planejar campanhas de marketing especificas para cada período.

<p align="center">
  <img src="https://github.com/Philippeizidorio/AnaliseVarejo/blob/main/Quantidade%20de%20vendas%20na%20Data.png" alt="Quantidade de vendas na data">
</p>

**4.Média de renda por canal de venda:** identificar a média de renda dos clientes em diferentes canais de venda pode ajudar a loja a adaptar a estratégia de marketing e vendas para cada público-alvo.

<p align="center">
  <img src="https://github.com/Philippeizidorio/AnaliseVarejo/blob/main/m%C3%A9dia%20de%20renda%20por%20canal.png" alt="Média de renda por canal de venda">
</p>

**5.Média de idade dos clientes por bandeira:** Saber a faixa etária dos clientes por bandeira pode ajudar a identificar perfis de consumidores e ajustar a estratégia de venda para atender melhor cada público.

<p align="center">
  <img src="https://github.com/Philippeizidorio/AnaliseVarejo/blob/main/m%C3%A9dia%20de%20idade%20por%20bandeira.png" alt="Média de idade por bandeira">
</p>

### ◾ Através das análises, podemos concluir que no período: 
1. O Top 3 departamentos com maior quantidade de vendas foram respectivamente: Telefones e Celulares, Eletrodomésticos e Eletroportáteis;
3. O departamento que apresentou maior média de preço com frete foi o de TVs e Acessórios;
4. O mês que apresentou a maior quantidade de vendas foi Março, sendo os departamentos com maior quantidade em vendas respectivamente: Produtos para Bebês e Eletrodomésticos;
5. A média de renda em todos os canais de venda não foi menor que R$8.200,00;
6. A média de idade foi de 53 anos para ambas bandeiras do grupo.

### ◾ Tecnologias Utilizadas: 
<div <br> 
<img src="https://img.shields.io/badge/Python-4695dd?style=for-the-badge&logo=python&logoColor=FFD43B">
<img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white">
<img src="https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white">
<img src="https://img.shields.io/badge/Matplotlib-%232A9D8F.svg?style=for-the-badge&logo=Matplotlib&logoColor=black"
</div> 

## Autor:

<img  src="https://github.com/Philippeizidorio/AnaliseTRIM_AgenciaMKTDIGITAL/assets/145637595/9800ac43-2070-48d4-9002-dbf82f756f2c" width="80" alt="cognitiveclass.ai logo" align="left" /> 

### &nbsp;&nbsp;Philippe Izidório

<p>
&nbsp;&nbsp;Estudante De Ciência De Dados / Business Intelligence / Analista De Dados<br/>
&nbsp;&nbsp;LinkedIn: https://www.linkedin.com/in/philippeizidorio/<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;E-mail: euphilippeizidorio@gmail.com<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Portifólio de projetos em Data Science: https://github.com/Philippeizidorio
</p>
