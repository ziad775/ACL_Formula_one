# Formula 1 Podium Prediction — Milestone 1

Predicting whether a Formula 1 driver finishes on the podium (top 3), using only information
available after qualifying and before the race starts.

## Links
- Kaggle notebook: <add link>
- Report (PDF): `report/` folder

## Dataset
[Formula 1 World Championship (1950–2024)](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020)
— 14 relational CSV tables (Kaggle / Ergast).

The data is **not** committed to this repo. To run locally, download the dataset and place the
14 CSV files in a `data/` folder at the repo root. On Kaggle, add the dataset as an input; the
notebook finds it automatically.

## How to run
```bash
pip install -r requirements.txt
jupyter notebook f1_podium_prediction.ipynb   # then Kernel → Restart & Run All
```

## Repository structure
```
├── f1_podium_prediction.ipynb   # the single run-all notebook
├── report/                      # final PDF report
├── data/                        # raw CSVs (git-ignored)
├── requirements.txt
└── README.md
```

## Notebook sections
0. Setup · 1. Raw EDA · 2. Cleaning & Auditing · 3. Post-cleaning EDA · 4. Data-Engineering Questions ·
5. Features · 6. Split · 7. Pre-processing · 8. Modeling · 9. Ablation · 10. XAI · 11. Inference · 12. Summary

## Team
| Name | Main responsibility |
|------|---------------------|
|   ziad walid   |                     |
