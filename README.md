# Phishing Baseline — OneSecurity

This repository contains an end-to-end lab for Phishing detection using a RandomForest baseline.

Files:
- notebooks/phishing_baseline.ipynb — Colab-ready notebook (end-to-end)
- data/sample/phishing_sample.csv — small sample CSV for quick tests
- requirements.txt — recommended package versions

Quick start:
1. Create a new GitHub repository (e.g., `anesra/phishing-baseline`) and add the files above using the web UI or git commands.
2. Open the notebook in Colab:
   https://colab.research.google.com/github/anesra/phishing-baseline/blob/main/notebooks/phishing_baseline.ipynb
   (Replace 'anesra' with your GitHub username if different.)
3. In Colab, run the first cell to install dependencies, then run the notebook cells in order. If you have your own CSV, upload it to `/content/phishing.csv` before running the data loading cell.

Notes:
- For the full Kaggle dataset, use the Kaggle API in Colab (requires uploading your `kaggle.json`) or download manually and upload to Colab.
- DO NOT visit suspicious URLs from datasets on an unprotected machine. Use only URLs as strings when possible and avoid opening landing pages unless in a sandbox.
