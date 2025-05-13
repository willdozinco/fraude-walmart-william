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

## Estrutura do Repositório 📂

🛒 Análise de Fraudes e Riscos no Delivery Walmart
│
├── data/
│ ├── Base_Painel_U_2.xlsx # Base de dados original
│ ├── Base_Painel_U_2_com_previsoes.xlsx # Base com previsões do modelo
│ ├── Base_Painel_U_2_com_clusters.xlsx # Base com clusters de risco
│ └── Base_Painel_U_2_com_outliers.xlsx # Base com outliers detectados
│
├── notebooks/
│ ├── 01_Exploracao_Geral.ipynb # Análise exploratória e visualizações
│ ├── 02_Modelo_Classe.ipynb # Modelo de classificação (fraude)
│ ├── 03_Clustering.ipynb # Segmentação de risco (KMeans)
│ ├── 04_Outliers.ipynb # Detecção de outliers com Isolation Forest
│ └── README.md # Descrição do projeto e notebooks
│
├── sql_queries/
│ ├── query_regiao.sql # SQL para análise por região
│ ├── query_entregador.sql # SQL para análise por entregador
│ └── query_produto.sql # SQL para análise por produto
│
├── models/
│ ├── modelo_final_fraude.pkl # Modelo treinado para previsão de fraude
│ └── README.md # Explicação sobre os modelos treinados
│
└── README.md # Descrição geral do projeto

markdown
Copiar
Editar

## Tecnologias Utilizadas ⚙️
- **Python**: Pandas, Scikit-learn, Imbalanced-learn 🐍
- **SQL**: Análise de dados com SQL 🧮
- **Excel & Power BI**: Análise e visualizações 📊
- **Git & GitHub**: Versionamento e entrega final 🦸‍♂️

## Autor 👨‍💻
**William Rodrigues**  
Projeto desenvolvido no contexto do **Curso de Data Science – 2025** 🎓
