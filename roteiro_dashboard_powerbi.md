# Roteiro do Dashboard no Power BI

## Página 1 - Visão Geral de Vendas

### KPIs no topo
Use cartões para:
- Receita Total
- Lucro Total
- Total de Vendas
- Ticket Médio
- Margem de Lucro %

### Gráficos principais
1. Gráfico de linhas:
   - Eixo X: data por mês
   - Valores: Receita Total
   - Título: Evolução Mensal da Receita

2. Gráfico de barras:
   - Eixo Y: regiao
   - Valores: Receita Total
   - Título: Receita por Região

3. Gráfico de colunas:
   - Eixo X: categoria
   - Valores: Receita Total
   - Título: Receita por Categoria

4. Gráfico de barras:
   - Eixo Y: produto
   - Valores: Receita Total
   - Filtro Top N: Top 10 produtos
   - Título: Top 10 Produtos por Receita

5. Gráfico de rosca:
   - Legenda: canal_venda
   - Valores: Receita Total
   - Título: Receita por Canal de Venda

### Segmentações
Adicione filtros para:
- Ano
- Região
- Categoria
- Canal de venda
- Status

## Página 2 - Análise de Lucratividade

### KPIs
- Receita Total
- Custo Total
- Lucro Total
- Margem de Lucro %

### Gráficos
1. Lucro por categoria
2. Margem de lucro por produto
3. Receita x Lucro por região
4. Receita por vendedor

## Nome da tabela no Power BI
Ao importar o CSV, renomeie a tabela para:

Vendas

Isso garante que as medidas DAX funcionem sem ajustes.
