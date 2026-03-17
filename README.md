# DAS-Group-13
DAS Project 2 for Group 13 - Coffee Quality Database (CQD) dataset

## Project overview
We analyse the Coffee Quality Database (CQD) dataset to understand which coffee features influence whether a batch is classified as **Good (>= 82.5)** or **Poor (< 82.5)**.

**Question of interest:**  
What influence do different features of coffee have on whether the quality of a batch of coffee is classified as good or poor?

## Data
- Dataset: `data/dataset13.csv` (from Moodle, allocated to Group 13)
- Outcome variable: `Qualityclass` (Good >= 82.5, Poor < 82.5)
- Unit of observation: coffee batch
  
## Repository structure
- `data/dataset13.csv` — CQD dataset
- `Group_13_Analysis.qmd` — Quarto analysis (cleaning, EDA, GLM)
- `Group_13_Analysis.html` — rendered report output
- `README.md` — project guide
  
## How to run the analysis (Quarto)
### Option: RStudio
1. Open `Group_13_Analysis.qmd` in RStudio
2. Install packages (if prompted)
3. Click **Render**

## Team & contributions
- **Yiying Wang**: repository setup, README maintenance
- **Jiani Wang**: data upload (`dataset13.csv`) + data cleaning + EDA plots + descriptive summaries
- **Ricky Tong**: GLM modelling + interpretation of model fit
- **Anqi Shen**: presentation slides + final polishing (formatting, clarity, checks)
- **Xiangrui Meng**: presentation slides + final polishing (formatting, clarity, checks)
