# Previsão de Churn em Telecomunicações

Este projeto utiliza Machine Learning para prever o cancelamento de clientes (Churn). A análise foca não apenas na acurácia, mas na otimização do **Recall** para garantir que a empresa identifique o maior número possível de clientes em risco.

## 🚀 Estrutura de Modelagem

### Fase 1: Baseline (Regressão Logística)
Nesta etapa, estabelecemos um ponto de partida simples e interpretável.
* **Destaque Técnico:** Identificação de multicolinearidade entre `TotalCharges`, `Tenure` e `MonthlyCharges`.
* **Ajuste de Negócio:** Alteração do threshold de decisão para **0.35**, elevando o Recall para **73%**.
* **Insight:** Clientes que optam por uma gama maior de serviços são os principais alvos de evasão.

### Fase 2: Modelo Final (Em desenvolvimento)
-

## 🛠️ Tecnologias Utilizadas
* Python, Pandas, Scikit-Learn, Matplotlib e Seaborn.

## 📊 Principais Insights
* O tempo de contrato (`tenure`) é o maior retentor de clientes.
* O público mais tecnologicamente ativo é menos leal
