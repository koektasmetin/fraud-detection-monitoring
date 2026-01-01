\# Fraud Detection Monitoring (PaySim)



Notebook project: EDA + baseline model + monitoring-style analysis (rolling metrics, alert rate, score drift).



\## Structure

\- `notebooks/` : analysis notebooks

\- `reports/figures/` : exported plots

\- `src/` : reusable code (if applicable)

\- `data/` : ignored large datasets (see below)



\## Dataset

PaySim CSV is not included in the repo (GitHub file size limit).  

Place the dataset locally in `data/raw/` and update notebook paths if needed.



\## How to run

```bash

python -m venv .venv

\# activate venv

pip install -r requirements.txt



