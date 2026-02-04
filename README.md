# Alliances Under Pressure: What World Wars Did to Global Commitments

*A Visual and Network Analysis of Alliance Evolution (1816–2012)*

## 📖 Description
This project examines how international alliance systems evolved over the long run and how major systemic conflicts—especially World War I and World War II—reshaped the depth of alliance commitments. Using historical data from the Correlates of War (COW) project, the analysis moves beyond simple alliance counts to study commitment structures and network architecture.

## ❓ Research Questions
- Long-Term Growth of Alliance Networks.
- Did World Wars push states toward low-commitment agreements (ententes and non-aggression pacts) over high-commitment defense treaties?

## 📂 Repository Structure
```
├── Datasets/
│   └── Correlates of War (COW) formal alliance datasets
├── Visualizations/
│   └── Figures used as empirical evidence
├── Exploratory_Data_Analysis.ipynb
│   └── Full data cleaning, analysis, and visualization pipeline
├── Final_Report.pdf
│   └── Final written report and interpretations
└── README.md
```

## 📊 Data Source
**Correlates of War – Formal Alliance Dataset (v4.1)**  
[https://correlatesofwar.org/data-sets/formal-alliances/](https://correlatesofwar.org/data-sets/formal-alliances/)

The dataset covers 1816–2012 and classifies alliances into defense pacts, ententes, non-aggression treaties, and neutrality agreements.

## 🔬 Methodology Overview
- **Data Preparation**: Cleaning, filtering, and aggregation of dyad-year alliance data
- **Temporal Analysis**: Long-term trends and historical period comparisons
- **Commitment Analysis**: Shifts between high- and low-commitment alliances during wars
- **Network Analysis**: Structural comparison of NATO and Warsaw Pact alliance systems

## 📈 Key Findings
- Formal alliances expanded steadily over time, especially after World War II.
- World Wars caused sharp, temporary shifts toward low-commitment alliances.
- NATO's Cold War network was dense and decentralized, reflecting collective security.
- The Warsaw Pact exhibited a centralized, core–periphery structure dominated by the Soviet Union.

## 🔁 Reproducibility
All figures and results can be reproduced by running `Exploratory_Data_Analysis.ipynb` using the datasets in the `Datasets/` folder. Visual outputs used in the report are saved in `Visualizations/`.

## 📋 Requirements
- Python 3.7+
- Libraries: pandas, matplotlib, plotly, seaborn, networkx
- Jupyter Notebook

Install dependencies:
```bash
pip install pandas matplotlib plotly seaborn networkx jupyter
```

## 🚀 Usage
1. Clone the repository.
2. Ensure datasets are in `Datasets/`.
3. Open `Exploratory_Data_Analysis.ipynb` in Jupyter.
4. Run all cells to reproduce the analysis.

## 🧾 Summary
By combining time-series analysis with network visualization, this project shows that systemic shocks reshape not only the size of alliance networks but the level of commitment states are willing to make—directly supporting the project's central research question.
