# Capacity-Controlled Volatility Forecasting — Supplementary Materials

This repository contains supplementary materials accompanying the research paper:

**“Capacity-Controlled Volatility Forecasting”**

The study investigates volatility forecasting under explicit model capacity constraints and evaluates econometric, machine learning, and deep learning models across multiple equity indices and forecasting horizons.

The repository provides the data artefacts, diagnostic analyses, and representative forecasting outputs used in the empirical study.

---

## Repository Structure

The repository contains the following components.

### Figures

`FIGURES_DRAWINGS/`

Figures used in the manuscript, including prediction overlays, forecast diagnostics, and training curves for selected experiments.

---

### Statistical Tables

`stats_tables/`

Forecast accuracy tables across models, indices, and horizons.  
Metrics include QLIKE, RMSE, MAE, MASE, and stress-period diagnostics.

---

### Volatility Process Diagnostics

Several directories contain the structural diagnostics discussed in the paper:

- `plots_diag/`
- `plots_bocpd/`
- `plots_hmm/`
- `plot_stats/`
- `regime_state_plots/`
- `regime_transition_plots/`
- `regime_transitions/`
- `regime_macro/`
- `regime_micro/`

These analyses examine regime persistence, structural breaks, and volatility jump behaviour.

---

### Data

Processed datasets used in the forecasting experiments are provided in

- `data_clean/`
- `data_returns/`
- `data_targets/`
- `data_diag/`
- `data_merged/`

Raw vendor datasets are not redistributed where licensing restrictions apply.

---

### Forecasting Model Results

`models_forecast_results/`

This directory contains representative outputs for several model classes:

- HAR
- HAR-X
- Elastic Net HAR-X
- Ridge regression
- XGBoost HAR-X
- MLP-based models

These outputs include summary CSV tables and forecast visualisations used in the manuscript.

---

### Experimental Code

`Vol_Code_files/`

Supporting scripts used for

- data preparation
- volatility diagnostics
- regime analysis
- experiment orchestration

These scripts document the computational pipeline used in the study.

---

## Note on Deep Learning Experiment Artifacts

Several deep learning experiments (LSTM and Transformer models) produced very large intermediate outputs, including training checkpoints, archived experiment dumps, and attention-analysis data files.

Due to GitHub’s repository size limitations, these raw experiment archives are **not included** in the public repository.

Instead, the repository provides:

- representative forecast plots
- aggregated evaluation tables
- diagnostic outputs used in the analysis

These materials contain the results required to reproduce the empirical findings reported in the paper.

The omission of large intermediate artifacts is solely for repository size management and does **not affect the reported results or conclusions**.

---

## Purpose of the Repository

This repository is intended to provide transparency for the empirical analysis and to document the diagnostic investigations underlying the study.

It serves as a supplementary resource accompanying the paper rather than a full archival storage of all experimental artifacts.

---

## Disclaimer

The materials provided in this repository are intended for academic research and documentation purposes.

The forecasting results and models should not be interpreted as financial advice or as recommendations for trading or investment.