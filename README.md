## The Evolution of Energy Aid Discourse: Insights from Structural Topic Modelling

This repository contains the code, outputs, and visualizations for my Master’s Thesis, which applies Structural Topic Modeling (STM) to project-level data on Official Development Assistance (ODA) in the energy sector.


## Repository Contents

| File | Description |
|------|-------------|
| `01_txt_to_csv_and_merge.ipynb` | Raw text conversion and dataset merge for all 10 years |
| `02_add_continents_and_clean.ipynb` | Data cleaning |
| `03_remove_french_translate_ipynb.ipynb` | Detect and translate project descriptions, remove French text if necessary |
| `04_preprocessing_nlp.ipynb` | NLP pre-processing |
| `05_STM.Rmd` | STM modeling and visual output |
| `doc_topic_distribution_20_eng.csv` | Topic proportions per project |
| `topic_labels_20_eng.csv` | Final 20 topics with keywords |
| `*.png` | Visualizations (e.g., model selection, ridge plots, regional trends) |
| `satam_manjiri_master_thesis.pdf` | Final version of master thesis |

## Methodology

- **Data**: OECD CRS project-level data (energy sector, 2014–2023) [Access/download the raw data](https://data-explorer.oecd.org/vis?fs[0]=Topic%2C1%7CDevelopment%23DEV%23%7COfficial%20Development%20Assistance%20%28ODA%29%23DEV_ODA%23&pg=0&fc=Topic&bp=true&snb=25&df[ds]=dsDisseminateFinalCloud&df[id]=DSD_CRS%40DF_CRS&df[ag]=OECD.DCD.FSD&df[vs]=1.3&dq=DAC..1000.100._T._T.D.Q._T..&to[TIME_PERIOD]=false&lom=LASTNPERIODS&lo=5)
- **Approach**: Structural Topic Modeling with covariates:
  - Region
  - Year
  - Climate objective (mitigation/adaptation)
- **Tools**: Python (preprocessing), R (`stm`) for modeling



## Author
Manjiri Satam \
Master's in Data Science for Public Policy, Hertie School, 2025

