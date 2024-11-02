# Dashboards-An-lises-Mkt
Análise de Campanhas de Marketing com Power BI

# Análise de Marketing - Power BI

Este repositório contém um dashboard em Power BI focado na análise de métricas de marketing. A base de dados utilizada, **dados_marketing.csv**, oferece informações sobre dados demográficos, comportamento de compra, gastos e engajamento do público em campanhas de marketing. O arquivo principal do Power BI, **AnáliseMkt.pbix**, apresenta visualizações e insights para suportar decisões estratégicas de marketing.

## Objetivo do Projeto

Estes relatórios estão divididos em 4 visões:
• Visão do Cliente
• Visão do Comportamento de Compra do Cliente
• Visão da Performance das Campanhas de Marketing
• Visão dos Padrões de Compra no Ponto de Venda (País)

Para cada visão apresentamos as varáveis, gráficos e medidas, entregando visões completas sobre os perfis dos clientes, padrões de compra e efetividades das campanhas de marketing.

### Objetivos das Análises

1. **Monitoramento de Campanhas**: Acompanhar o impacto das campanhas de marketing ao longo do tempo, identificando as mais eficazes.
2. **Segmentação e Perfil do Público**: Explorar dados demográficos e financeiros para ajustar o público-alvo e segmentar campanhas.
3. **Análise de Comportamento de Compra**: Observar o ciclo de compra dos clientes para otimizar estratégias de aquisição e retenção.
4. **Avaliação Gastos por categorias e países**: Avaliar o total de gasto por países em diferentes categorias e por ano.

## Visões do Dashboard

### 1. Visão Geral do Cliente

- **Objetivo**: Proporcionar uma visão geral dos tipos de clientes como os mesmos segmentados por estado civil e por grau de escolaridade, além de diversas métricas da valores de compras.
- **Métricas Principais**:
  - **Contagem de ID**: Medida para avaliar a contagem de clientes.
  - **Média de salário anual**: Média de salário anual dos clientes.
  - **Compras na loja física**: Valor referente ao total de compras realizadas na loja física.
  - **Compras na web**: Valor referente ao total de compras realizadas na loja da web.
  - **Compras via catálogo**: Contagem do total de compras via catálogo.
  - **Filtros**: Filtros para análises de clientes por países.

### 2. Visão Comportamento

- **Objetivo**: Explorar o perfil de comportamento de compra e de valores refentes ao clientes que possuem filhos e adolescentes.
- **Métricas principais**:
  - **Total e gastos x salário anual**: Distribuição da soma do total gasto com diversas categorias e os gastos x salário anual.
  - **Arvore hirarquica do total gasto po estado civil e escolaridade**: Gráfico exibindo o total gasto de acordo com o estado civil do cliente e seu grau de escolaridade.
  - **Total de gastos x filhos em casa**: Total gasto referente aos clientes que possuem filhos em casa.
  - **Total de gastos x adolescentes em casa**: Total gasto referente aos clientes que possuem adolescentes em casa.

### 3. Visão Campanhas

- **Objetivo**: Analisar a perfomance referente as campanhas de marketing realizadas.
- **Métricas**:
  - **Total de compras vs a quantia de filhos em casa**: Quantidade de compras feitas de acordo com a quantidade de filhos que moram em casa.
  - **Resultado das campanhas de marketing**: Gráfico de pizza analisando clientes que compraram ou não referente as campanhas de marketing.
  - **Tabela de compras na campanha por segmentos de clientes**: Tabela exibindo se clientes compraram nas campanhas divididos por estado civil e grau de esclaridade.
  - **Média de salário anual vs resultados**: Média de salário anual de clientes de acordo se compraram ou nao nas campanhas .


### 4. Visão Ponto de Vendas

- **Objetivo**: Análisar de onde vem as compras segmmentadas por diversos tipos de cateogiras e por tempo.
- **Métricas de Campanha**:
  - **Total gasto em diversas categorias por país**: Comparação das compras de acordo com as categorias e divididas pelos países.
  - **Total gasto por ano e páis**: Linha no tempo do total gasto em diversas categorias por país.

## Estrutura do Repositório

- **AnáliseMkt.pbix**: Arquivo principal do Power BI contendo as 4 visões detalhadas acima.
- **dados_marketing.csv**: Base de dados em formato CSV utilizada para alimentar as análises.

## Como Utilizar

1. **Pré-requisitos**: Instale o Power BI Desktop para abrir e explorar o arquivo `.pbix`.
2. **Abrindo o Arquivo**: Baixe **AnáliseMkt.pbix** e abra-o no Power BI Desktop.
3. **Exploração do Dashboard**: Use os filtros e segmentadores interativos para ajustar as visualizações conforme necessário para análise.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues, fazer um fork e enviar um pull request com sugestões de melhorias.

