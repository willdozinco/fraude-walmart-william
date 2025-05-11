# 🛒 Análise de Fraudes e Riscos no Delivery Walmart  
Projeto de Data Science | William Rodrigues

📌 Descrição

Este projeto analisa ocorrências de fraudes no sistema de delivery do e-commerce do Walmart na Flórida Central (EUA), com foco em perdas relatadas por consumidores. Foram aplicadas técnicas de análise exploratória, modelagem de dados e visualizações para identificação de padrões e riscos associados.


🎯 Objetivos

- ✅ Analisar ocorrências de não recebimento de produtos.
- ✅ Identificar padrões de fraude envolvendo entregadores, horários e regiões.
- 🟡 Aplicar machine learning para prever riscos de fraude.
- 🔲 Propor soluções baseadas em evidências estatísticas com validação experimental.


## 🧠 Metodologia (CRISP-DM)

| Etapa                         | Status       |
|------------------------------|--------------|
| Entendimento do Negócio      | ✅ Concluído  |
| Entendimento dos Dados       | ✅ Concluído  |
| Preparação dos Dados         | ✅ Concluído  |
| Modelagem                    | 🟡 Em andamento |
| Avaliação dos Resultados     | 🔲 A fazer   |
| Deploy / Validação (RCT)     | 🔲 A fazer   |


📊 Análises Realizadas (SQL & Excel)

1. ✅ **Métricas Gerais**  
   - Total de pedidos  
   - Valor total dos pedidos  
   - Itens faltantes  
   - Prejuízo estimado

2. ✅ **Análise por Região**  
   - Pedidos e perdas por região  
   - Prejuízo financeiro

3. ✅ **Análise por Entregador**  
   - Taxa de faltas  
   - Entregadores fora da média

4. ✅ **Análise por Produto**  
   - Produtos mais faltantes  
   - Impacto financeiro

5. ✅ **Análise Temporal**  
   - Sazonalidade de perdas

6. ✅ **Detecção de Padrões de Fraude**  
   - Correlação entre região, entregador e horário


## 📁 Estrutura do Projeto
📁 data/ → dados brutos e tratados (.csv, .xlsx)
📁 sql_queries/ → análises SQL feitas no Data.World
📁 notebooks/ → notebooks Python (Jupyter) com análises e modelos
📁 src/ → scripts auxiliares (ETL, ML, funções)
📁 dashboards/ → prints e/ou link do dashboard no Power BI
📁 reports/ → documentos finais (Word, PPT)
📄 README.md → descrição do projeto


📊 Análises Realizadas (via SQL)

1. **Métricas Gerais**
   - Total de pedidos, valor total e prejuízo estimado.
2. **Por Região**
   - Volume de pedidos, itens faltantes e prejuízo.
3. **Por Entregador**
   - Comparativo de performance e detecção de comportamento suspeito.
4. **Por Produto**
   - Frequência de faltas e impacto financeiro.
5. **Temporal**
   - Análise por mês e horário.
6. **Padrões de Fraude**
   - Correlação entre regiões, turnos e entregadores.

As queries estão salvas na pasta `/sql_queries`.


🚀 Tecnologias Utilizadas

- **Excel & Power BI** – análise e visualizações
- **Python (Pandas, Scikit-learn)** – modelagem e predição
- **SQL (Data.World)** – exploração dos dados
- **Git & GitHub** – versionamento e entrega final


👨‍💻 Autor

William Rodrigues  
Projeto Curso de Data Science – 2025
