# Power BI – Dashboard de Vendas

Projeto de estudo de Business Intelligence com foco em modelagem dimensional, medidas DAX e análise de vendas.

## Estado do repositório

Este repositório contém somente esta documentação. Ainda não há arquivo `.pbix`/`.pbip`, base de dados, medidas DAX exportadas ou imagens do relatório versionadas. Por isso, não é possível reproduzir o dashboard, conferir os indicadores ou avaliar sua interface a partir do conteúdo atual.

## Entrega mínima para reprodução

- Arquivo do projeto Power BI ou estrutura PBIP, sem credenciais.
- Base fictícia ou anonimizada, com origem e condições de uso documentadas.
- Dicionário com nomes, tipos, granularidade e significado das colunas.
- Descrição dos relacionamentos e da tabela calendário.
- Medidas DAX em texto e definição de cada indicador.
- Capturas das páginas, incluindo filtros aplicados e período analisado.
- Instruções para configurar a fonte e atualizar o relatório no Power BI Desktop.

## Roteiro de validação

1. Confirmar a granularidade da tabela de vendas e a unicidade das dimensões.
2. Conferir chaves sem correspondência, nulos e duplicações antes de medir receita.
3. Reconciliar os totais do relatório com a fonte para o mesmo período e filtros.
4. Validar receita, quantidade, pedidos e ticket médio com regras explícitas, incluindo cancelamentos e devoluções.
5. Testar filtros sem resultados e divisões com denominador zero.
6. Revisar contraste, títulos, unidades, casas decimais e navegação por teclado.
7. Registrar a data da validação e evidências dos resultados, sem expor dados pessoais.

## Organização sugerida

Quando os artefatos estiverem disponíveis, separar `dados/`, `medidas/`, `imagens/` e `docs/`. Essas pastas são uma proposta de organização; ainda não existem neste repositório.

Não publicar credenciais, dados de clientes ou informações comerciais privadas. A documentação não representa um dashboard implementado nem indicadores validados.
