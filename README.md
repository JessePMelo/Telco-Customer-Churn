# Telco Customer Churn Prediction

## Overview
This project presents an end-to-end machine learning solution to predict
customer churn in a telecommunications context, with a strong focus on
interpretability and business-oriented decision making.

The goal is to identify customers with a higher risk of cancellation,
enabling proactive retention strategies.

## Business Problem
Customer churn has a direct impact on revenue and long-term growth.
In competitive subscription-based markets, retaining existing customers
is often more cost-effective than acquiring new ones.

This project addresses the challenge of identifying churn risk in advance,
allowing the business to act before customers leave.

## Approach
A structured machine learning pipeline was built using Logistic Regression,
selected for its transparency and interpretability.

The solution includes:
- Proper train-test separation and preprocessing pipelines
- Recall-oriented evaluation aligned with business risk
- Probability calibration for reliable risk estimation
- Model explainability using coefficients and SHAP values

## Key Metric
Recall for the churn class was prioritized, as failing to identify a
customer at risk represents a higher business cost than a false positive.

## Key Insights
- Contract type and customer tenure are among the strongest drivers of churn
- Month-to-month contracts show significantly higher churn risk
- Longer customer tenure strongly contributes to retention
- Payment methods and internet service type also influence churn behavior

## Business Recommendations
Based on the model insights, the following actions are recommended:
- Prioritize retention campaigns for customers on month-to-month contracts
- Offer incentives for long-term contract migration
- Target early-tenure customers with onboarding and support initiatives
- Use calibrated churn probabilities to segment customers by risk level

## Project Structure
- `data_science/notebooks/02_final_churn_model.ipynb`  
  Final, presentation-ready notebook with full analysis and explanations

## Notes
This project emphasizes decision-making, interpretability, and clarity
over model complexity or raw predictive performance.

---

# Previsão de Churn de Clientes (Português)

## Visão Geral
Este projeto apresenta uma solução completa de machine learning para
prever o churn (cancelamento) de clientes em um contexto de telecomunicações,
com forte foco em interpretabilidade e tomada de decisão orientada ao negócio.

O objetivo é identificar clientes com maior risco de cancelamento,
permitindo ações proativas de retenção.

## Problema de Negócio
O churn de clientes impacta diretamente a receita e o crescimento
de longo prazo. Em mercados competitivos e baseados em assinatura,
reter clientes existentes costuma ser mais barato do que adquirir novos.

Este projeto aborda o desafio de identificar o risco de churn de forma
antecipada, permitindo que a empresa atue antes da perda do cliente.

## Abordagem
Foi construído um pipeline estruturado de machine learning utilizando
Regressão Logística, escolhida por sua transparência e interpretabilidade.

A solução inclui:
- Separação adequada entre treino e teste
- Pipeline de pré-processamento para evitar vazamento de dados
- Avaliação orientada ao recall, alinhada ao risco de negócio
- Calibração de probabilidades para estimativas confiáveis
- Explicabilidade do modelo por meio de coeficientes e SHAP

## Métrica Principal
O recall da classe churn foi priorizado, pois não identificar um cliente
em risco representa um custo maior para o negócio do que um falso positivo.

## Principais Insights
- Tipo de contrato e tempo de permanência são os principais fatores de churn
- Contratos mensais apresentam risco significativamente maior
- Clientes com maior tempo de casa tendem a permanecer
- Método de pagamento e tipo de serviço de internet influenciam o churn

## Recomendações de Negócio
Com base nos insights do modelo, recomenda-se:
- Priorizar campanhas de retenção para clientes com contrato mensal
- Incentivar migração para contratos de longo prazo
- Atuar nos primeiros meses do cliente com suporte e onboarding
- Utilizar probabilidades calibradas para segmentar clientes por nível de risco

## Estrutura do Projeto
- `data_science/notebooks/02_final_churn_model.ipynb`  
  Notebook final, pronto para apresentação, contendo toda a análise

## Observações
Este projeto prioriza clareza, interpretabilidade e tomada de decisão
em detrimento de complexidade excessiva ou otimização extrema de métricas.
