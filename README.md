# Power BI – Dashboard de Vendas

Projeto de Business Intelligence desenvolvido em Power BI Desktop com foco em modelagem dimensional, criação de medidas em DAX e análise de vendas.

## 🎯 Objetivo
Responder perguntas de negócio como:
- Qual categoria de produto gera mais vendas?
- Como as vendas evoluem ao longo do tempo?
- Qual o ticket médio?
- Qual a participação (%) de cada categoria no faturamento total?

## 🗂️ Dataset
Dados simulados em formato CSV/Excel:
- **Clientes** (dimensão)
- **Produtos** (dimensão)
- **Vendas** (fato)

Os arquivos estão disponíveis na pasta `/data`.

## 🧱 Modelagem de Dados
Modelo estrela:
- `Vendas` como tabela fato
- `Clientes` e `Produtos` como tabelas dimensão  
Relacionamentos 1:N (dimensões → fato).

## 📐 Medidas DAX
- Total de Vendas
- Quantidade de Vendas
- Ticket Médio
- % Participação por Categoria

As medidas estão documentadas em `/docs/medidas_dax.md`.

## 📊 Dashboard
O dashboard apresenta:
- KPIs de vendas e ticket médio
- Análise de vendas por categoria
- Evolução temporal das vendas
- Segmentadores por categoria e data

Imagens do dashboard estão disponíveis em `/exports`.

## 🛠️ SQL
Scripts SQL incluídos para simular a criação e análise de dados em banco relacional:
- Criação de tabelas
- Inserção de dados
- Consultas analíticas

## ▶️ Como executar
1. Clone o repositório
2. Abra o arquivo `/powerbi/dashboard_vendas.pbix` no Power BI Desktop
3. Ajuste o caminho das fontes se necessário

## 🚀 Próximos passos
- Criar tabela calendário
- Adicionar métricas de crescimento (MoM / YoY)
- Refinar regras de qualidade de dados
