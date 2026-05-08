# Medidas DAX - Dashboard de Vendas

Crie uma tabela de medidas no Power BI e adicione as medidas abaixo.

```DAX
Receita Total = SUM(Vendas[receita_liquida])

Custo Total = SUM(Vendas[custo_total])

Lucro Total = SUM(Vendas[lucro])

Total de Vendas = COUNTROWS(Vendas)

Quantidade Vendida = SUM(Vendas[quantidade])

Ticket Médio = DIVIDE([Receita Total], [Total de Vendas])

Margem de Lucro % = DIVIDE([Lucro Total], [Receita Total])

Vendas Concluídas = 
CALCULATE(
    COUNTROWS(Vendas),
    Vendas[status] = "Concluída"
)

Taxa de Cancelamento % =
DIVIDE(
    CALCULATE(COUNTROWS(Vendas), Vendas[status] = "Cancelada"),
    COUNTROWS(Vendas)
)

Receita Mês Anterior =
CALCULATE(
    [Receita Total],
    DATEADD(Vendas[data], -1, MONTH)
)

Variação Receita % =
DIVIDE(
    [Receita Total] - [Receita Mês Anterior],
    [Receita Mês Anterior]
)
```
