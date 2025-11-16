# ☀️ Análise Energética do Palácio do Planalto com Energia Solar (FIAP - Global Solution)

Este repositório apresenta a **Global Solution** do curso de **Ciência da Computação - FIAP**, na matéria de **Soluções de Energias Renováveis e Sustentáveis**.  
Analisamos o **consumo e gasto energético oficial do Palácio do Planalto (2023–2025)** e propomos uma **solução realista de energia solar fotovoltaica on-grid** nos Anexos — o local de maior consumo.

> **Dados reais + Python + Sustentabilidade = Economia de R$1,9M/ano + 78t CO₂ evitadas**

---

## 🚀 Funcionalidades

* **Análise completa de consumo e gasto** (2023 a outubro/2025)
* **Visualizações interativas**:
  - Gráficos de linha mensal
  - Heatmap de consumo médio
  - Boxplot de sazonalidade
  - Barras por local
* **Predição de novembro e dezembro 2025** com tendência histórica
* **Simulação técnica de sistema solar**:
  - Dimensionamento: **2.728 painéis** | **1.091 kWp**
  - Irradiação via **CRESESB (5,8 kWh/m²/dia)**
  - Cobertura parcial de **50%** (respeitando patrimônio)
* **Cálculo de ROI**:
  - Investimento: **R$ 2,7 milhões**
  - Economia anual: **R$ 1,9 milhão**
  - **Payback: 1 ano e 5 meses**
* **Impacto ambiental**: **-78,5 toneladas de CO₂/ano**

---

## 🛠️ Tecnologias

| Ferramenta | Uso |
|----------|-----|
| **Python 3.10+** | Análise e modelagem |
| **Pandas** | Tratamento de dados |
| **Matplotlib + Seaborn** | Visualizações |
| **NumPy** | Cálculos solares |
| **Jupyter Notebook / Google Colab** | Desenvolvimento interativo |
| **CSV (dados.gov.br)** | Fonte oficial |
| **CRESESB / Atlas Solarimétrico** | Irradiação solar |

---

## 📦 Pré-requisitos para Executar

* **Python 3.8+** ou **Google Colab** (recomendado)
* Bibliotecas:
  ```bash
  pip install pandas numpy matplotlib seaborn
