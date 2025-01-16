# sales
Dashboard de Vendas

## Descrição
Fiz esse relatório no Power BI para treinar.
A base de dados foi baixado no Kaggle. Link: https://www.kaggle.com/datasets/yusufdelikkaya/online-sales-dataset?resource=download

### Tratamento no Python
Antes de Iniciar no relatório no Power BI, tratei a base de dados no Python. 
1. Exclusão de Outliers.
2. Exclusão de datas futuras. (Conforme a época que foi feito)
3. Exclusão de dados faltantes.
4. Produtos classificado em categorias erradas.

## Breve análise do relatório

* Visão Geral

Ao analisar a categoria de Acessórios, observa-se que a loja de Portugal possui o maior faturamento até o momento, mas isso se deve ao fato de ela ter realizado um número maior de vendas em comparação às lojas da Alemanha e da Espanha. Surge a dúvida: será que algum custo na operação da loja de Portugal é mais elevado? Ou será que as lojas da Alemanha e da Espanha adotam práticas diferentes que impactam positivamente sua eficiência?

Outra possível explicação pode estar no desconto oferecido pela loja de Portugal, que parece ser maior. Isso é sugerido pelo fato de que, embora a loja online de Portugal seja uma das que mais vende, ela apresenta o quarto pior faturamento da categoria no ambiente online.

![Visão Geral](analisegeral1.png) ![Visão Geral](analisegeral2.png)

* Devoluções

A categoria de Eletrônicos apresenta o maior volume de devoluções. Entre os produtos, o Mouse Wireless é o mais devolvido, tanto nas lojas físicas quanto nas lojas online.

Na análise das devoluções das lojas online, constata-se que 92% delas estão associadas a pedidos com prioridade de entrega classificada como "Low". Isso sugere que a demora na entrega leva os consumidores a desistirem da compra. Além disso, 72% das devoluções se originam no centro de distribuição de Roma, e a transportadora UPS teve 100% de suas entregas devolvidas. Esses dados indicam que pode haver problemas operacionais no centro de distribuição ou falhas na execução das entregas pela transportadora.

Nas lojas físicas, o percentual de devoluções é ligeiramente menor em relação às online, mas o número absoluto de devoluções é maior. É possível que isso esteja relacionado à qualidade dos produtos ou a informações inadequadas fornecidas pelos vendedores. Seria interessante aprofundar a análise nesses dois aspectos.



