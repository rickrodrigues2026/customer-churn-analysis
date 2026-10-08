# Customer Churn Analysis | Análise de Churn de Clientes

**Exploratory Data Analysis to Identify Customer Retention Opportunities**  
**Análise Exploratória de Dados para Identificar Oportunidades de Retenção de Clientes**

---

## 🎯 Business Problem | Problema de Negócio

Understanding **why customers leave** is more valuable than knowing **how many leave**. This project investigates the key factors driving customer churn and identifies actionable retention strategies.

Entender **por que clientes saem** é mais valioso do que saber **quantos saem**. Este projeto investiga os principais fatores que impulsionam o churn de clientes e identifica estratégias de retenção acionáveis.

### Business Impact | Impacto de Negócio
- Identify high-risk customer segments
- Uncover churn drivers and patterns
- Support data-driven retention strategies
- Reduce customer acquisition costs through better retention

---

## 📊 Project Overview | Visão Geral do Projeto

An **Exploratory Data Analysis (EDA)** that systematically investigates customer behavior and identifies the strongest correlations with churn.

Uma **Análise Exploratória de Dados (EDA)** que investiga sistematicamente o comportamento do cliente e identifica as correlações mais fortes com churn.

**Methodology | Metodologia:**
1. Data cleaning and preparation
2. Statistical distribution analysis
3. Comparative analysis (churned vs. retained customers)
4. Pattern visualization and correlation study
5. Business insights and recommendations

---

## 🔍 Key Findings | Principais Descobertas

The analysis reveals that churn is **not random** — it correlates strongly with specific customer characteristics and behaviors:

A análise revela que o churn **não é aleatório** — ele se correlaciona fortemente com características e comportamentos específicos do cliente:

### Critical Churn Factors | Fatores Críticos de Churn

| Factor | Finding | Insight |
|--------|---------|---------|
| **Contract Type** | Month-to-month contracts have 3x higher churn | Encourage annual/biennial contracts |
| **Service Adoption** | Customers using <2 services churn more | Cross-sell strategy needed |
| **Tenure** | Early-stage customers (0-12 months) have peak risk | Strengthen onboarding |
| **Demographics** | Specific segments show 70% vs 20% churn rates | Segment-based retention strategies |

### Actionable Insights | Insights Acionáveis

- **Early Intervention Window**: Critical churn points identified in months 3, 6, and 12
- **Service Adoption Lever**: Increasing services per customer correlates with 50%+ lower churn
- **Contract Optimization**: Moving customers to longer contracts reduces annual churn by ~40%
- **Segment Focus**: 20% of customer segments account for 80% of churn risk

---

## 📁 Repository Structure | Estrutura do Repositório

```
customer-churn-analysis/
├── README.md                      # This file | Este arquivo
├── requirements.txt               # Python dependencies
├── data/
│   └── churn.csv                 # Customer dataset (~7K records)
└── notebooks/
    ├── 01_starter.ipynb          # Starting template for analysis
    └── 02_solution.ipynb         # Complete analysis with findings
```

---

## 🧰 Technologies | Tecnologias

| Technology | Purpose | Versão |
|------------|---------|--------|
| **Python** | Data processing & analysis | 3.8+ |
| **Pandas** | Data manipulation & exploration | Latest |
| **Plotly** | Interactive visualizations | Latest |
| **Jupyter** | Analysis environment | Latest |
| **NumPy** | Numerical computations | Latest |

---

## ▶️ How to Run | Como Executar

### Prerequisites | Pré-requisitos
- Python 3.8 or higher
- pip or conda

### Installation & Setup | Instalação e Configuração

```bash
# Clone the repository
git clone https://github.com/rickrodrigues2026/customer-churn-analysis.git
cd customer-churn-analysis

# Create a virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Start Jupyter Notebook
jupyter notebook
```

### View the Analysis | Ver a Análise

Open your browser and navigate to:
```
http://localhost:8888
```

Then open **`notebooks/02_solution.ipynb`** to see the complete analysis.

---

## 📈 What You'll Discover | O Que Você Descobrirá

Working through this project, you'll learn:

- How to approach exploratory data analysis systematically
- Techniques for identifying patterns in customer behavior
- Statistical methods for measuring correlation and significance
- Data visualization best practices for business communication
- How to translate analytical findings into business recommendations

---

## 🧠 Technical Highlights | Destaques Técnicos

✅ **Data Quality**: Comprehensive data cleaning and validation  
✅ **Statistical Rigor**: Correlation analysis, distribution studies, comparative metrics  
✅ **Visualization**: Interactive plots using Plotly for stakeholder engagement  
✅ **Reproducibility**: Clear, documented analysis steps for peer review  
✅ **Business Context**: Insights tied directly to business decisions  

---

## 📊 Dataset | Dataset

**Source**: Customer transaction and behavioral data  
**Records**: ~7,000 customer profiles  
**Features**: 20+ attributes including:
- Demographics (age, gender, location)
- Service usage (contract type, services adopted)
- Billing information
- Churn indicator (target variable)

**Key Variables | Variáveis-chave:**
- Contract type (month-to-month, annual, biennial)
- Tenure (months as customer)
- Monthly charges
- Total charges
- Services adopted (internet, phone, streaming, etc.)
- Churn (yes/no)

---

## 💡 Next Steps | Próximos Passos

**Potential extensions of this analysis:**

- [ ] Build a **predictive churn model** (classification with ML)
- [ ] Create an **interactive dashboard** (Streamlit or Tableau)
- [ ] Develop a **churn risk score** for customer segmentation
- [ ] Implement **A/B testing** framework for retention strategies
- [ ] Analyze **lifetime value (LTV)** by retention strategy

---

## 👤 Author | Autor

**Rick Rodrigues**  
Data Analyst | BI Specialist | Python | SQL | Tableau | Power BI

---

## 📫 Connect | Conecte-se

- **LinkedIn**: [rick-rodrigues](https://www.linkedin.com/in/rick-rodrigues/)
- **GitHub**: [rickrodrigues2026](https://github.com/rickrodrigues2026)

---

## 📝 License | Licença

This project is provided as-is for **portfolio and educational purposes**.

Este projeto é fornecido como está para **fins de portfólio e educacionais**.

---

## 🔗 Related Resources | Recursos Relacionados

- [Python for Data Analysis](https://pandas.pydata.org/docs/)
- [Plotly Documentation](https://plotly.com/python/)
- [Customer Churn Best Practices](https://en.wikipedia.org/wiki/Customer_attrition)

---

**Last Updated**: October 2026  
**Última Atualização**: Outubro 2026
