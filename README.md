# Seasonal Agriculture Performance Analysis

**VOIS AICTE Batch 1 • 2026–2027**

A data analytics project exploring how agricultural performance changes across **Kharif, Rabi and Zaid** seasons. The analysis focuses on seasonal patterns in yield, profitability, environmental conditions, irrigation/resource use and crop performance.

## Project objective

The project investigates meaningful patterns, trends, relationships and differences in agricultural performance across seasons. It also compares relevant groups and develops evidence-based observations and recommendations.

## Dataset

The supplied dataset contains **4,000 rows and 28 columns** covering farms, locations, crops, seasons, environmental conditions, farm inputs, irrigation, yield, production, market price, costs, revenue, profit, water use and disease/pest risk.

Main analytical fields include:

- `Season`
- `Crop`
- `Rainfall_mm`
- `Avg_Temperature_C`
- `Humidity_pct`
- `Irrigation_Method`
- `Yield_Tonnes_Ha`
- `Production_Tonnes`
- `Market_Price_INR_Tonne`
- `Total_Cost_INR`
- `Revenue_INR`
- `Profit_INR`
- `Water_Used_m3`
- `Water_Efficiency_t_per_1000m3`
- `Disease_Pest_Risk_pct`

## Key findings from the supplied data

- **Kharif** has the highest mean yield (**5.64 tonnes/ha**) and the highest mean profit (**INR 178,915**).
- **Rabi** has a lower mean yield (**5.08 tonnes/ha**) and mean profit (**INR 87,689**).
- **Zaid** has the lowest mean yield (**4.67 tonnes/ha**) and a negative mean profit (**-INR 24,805**).
- Among irrigation methods, **Drip** has the highest mean yield (**6.62 tonnes/ha**) and mean profit (**INR 219,626**).
- **Rainfed** has the highest mean water-efficiency metric (**7.56 tonnes per 1,000 m³**) and the lowest average water use (**3,550 m³**).
- **Flood** has the highest average water use (**8,026 m³**) among the four irrigation methods.
- The strongest positive numerical association with `Profit_INR` is `Revenue_INR` (**0.887**), followed by `Production_Tonnes` (**0.554**) and `Yield_Tonnes_Ha` (**0.490**).
- The dataset contains **120 missing cells** and **no duplicate rows**.

These findings are descriptive associations from the supplied dataset and should not be interpreted as causal effects without further statistical testing.

## Repository structure

```text
Seasonal_Agriculture_Performance_Analysis/
├── data/
│   └── seasonal_agriculture_performance_dataset.csv
├── notebooks/
│   └── Seasonal_Agriculture_Performance_Analysis.ipynb
├── presentation/
│   └── Seasonal_Agriculture_Performance_Analysis_Final.pptx
├── docs/
│   └── Project_Brief.pdf
├── requirements.txt
└── README.md
```

## How to run

1. Clone or download the repository.
2. Install the dependencies:

```bash
pip install -r requirements.txt
```

3. Open `notebooks/Seasonal_Agriculture_Performance_Analysis.ipynb` in Jupyter Notebook, JupyterLab or VS Code.
4. Run the cells from top to bottom.

## Tools used

Python, Pandas, NumPy, Matplotlib and Jupyter Notebook.

## Project deliverables

The repository includes the analysis notebook, source dataset, final presentation and the supplied project brief.
