## Overview

This repository contains the notebooks, intermediate artifacts, and sample outputs used to evaluate LLM translations of **Tractate Sotah**, with an emphasis on detecting potential **“smoothing”** of harsh or morally challenging content.

---

## Download datasets

### 1) Full Talmud data (Sefaria)
Use **Download Talmud Data** to download the original Hebrew text and English translations for all tractates from Sefaria.

- Relevant dataset location: `The Full Talmud- GPT 3.5/`

### 2) Sotah subset used in the paper
Use **Download Sotah Data** to download the original Hebrew text and English translations for the selected Sotah sections analyzed in the paper.

- Relevant file: `Sotah Analysis Code/sotah_passages_with_text.json`

---

## Run the analysis

### Sotah / tractate-level analysis
Model-specific code for running analysis on an individual tractate or Sotah section:

- `Sotah Analysis Code/`

### Bavli-wide (batch) analysis
Code for running analysis across the entire Talmud:

- `Batch Translation Code/`

---

## Results

### Human evaluation and QA assessment
Evaluator comments are in:
- the Sotah GPT-3.5 vs GPT-5.2 comparison file
- the QA assessment file

### Output files
Generated outputs are located in:
- `QA Results/`
- `Translation_Results/`
