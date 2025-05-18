# EcoSound Festival Travel Analysis

Data-driven study of travel emissions for the EcoSound Festival at Heaton Park, Manchester. Recognized by the UK Government, this project uses Power BI for preprocessing & visualization and R/XGBoost for predictive modeling to recommend low-carbon travel options.

## 🚀 Features
- Cleaned & merged master dataset (`data/Cleaned_master_dataset.csv`)
- Power BI report (`visuals/DigData_new.pbix`)
- Predictive R script (`analysis/predict_emissions.R`)
- Presentation slides (`slides/DigData Final.pptx`)

## 📂 Repository Structure

```
├── analysis/
│ └── predict_emissions.R # XGBoost model training & evaluation
├── data/
│ └── Cleaned_master_dataset.csv
├── visuals/
│ └── DigData_new.pbix
├── slides/
│ └── DigData Final.pptx
└── README.md
```

## 🛠 Requirements
- **Power BI Desktop** (to open `.pbix` file)
- **R** ≥ 4.0 with packages: `xgboost`, `tidyverse`, `caret`
- **Git** (to clone this repo)

## 🚩 Usage

1. **Data & Visualization**  
   - Open `visuals/DigData_new.pbix` in Power BI to explore dashboards and measures.
<img width="747" alt="Screenshot 2025-05-18 at 3 34 52 PM" src="https://github.com/user-attachments/assets/a6e3f17e-758c-4781-bc1c-8891691696df" />


2. **Predictive Modeling**  
   ```bash
   Rscript analysis/predict_emissions.R \
     --input data/Cleaned_master_dataset.csv \
     --output analysis/results/
   
##Presentation

Review slides in slides/DigData Final.pptx for methodology, results, and recommendations.

## 📈 Key Insights
Greenest modes: EVs, buses, trains—cut 12.75 M kg CO₂

Optimal timing: Weekday off-peak & sunny conditions

Target audience: Incentivize 18–34-year-olds for maximum impact

## 🤝 Contributing
Contributions are welcome! Please open an issue or pull request for data corrections, code improvements, or new visualizations.
