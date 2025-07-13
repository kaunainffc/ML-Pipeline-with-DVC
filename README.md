# ML Pipeline with DVC 

An end-to-end machine learning project built with reproducible pipelines using DVC.

## 📂 Project Structure
- `src/` – Contains scripts for data ingestion, model training, evaluation
- `data/` – Raw and processed datasets (DVC tracked)
- `dvc.yaml` – Defines pipeline stages
- `dvc.lock` – Captures exact inputs/outputs for reproducibility

## Tech Stack
Python, DVC, Scikit-learn, Pandas, NumPy, Git

## 🛠 How to Reproduce
```bash
git clone https://github.com/kaunainffc/ML-Pipeline-with-DVC.git
cd ML-Pipeline-with-DVC
dvc pull
dvc repro
