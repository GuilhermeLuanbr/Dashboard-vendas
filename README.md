# Dashboard de Vendas - Power BI

## Objetivo
Analisar dados de vendas para identificar padrões de receita, lucratividade, canais de venda, desempenho por região, categoria e produto.

## Ferramentas utilizadas
- Power BI
- DAX
- CSV/Excel
- Modelagem de dados
- Análise de indicadores

## Dataset
O dataset foi gerado de forma fictícia, simulando vendas entre 2024 e 2025.

### Colunas principais
- data
- produto
- categoria
- regiao
- canal_venda
- tipo_cliente
- vendedor
- quantidade
- preco_unitario
- receita_liquida
- custo_total
- lucro
- status

## KPIs sugeridos
- Receita Total
- Lucro Total
- Total de Vendas
- Ticket Médio
- Margem de Lucro %
- Taxa de Cancelamento %

## Análises realizadas
- Evolução mensal da receita
- Receita por região
- Receita por categoria
- Top produtos por receita
- Receita por canal de venda
- Lucratividade por categoria e produto
- Desempenho por vendedor

## Estrutura do projeto

dashboard-vendas-powerbi/
├── dataset/
│   ├── vendas_powerbi.csv
│   └── vendas_powerbi.xlsx
├── docs/
│   ├── medidas_dax.md
│   └── roteiro_dashboard_powerbi.md
├── dashboard/
│   └── coloque_aqui_o_arquivo_pbix.txt
├── imagens/
│   └── coloque_aqui_os_prints_do_dashboard.txt
└── README.md
```

## Como usar
1. Abra o Power BI Desktop
2. Importe o arquivo `dataset/vendas_powerbi.csv`
3. Renomeie a tabela para `Vendas`
4. Crie as medidas DAX disponíveis em `docs/medidas_dax.md`
5. Monte os gráficos seguindo `docs/roteiro_dashboard_powerbi.md`
6. Salve o arquivo `.pbix` na pasta `dashboard`
7. Exporte prints do dashboard para a pasta `imagens`

## Autor
Guilherme Luan Fernandes
