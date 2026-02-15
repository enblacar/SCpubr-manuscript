## Reproducing the figures

All figures in the manuscript can be reproduced using the scripts in the `Code/` directory:

- **`Code/Figures.qmd`** — Figure 1 (panels A–I)
- **`Code/Supp Figures.qmd`** — Supplementary Figures 1–4

Each script starts from a preprocessed Seurat object and contains the exact
SCpubr function calls used to generate every panel. Figures were exported
individually using `SCpubr::do_SavePlot()` and assembled in Affinity Designer.

The input dataset originates from Blanco-Carmona et al. (2023), *Cell Reports
