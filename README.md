# Telco Customer Churn Prediction

## 📌 Project Overview (English)

Customer churn is one of the most critical problems in subscription-based businesses.  
This project focuses on predicting customer churn using Machine Learning techniques, with a strong emphasis on **interpretability**, **statistical rigor**, and **real-world applicability**.

The goal is not only to build predictive models but also to **understand the drivers of churn**, explain model decisions, and extract actionable insights for business decision-making.

This repository contains:
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model training and evaluation
- Interpretation using coefficients and SHAP values
- A final production-ready notebook

---

## 📌 Visão Geral do Projeto (Português)

A evasão de clientes (churn) é um dos principais desafios de negócios baseados em assinatura.  
Este projeto tem como objetivo prever o churn de clientes utilizando técnicas de Machine Learning, com forte foco em **interpretabilidade**, **fundamentação estatística** e **aplicação prática no mundo real**.

Mais do que apenas prever, o projeto busca **entender os fatores que levam ao cancelamento**, explicar as decisões do modelo e gerar **insights acionáveis para o negócio**.

Este repositório contém:
- Análise exploratória dos dados
- Engenharia de atributos
- Treinamento e avaliação de modelos
- Interpretação via coeficientes e SHAP
- Um notebook final pronto para portfólio

---

## 🎯 Business Problem | Problema de Negócio

### English
Customer churn directly impacts revenue, growth, and long-term sustainability.  
Being able to **anticipate churn** allows companies to act proactively, offering retention strategies before customers leave.

### Português
O churn impacta diretamente receita, crescimento e sustentabilidade do negócio.  
Antecipar o cancelamento permite ações preventivas, como campanhas de retenção e melhorias de serviço.

---

## 📂 Repository Structure | Estrutura do Repositório

- **data_science/**
  - **data/**
    - **raw/**
      - `WA_Fn-UseC_-Telco-Customer-Churn.csv`
  - **notebooks/**
    - `01_lab_exploration.ipynb`
    - `02_final_churn_model.ipynb`
- `requirements.txt`
- `README.md`


---

## 📘 Notebooks Description | Descrição dos Notebooks

### 🔍 01_lab_exploration.ipynb
**Exploratory Data Analysis & Feature Understanding**

- Data loading and cleaning
- Handling missing values
- Distribution analysis
- Correlation analysis
- Initial business insights

### 🧠 02_final_churn_model.ipynb
**Final Model & Interpretation**

- Feature selection
- Train/test split
- Model training:
  - Logistic Regression (primary and baseline model)
  - Random Forest (comparative model for non-linear effects)
- Evaluation metrics:
  - Accuracy
  - Precision
  - Recall
  - Confusion Matrix
- Model interpretation:
  - Coefficients (Logistic Regression)
  - SHAP values (global and local explanations)

---

## 🧪 Models Used | Modelos Utilizados

### Logistic Regression
- Baseline and main model
- High interpretability
- Coefficients analyzed to understand feature impact

### Random Forest
- Used as a comparative model
- Captures non-linear relationships
- Higher predictive power in some scenarios
- Feature importance and SHAP explanations

---

## 🧪 Validation Strategy | Estratégia de Validação

### English
The dataset was split into training and testing sets to evaluate generalization performance.  
Care was taken to avoid data leakage, ensuring that all preprocessing and feature engineering steps were applied consistently across splits.

### Português
O conjunto de dados foi dividido em treino e teste para avaliar a capacidade de generalização do modelo.  
Foram adotados cuidados para evitar vazamento de dados, garantindo que as etapas de pré-processamento e engenharia de atributos fossem aplicadas de forma consistente.

---

## 📊 Model Interpretability | Interpretabilidade

### Coefficients
Used to understand how each feature affects the probability of churn in linear models.

### SHAP (SHapley Additive exPlanations)
- Global feature importance
- Local explanations for individual predictions
- Clear visualization of model behavior

This combination ensures **trustworthy and explainable AI**.

---

## 🧠 Key Insights | Principais Insights

- Contract type strongly influences churn
- Monthly charges have a significant impact
- Tenure is one of the most protective factors against churn
- Some features show non-linear effects, captured better by tree-based models

---

## 🎥 Project Presentation | Apresentação do Projeto

- 📺 **YouTube Video (PT-BR)**  
  https://www.youtube.com/watch?v=cbw1K6l7Bxg  

- 📝 **LinkedIn Article**  
  https://www.linkedin.com/posts/jessepmelo_apresento-aqui-um-projeto-completo-de-machine-activity-7424052162999058433-Phip

The video presentation is in Portuguese.  
YouTube automatically provides AI-based audio translation for English viewers.

---

## ⚙️ Installation & Setup | Instalação e Execução

### Clone the repository
git clone https://github.com/JessePMelo/Telco-Customer-Churn.git  
cd Telco-Customer-Churn

### Create and activate a virtual environment
python -m venv venv  
source venv/bin/activate   # Linux/Mac  
venv\Scripts\activate      # Windows

### Install dependencies
pip install -r requirements.txt

---

## ☁️ Running on Google Colab | Rodando no Google Colab

1. Open Google Colab
2. Upload the notebooks
3. Install dependencies:
!pip install pandas numpy scikit-learn matplotlib shap statsmodels

---

## 📦 Requirements | Dependências

pandas  
numpy  
scikit-learn  
matplotlib  
shap  
statsmodels  

---

## 🚀 Why This Project Matters | Por Que Este Projeto Importa

- Real-world business problem
- Strong focus on explainability
- Combines statistics and machine learning
- Portfolio-ready and recruiter-friendly
- Clear communication of results

This project demonstrates the complete lifecycle of a data science solution, from problem formulation to interpretable results and business insights.

---

## 👤 Author | Autor

**Jessé Pereira de Melo**  
Data Science | Machine Learning | Business Intelligence  

GitHub: https://github.com/JessePMelo  
LinkedIn: https://www.linkedin.com/in/jessepmelo/

---

## 📜 License | Licença

This project is intended for educational and portfolio purposes.
