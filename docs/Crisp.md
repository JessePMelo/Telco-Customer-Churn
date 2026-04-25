CRISP-DM Framework
1 Business Understanding
Problema de negócio: Empresa do sertor de telecomunicações com muito cancelamento de contratos 
Objetivo: Identificar caracteristicas que influenciam no cancelamento
KPI principal: Cancelamento 
Critério de sucesso: Separar clientes em categorias de muita,media, baixa e meuito baixa chance de cancelamento. Identificar os clientes que geram maior receita e tem alta probabilidade de cancelamento e mostrar as caracteriscas que mais impactam no cancelamento.

2 Data Understanding
Fontes de dados: Dataset publico fornecido pela IBM
Variável target: Churn
Período dos dados: Não se aplica
Problemas conhecidos: Como os dados vieram da IBM não tem grandes problemas. Oque me incomodou é não tem geolocalização

3 Data Preparation
Pipeline:
problem definition → data understanding → data cleaning → feature engineering → modeling → model evaluation → model explainability → model selection → conclusion

4 Modeling
Baseline: Regressão Logistica
Modelos candidatos: random forest e xgboost


5 Evaluation
Métricas:
Precision 0.52
Recall 0.80
F1 0.63
