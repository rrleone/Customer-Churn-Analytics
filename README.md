# 📊 Customer Churn Analytics

## 🎯 Problema de negócio

A análise busca entender o comportamento de churn dos clientes e identificar os principais segmentos associados ao cancelamento.

O objetivo é transformar os dados de clientes em informações que apoiem decisões de retenção, identificação de perfis de risco e acompanhamento dos principais indicadores de churn.

---

## 🗂️ Sobre os dados

- **Fonte:** Dataset público de Customer Churn — Kaggle
- **Tamanho:** 7.043 clientes e 19 variáveis
- **Tipo de análise:** Customer Churn / Customer Retention
- **Unidade de análise:** cliente

### Principais informações analisadas

- Perfil dos clientes
- Partner e Dependents
- Tenure
- Tipo de contrato
- Serviços de internet
- Serviços adicionais
- Monthly Charges
- Total Charges
- Forma de pagamento
- Status de Churn

---

## 🛠️ Ferramentas utilizadas

- **Python**
- **Pandas / NumPy**
- **Jupyter Notebook**
- **Matplotlib / Seaborn**
- **Power Query**
- **Power BI**
- **DAX**
- **Git / GitHub**

---

## 🔍 Etapas da análise

1. **Data Profiling** — entendimento da estrutura, dimensões, tipos e características das variáveis.
2. **Data Cleaning** — tratamento e preparação dos dados para análise.
3. **Análise Exploratória (EDA)** — investigação do comportamento de churn segundo perfil, tenure, contrato, serviços e forma de pagamento.
4. **Feature Engineering** — criação de agrupamentos e variáveis analíticas, incluindo faixas de tenure e perfil de risco.
5. **Modeling** — desenvolvimento das análises e modelos relacionados ao comportamento de churn.
6. **Model Evaluation** — avaliação dos resultados obtidos.
7. **Business Insights** — transformação dos resultados em informações relevantes para retenção de clientes.
8. **Power BI Dashboard** — construção de dashboard executivo com três páginas de análise.

---

## 📈 Principais insights

- **26,54%** dos clientes da base apresentam churn.
- Clientes com contrato **Month-to-month** apresentam taxa de churn de **42,7%**.
- Clientes com **0–12 meses** de relacionamento apresentam taxa de churn de **47,4%**.
- Clientes com serviço de internet **Fiber optic** apresentam taxa de churn de **41,9%**.
- **Electronic check** apresenta a maior taxa de churn entre as formas de pagamento analisadas, com **45,29%**.
- Clientes classificados como **Senior Citizen** apresentam taxa de churn de **41,7%**, contra **23,6%** entre os demais clientes.
- Clientes **sem dependents** apresentam taxa de churn de **31,28%**, enquanto clientes com dependents apresentam **15,45%**.

Os resultados representam associações observadas na base analisada e não implicam, isoladamente, relação de causalidade.

---

## 🖼️ Prévia do dashboard

O projeto possui três páginas no Power BI:

### 01 — Executive Overview

Visão executiva dos principais KPIs e indicadores associados ao churn.

### 02 — Customer Profile & Churn Drivers

Análise do perfil dos clientes e dos principais fatores associados ao churn.

### 03 — Churn Risk & Customer Segmentation

Análise de risco, segmentação de clientes e visualização do perfil dos clientes.

A capa do projeto está disponível em `images/Customer_Churn_Analytics_Capa.png`.

---

## ✅ Conclusão e recomendação

A análise indica concentração de churn em determinados segmentos, especialmente entre clientes com contratos Month-to-month, menor tempo de relacionamento e determinados serviços e formas de pagamento.

Como oportunidade de negócio, esses segmentos podem ser utilizados como base para estratégias de retenção e acompanhamento direcionado, com posterior validação dos resultados das ações implementadas.

---

## 📁 Estrutura do repositório

```text
Customer-Churn-Analytics/
│
├── data/
│   ├── raw/
│   │   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│   │
│   └── processed/
│       └── customer_churn_clean.csv
│
├── images/
│   └── Customer_Churn_Analytics_Capa.png
│
├── notebooks/
│   ├── 01_data_profiling.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_eda_churn.ipynb
│   ├── 04_feature_engineering.ipynb
│   ├── 05_modeling.ipynb
│   └── 06_model_evaluation.ipynb
│
└── README.md
```

---

## 🚀 Como reproduzir

Clone o repositório:

```bash
git clone https://github.com/rrleone/Customer-Churn-Analytics.git
cd Customer-Churn-Analytics
```

Abra os notebooks na ordem indicada em `notebooks/` e execute as etapas da análise.

O dashboard pode ser aberto no Power BI Desktop quando o arquivo `.pbix` estiver disponível no projeto.

---

## 👤 Autor

**Renato Leone**

Analista de Dados | BI | Power BI | Python

GitHub: https://github.com/rrleone
