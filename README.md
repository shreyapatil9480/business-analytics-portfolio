# Business Analytics Portfolio

What inventory conditions cause stockouts?

**Stakeholder:** Inventory Planner

## Key Insights

- Lead times above 14 days raise stockout risk when variability is high.
- Safety stock under 50 units fails for volatile SKUs.
- Demand variability above 0.35 overwhelms default replenishment rules.

## Dataset

Primary file: `data/inventory_stockouts.csv`  
Target variable: `stockout`

## Getting Started

```bash
pip install -r requirements.txt
jupyter notebook notebooks/eda.ipynb
```


## Next Steps

**Done.** Weekly stakeholder report automation is implemented — see ### Implemented below.

---
*Analytics portfolio project — 2025-08*

<!-- build 5 -->

### Implemented

```bash
pip install -r requirements.txt
python scripts/weekly_report.py
```
### Report output

After running `python scripts/weekly_report.py`, open `reports/weekly_summary.html` for the stakeholder summary.

