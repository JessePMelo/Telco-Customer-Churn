CRISP-DM Framework

1. Business Understanding
Problema de negócio: Empresa do setor de telecomunicações com alta taxa de cancelamento de contratos (churn).

Objetivo: Identificar os principais fatores que influenciam o cancelamento de clientes e prever a probabilidade de churn.

KPI principal: Taxa de churn (%)

Critério de sucesso:
- Classificar clientes em categorias de risco (alto, médio, baixo)
- Identificar clientes de alto valor com alta probabilidade de cancelamento
- Extrair insights sobre as variáveis mais relevantes para o churn


2. Data Understanding
Fontes de dados: Dataset público fornecido pela IBM

Variável target: Churn

Período dos dados: Não especificado

Limitações:
- Ausência de geolocalização
- Dataset não temporal (não permite análise de evolução no tempo)
- Possível natureza sintética dos dados


3. Data Preparation
Pipeline:
problem definition → data understanding → data cleaning → feature engineering → modeling → model evaluation → model explainability → model selection → conclusion


4. Modeling
Baseline: Regressão Logística

Modelos candidatos:
- Random Forest
- XGBoost


5. Evaluation
Métricas:
- Precision: 0.52
- Recall: 0.80
- F1-score: 0.63


6. Conclusion
O modelo apresentou bom desempenho na identificação de clientes com risco de churn, com destaque para o recall elevado.

Isso indica que o modelo é eficiente em capturar clientes que realmente cancelam, sendo útil para estratégias de retenção, ainda que com trade-off em precisão.