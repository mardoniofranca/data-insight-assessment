# Clube da Esquina -  🔭

**Analisando Dados de Clientes para Produto Bancário **

## Desafio

O desafio envolve analisar campanhas de marketing de uma institiução bancária. Nas campanhas é vendido ao cliente um produto adicional de débito automático. Queremos saber se um determinado cliente se inscreve ou não ao produto. Portanto, **é um problema de classificação**:

1. cliente se inscreve/ 2. o cliente não se inscreve

### Objetivo

1. Code:
   1. Implementar um modelo de classificação com uma performance aceitável (nos códigos, pasta src)
   1. Conjunto de dados contendo a coluna da previsão, `y'` (pasta data/result_campaigns.csv)

1. Insight:
   1. Elencar e **analisar** quais _features_ são determinantes para aderência de um cliente ao produto (nos códigos, pasta src)
   1. Descrever um **plano de ação** para futuras campanhas de marketing fundamentado na análise deste conjunto de dados (planoacao.md)

### Resultados

Todos os notebooks jupyter estão na pasta src

1. Modelo:  (src/Modelo_Classificacao.ipynb)
2. Análise de Resultados:  (src/Analise_Dados.ipynb)
3. Segmentação dos Clientes: (src/Segm_Clientes.ipynb)
4. Plano de Ação, um breve caminho (planoacao.md)
5. Conjunto de Dados com a coluna previsão, 'y' (data/result_campaigns.csv)

obs.: inicialmente, via código, a coluna referente ao resultado era 'pred' e foi modificada manualmente para 'y' afim de garantir com a especificação requisitada.
