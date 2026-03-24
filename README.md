# Supervised AI Project

This repository contains exercise materials and notebooks for a supervised Machine Learning workshop.

## Folder structure

- `data/`
  - `bronze/`: raw data or initial ingestion stage
  - `silver/`: intermediate cleaned data
  - `gold/`: final data ready for analysis and modeling
    - `duplicated_rows.csv`
    - `metadata.csv`
    - `quality_data_filtered.csv`
    - `quality_data.csv`

- `docs/`
  - `MIAX ML - 03_05 Workshop Part 1 of 2.ipynb`
  - `MIAX ML - 09_05 Workshop Part 2 of 2.ipynb`

- `src/`
  - `cleaning_data.ipynb`
  - `preprocessing_data.ipynb`

- `requirements.txt`: Python dependencies for the project.

## Goal

Explore the typical workflow of a supervised Machine Learning project:

1. Data ingestion and cleaning (`data/bronze`, `data/silver`, and `src/cleaning_data.ipynb`)
2. Data preprocessing (`src/preprocessing_data.ipynb`)
3. Exploratory analysis and modeling (`data/gold/` and notebooks in `docs/`)

## How to use

1. Create a Python environment (recommended: `venv` or `conda`).
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the notebooks in `src/` and `docs/` with Jupyter.

4. Review results in `data/gold/`.

## Notes

- The notebooks are the main learning artifacts, including steps for cleaning, preprocessing, and experimentation.
- Adjust input/output paths as needed if your data is stored elsewhere.

