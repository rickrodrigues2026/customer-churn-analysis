# Customer Churn Analysis

**Transforming customer data into actionable retention insights through exploratory data analysis.**

---

## 🎯 The Impact

This project analyzes customer churn patterns to identify the key factors driving cancellations. By combining statistical analysis with data visualization, I discovered:

- **Churn reduction pathway**: 56.7% → 46.1% → 18.4%
- **Key finding**: Specific customer behaviors and demographics directly correlate with retention
- **Actionable insights**: Identified retention levers that can reduce cancellation risk by up to 70%

> **Why this matters**: Understanding *why* customers leave is more valuable than knowing *how many* leave. This analysis enables data-driven retention strategies.

---

## 📊 Project Overview

An exploratory data analysis (EDA) project that investigates customer churn through:

- **Statistical analysis** of churn rates across customer segments
- **Comparative analysis** of churned vs. retained customer characteristics
- **Pattern visualization** to reveal non-obvious retention factors
- **Data-driven recommendations** for reducing customer cancellation

---

## 🗂️ Repository Structure

```
.
├── README.md                      # This file
├── requirements.txt               # Python dependencies
├── data/
│   └── churn.csv                 # Customer churn dataset
└── notebooks/
    ├── 01_starter.ipynb          # Starter notebook (exercise template)
    └── 02_solution.ipynb         # Complete analysis with findings
```

---

## 🚀 Quick Start

### Prerequisites
- Python 3.8+
- pip or conda

### Installation & Setup

```bash
# Clone the repository
git clone https://github.com/rickrodrigues2026/customer-churn-analysis.git
cd customer-churn-analysis

# Install dependencies
pip install -r requirements.txt

# Open Jupyter Notebook
jupyter notebook
```

Then open `notebooks/02_solution.ipynb` to view the complete analysis.

---

## 📈 Key Findings

The analysis reveals that churn is not random — it correlates strongly with:

1. **Customer lifecycle stage** — early-stage customers have higher churn risk
2. **Contract type** — month-to-month contracts show higher cancellation rates
3. **Service adoption** — customers using fewer services are more likely to churn
4. **Tenure patterns** — there are critical points where retention drops

These insights directly inform customer success strategies and proactive retention campaigns.

---

## 📁 Notebooks

- **`01_starter.ipynb`** — Template for exploratory analysis (exercise version)
- **`02_solution.ipynb`** — Full analysis with visualizations and statistical insights

Both notebooks use the same dataset and build on each other. Start with the starter version to practice your EDA skills, then compare with the solution.

---

## 📊 Dataset

- **File**: `data/churn.csv`
- **Records**: Customer profiles with churn status and behavioral metrics
- **Features**: Demographics, service usage, contract terms, and churn indicator

---

## 🛠️ Technologies

- **Python 3.x** — Data processing and analysis
- **Pandas** — Data manipulation and exploration
- **Plotly** — Interactive visualizations
- **Jupyter Notebook** — Analysis environment

---

## 💡 What You'll Learn

- How to approach exploratory data analysis systematically
- Techniques for identifying churn risk factors
- Data visualization best practices for stakeholder communication
- Statistical reasoning applied to business problems

---

## 📚 Original Course

This project is based on the course data from **Python Insights** by Alura.

Original course files available [here](https://drive.google.com/drive/folders/1uDesZePdkhiraJmiyeZ-w5tfc8XsNYFZ?usp=drive_link) (if needed for reference).

---

## 📝 License

This project is provided as-is for portfolio and educational purposes.

---

## 👤 Author

**Rick Rodrigues** — Data analyst passionate about turning data into decisions.

Connect: [LinkedIn](https://linkedin.com/in/rickrodrigues2026) | [GitHub](https://github.com/rickrodrigues2026)

---

## ✨ Next Steps (Potential Improvements)

- [ ] Add predictive churn model (classification)
- [ ] Build interactive dashboard with Streamlit
- [ ] Implement retention score formula
- [ ] A/B testing analysis for retention strategies
