Projeto prático desenvolvido na Formação Power BI Analyst da DIO. O objetivo deste projeto foi aplicar funcionalidades avançadas de Análise de Dados (Data Analytics) nativas e personalizadas do Power BI sobre uma base de dados financeira!

## O que foi implementado
O relatório foi expandido para 6 páginas interativas, focando na extração de *insights* dinâmicos:

* **Navegabilidade Estruturada:** Implementação de botões de navegação globais e uso avançado de **Indicadores (Bookmarks)** com o painel de seleção, permitindo alternar a visualização de gráficos (Semestres vs. Meses) ocupando o mesmo espaço na tela.
* **Filtros Top N e Outliers:** Configuração de filtros de *N superior* atrelados a medidas DAX para isolar os melhores resultados (Top 5 Meses, Top 3 Países) e identificação de anomalias nas vendas.
* **Análise Temporal Animada:** Inserção de eixo de reprodução (*Play Axis*) em gráficos de dispersão, criando animações temporais para acompanhar a evolução de vendas, unidades e lucros por produto ao longo dos meses.
* **Agrupamento e Clusterização:** Utilização dos algoritmos de Machine Learning do Power BI para agrupar clientes/produtos e gerar *Clusters* automáticos de lucro.
* **Visuais Personalizados e Tendências:** Uso do *Sankey Diagram* para mapear o fluxo de vendas entre continentes e anos, além da ativação de linhas de tendência analíticas em gráficos de dispersão.

## Estrutura das Páginas
1. **Home page:** Capa de entrada do relatório.
2. **Principal:** Visão executiva e segmentação macro.
3. **Detalhes:** Histogramas e detalhamento com botões de alternância (Bookmarks).
4. **TOPN & Outliers:** Gráficos de dispersão dinâmicos e rankings.
5. **Data Analytics:** Correlações, linhas de tendência e análise de máximos.
6. **Categorias & Cluster:** Segmentações por grupos, clusters e fluxos de dados (Sankey).

## Ficheiros
* `sales_report_data_analytics.pbix`: Ficheiro do Power BI Desktop com o dashboard completo.
