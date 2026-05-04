# 2024_Vintage_Pinot
# Pinot Noir Fermentation Analysis (2024)

## Overview
This repository contains a Jupyter notebook for analyzing chemical and sensory outcomes of Pinot noir wines produced under different malolactic fermentation strategies.

The analysis integrates:
- Chemical measurements (color, phenolics, volatile acidity)
- GC–MS volatilome profiling
- Sensory evaluation (RATA and color triangle)

---

## Notebook
`24pinot_github_ready.ipynb`

Run all cells sequentially.

---

## Required Data Files
Place the following files in `/data/`:

- brix_Pinot24_master.xlsx  
- Napping data_2.12.26_NM_consumer.xlsx  
- Consumer_RATA_10.2025.xlsx  
- Owri winemakers panel.xlsx  
- 2024PinotGC.xlsx  

---

## Outputs
Results are written to `/outputs/`:

- `figures/` → plots (PCA, triangle plots, etc.)
- `tables/` → CSV outputs
- `reports/` → statistical summaries (.txt)

---

## Key Settings

In the global controls cell:

```python
PANEL_MODE = "consumer"  # or "winemaker"
