# 📊 Análise de Vendas BikeStore

Utilizando o banco de dados BikeStores, que simula um ambiente varejista com múltiplas lojas de bicicletas, iniciei uma análise para entender o desempenho comercial das unidades ao longo do tempo. O objetivo foi avaliar indicadores estratégicos como faturamento, número de vendas, ticket médio e média de produtos por pedido, além de investigar variações sazonais relevantes.
<br><br>

## 🔍 Análise Exploratória de Dados
<img align="right" width="500"  src="https://github.com/Pedrax00/Portfolio-BikeStore/blob/main/Imagens/P%C3%A1gina%202%20-%20Lojas.png?raw=true">
A primeira etapa consistiu em explorar a estrutura do banco de dados, entendendo tabelas, campos, tipos de dados e relacionamentos. A partir disso, foram desenvolvidas consultas SQL para extrair os principais indicadores e padrões iniciais: <br><br>
• 	Faturamento total por loja e por mês <br>
• 	Evolução mensal das vendas <br>
• 	Ticket médio por unidade <br>
• 	Média de produtos por pedido <br>
• 	Identificação de variações atípicas entre janeiro e fevereiro <br>
Essa análise permitiu levantar hipóteses sobre o comportamento das lojas e entender como fatores regionais podem influenciar os resultados
<br><br>

## 🗂️ Modelo e Fonte de Dados
<img align="left" width="500"  src="https://github.com/Pedrax00/Portfolio-BikeStore/blob/main/Imagens/Esquema%20Estrela.png?raw=true">
O projeto utilizou o banco de dados BikeStores, que já contém todas as informações necessárias para análise (clientes, pedidos, produtos e lojas). <br>
A modelagem foi estruturada em formato Star Schema, garantindo integridade e clareza nas análises. <br>
Essa abordagem evitou a necessidade de importar dados de fontes externas e permitiu criar métricas consistentes para o dashboard no Power BI.
<br>

<br><br>


<br><br>
## 📈 Investigação de Outliers
<img align="right" width="500" height="320" src="https://github.com/Pedrax00/Portfolio-BikeStore/blob/main/Imagens/P%C3%A1gina%203%20-%20An%C3%A1lise%20de%20Varia%C3%A7%C3%A3o.png?raw=true">
Durante a análise, foi identificada uma variação atípica no faturamento entre os meses de janeiro e fevereiro. <br>
Esse comportamento destoou do padrão observado ao longo do ano e levantou hipóteses sobre fatores sazonais e regionais que podem ter influenciado os resultados. <br>
A investigação desse outlier reforça a importância de não apenas acompanhar indicadores gerais, mas também analisar anomalias que podem revelar oportunidades ou riscos para o negócio. <br>

<br>


<br>

## ✅ Resultados e Benefícios
• 	Identificação das diferenças de escala entre as lojas (NY, CA, TX). <br>
• 	Conclusão de que o faturamento varia mais pelo volume de vendas do que pelo ticket médio. <br>
• 	Investigação de outliers: variação atípica entre janeiro e fevereiro, levantando hipóteses sobre fatores sazonais e regionais. <br>
• 	Dashboard interativo que apoia decisões estratégicas e permite explorar variações de forma dinâmica. <br>
• 	Modelo em Star Schema que garante consistência e clareza nas análises.

<br>



<a href="https://app.powerbi.com/view?r=eyJrIjoiZWQ2YjIzOWYtODEzOS00YTE5LWFkODMtY2U5NmRhYzFmMWIyIiwidCI6IjY1OWNlMmI4LTA3MTQtNDE5OC04YzM4LWRjOWI2MGFhYmI1NyJ9">Clique aqui</a> e veja o dashboard interativo no Power BI.

## Ferramentas e linguagens utilizadas
<div style="display: inline_block">
    <img align="center" alt="SQL" height="40" width="40" src="https://github.com/BruceFonseca2/Portfolio/blob/main/linguagens/sql.png?raw=true">
    <img align="center" alt="Power BI" height="40" width="40" src="https://github.com/BruceFonseca2/Portfolio/blob/main/linguagens/power%20bi.png?raw=true">
</div>
