# 🏢 PL01 Condominium Data Analysis

This repository contains data analysis and visualization notebooks for condominium management data.  
It includes data cleaning, exploratory data analysis (EDA), and visual insights on various aspects such as occurrences, maintenance, payments, and repairs.

---

## 📚 Project Overview

The main objectives of this project are to:
- Clean and preprocess multiple condominium-related datasets.
- Perform exploratory data analysis (EDA) to uncover trends and patterns.
- Generate visual insights to support management decisions.

---

## 📂 Repository Contents

| File | Description |
|------|--------------|
| **PL01.ipynb** | Main notebook integrating the overall data analysis. |
| **tratamento_e_eda_condominios.ipynb** | Data cleaning and EDA for condominium units. |
| **tratamento_ocorrencias.ipynb** | Processing and analysis of occurrences and complaints. |
| **pagamentos_e_eda_cleaned.ipynb** | Analysis of payments and quotas data. |
| **eda_ocorrencias.ipynb** | Exploratory analysis of occurrences dataset. |
| **Analise_Visual_Insights.ipynb** | Visualization and insights dashboard for all datasets. |
| **condominios_fracoes.csv** | Condominium units and fractional data. |
| **ocorrencias_reclamacoes.csv** | Registered occurrences and complaints data. |
| **manutencoes_reparacoes.csv** | Maintenance and repair records. |
| **pagamentos_quotas.csv** | Payments and quotas data. |

---

## ⚙️ Setup Instructions

To run this project locally:

```bash
# 1️⃣ Create a virtual environment
python -m venv env

# 2️⃣ Activate it
# Windows:
env\Scripts\activate
# macOS/Linux:
source env/bin/activate

# 3️⃣ Install dependencies
pip install -r requirements.txt

# 4️⃣ Launch Jupyter Notebook
jupyter notebook
