# Tarsometatarsus: Ankara vs Nigde - Full ML Pipeline (ASCII ONLY)

This repository contains an end-to-end ML pipeline in R to classify specimens (Ross vs Cobb) using measurements from an Excel file (`data.xlsx`).

Key features:
- Saves all figures to `./figures`
- Saves all outputs (CSVs) to `./outputs`
- Normalizes Turkish characters to ASCII (Unicode escapes)
- No Plotly (PCA saved as PNG via base R + ggplot2)

## Input data
Place your Excel file here:

- `data/data.xlsx`

Expected sheets:
- `Ross`
- `Cobb`

## How to run
From the repo root:

```bash
Rscript pipeline.R

cff-version: 1.2.0
message: "If you use this pipeline, please cite it."
title: "Tarsometatarsus: Ankara vs Nigde - Full ML Pipeline"
type: software
authors:
  - family-names: "Zeybek"
    given-names: "Mustafa"
year: 2026
license: "MIT"
