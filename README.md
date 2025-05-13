# 🛒 Análise de Fraudes e Riscos no Delivery Walmart  
Projeto de Data Science | William Rodrigues

📌 Descrição

Este projeto analisa ocorrências de fraudes no sistema de delivery do e-commerce do Walmart na Flórida Central (EUA), com foco em perdas relatadas por consumidores. Foram aplicadas técnicas de análise exploratória, modelagem de dados e visualizações para identificação de padrões e riscos associados.

## Objetivos 🎯

- **Analisar ocorrências de não recebimento de produtos.** 📦❌
- **Identificar padrões de fraude envolvendo entregadores, horários e regiões.** 🕒🚚
- **Aplicar machine learning para prever riscos de fraude.** 🤖
- **Propor soluções baseadas em evidências estatísticas com validação experimental.** 📊✅

## Metodologia (CRISP-DM) 🔄
| Etapa                        | Status          |
|------------------------------|-----------------|
| **Entendimento do Negócio**       | ✅ Concluído    |
| **Entendimento dos Dados**        | ✅ Concluído    |
| **Preparação dos Dados**          | ✅ Concluído    |
| **Modelagem**                     | 🟡 Em andamento |
| **Avaliação dos Resultados**      | 🔲 A fazer      |
| **Deploy / Validação (RCT)**      | 🔲 A fazer      |

## Análises Realizadas 🔍

### 📊 Análises com SQL & Excel
- **Métricas Gerais**: Total de pedidos, valor total dos pedidos, itens faltantes, prejuízo estimado. 💰
- **Análise por Região**: Pedidos e perdas por região, prejuízo financeiro. 🌍
- **Análise por Entregador**: Taxa de faltas, entregadores fora da média. 🚚
- **Análise por Produto**: Produtos mais faltantes, impacto financeiro. 📦
- **Análise Temporal**: Sazonalidade de perdas ao longo do tempo. 📅
- **Detecção de Padrões de Fraude**: Correlação entre região, entregador e horário. 🕵️‍♂️

### 🛠️ Análises e Modelos Realizados com Python

1. **Exploração Geral + Insights Visuais (Notebook 01)** 📊:
   - Análise descritiva com gráficos, correlações, e identificação de padrões de fraude por região, entregador, turno e dia da semana. 
   - Ferramentas utilizadas: Pandas, Matplotlib, Seaborn.

2. **Modelo de Classificação Preditiva de Fraude (Notebook 02)** 🔮:
   - Modelo **Random Forest** para prever se um pedido é fraudulento, com validação usando SMOTE para balanceamento de classes.
   - Métricas: Precisão, Recall, F1-Score, AUC-ROC. 📈
   - **Arquivo gerado**: Base com previsões salvas (ex.: `Base_Painel_U_2_com_previsoes.xlsx`).

3. **Clustering de Risco (Notebook 03)** 🔒:
   - Segmentação de pedidos utilizando **KMeans** para identificar grupos de comportamento de risco.
   - Análise das características dos clusters (ex.: valores de pedido, número de itens entregues).
   - **Arquivo gerado**: Base com clusters salvos (ex.: `Base_Painel_U_2_com_clusters.xlsx`).

4. **Detecção de Outliers com Isolation Forest (Notebook 04)** 🚨:
   - Aplicação de **Isolation Forest** para identificar anomalias nos dados de pedidos, detectando comportamentos suspeitos.
   - **Arquivo gerado**: Base com outliers salvos (ex.: `Base_Painel_U_2_com_outliers.xlsx`).

## Próximos Passos ⏳

- **Avaliação dos Modelos**: Aplicar avaliação detalhada dos modelos, incluindo validação cruzada, métricas de desempenho e análise de impacto. ⚖️
- **Deploy e Validação (RCT)**: Implementar testes de validação experimental (Randomized Controlled Trial) para avaliar a eficácia do modelo em um ambiente real. 🚀

## 📁 Estrutura do Projeto

| Pasta / Arquivo     | Descrição |
|---------------------|-----------|
| `/data/`            | Arquivos de dados brutos e tratados (Excel e CSV) |
| `/notebooks/`       | Notebooks do Jupyter com análises e modelagem |
| `/src/`             | Scripts de pré-processamento, modelagem e utilitários |
| `/reports/`         | Relatórios gerados com insights e tabelas |
| `README.md`         | Documentação do projeto |
| `requirements.txt`  | Bibliotecas necessárias |
| `.gitignore`        | Arquivos e pastas ignoradas pelo Git |
## 📊 Etapas Realizadas

✅ Organização e limpeza dos dados  
✅ Cálculo de métricas de risco e fraude por região, turno, entregador  
✅ Clusterização para detectar padrões anômalos  
✅ Modelo de Machine Learning para previsão de risco  
✅ Análise de outliers e casos extremos  
✅ Geração de dashboards no Power BI 


## Tecnologias Utilizadas ⚙️
- **Python**: Pandas, Scikit-learn, Imbalanced-learn 🐍
- **SQL**: Análise de dados com SQL 🧮
- **Excel & Power BI**: Análise e visualizações 📊
- **Git & GitHub**: Versionamento e entrega final 🦸‍♂️

## Autor 👨‍💻
**William Rodrigues**  
Projeto desenvolvido no contexto do **Curso de Data Science – 2025** 🎓
