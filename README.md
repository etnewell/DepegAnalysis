# Stablecoin Depeg Analysis

Small utilities to fetch stablecoin price history, compute deviation from peg, and visualize results.

Quickstart:

Install dependencies:
```bash
python -m pip install -r requirements.txt
```

Run CLI example:
```bash
python -m depeg.cli --token tether --days 90 --out tether_deviation.png
```

Or open `stablecoin_depeg_analysis.ipynb` for an interactive analysis.
# DepegAnalysis