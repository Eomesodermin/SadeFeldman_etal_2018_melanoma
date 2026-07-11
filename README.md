# Sade-Feldman et al. 2018 — melanoma TIL states (re-analysis)

Re-analysis of the publicly available single-cell dataset from:

> **Sade-Feldman M, Yizhak K, Bjorgaard SL, et al. Defining T Cell States Associated with Response to Checkpoint Immunotherapy in Melanoma.**  
> *Cell* 2018. https://doi.org/10.1016/j.cell.2018.10.038  
> Data: GEO: GSE120575

## Dataset at a glance
- **System:** Human metastatic melanoma tumour-infiltrating lymphocytes (pre/post checkpoint blockade)
- **Assay:** Smart-seq2 scRNA-seq
- **Accession / source:** GEO: GSE120575

## What this repository does
Preprocesses the Sade-Feldman melanoma TIL dataset into an annotated Seurat object (QC, normalisation, clustering, T-cell state annotation). See `R/01_Sade_Feldman_Cell_2018_Melanoma_TIL_PreProcessing.Rmd`.

## Repository structure
- `R/` — analysis pipeline (numbered `.Rmd` scripts run in order)
- `Setup.R` / `Load_packages.R` — environment setup and package loading
- Large data objects are **not** tracked in Git — download from the source above.
- `renv.lock` — pinned package versions for reproducibility (`renv::restore()`).

---
Part of my NK / T-cell single-cell research programme — see my [GitHub profile](https://github.com/Eomesodermin) and [dilloncorvino.com](https://dilloncorvino.com).  
Author: **Dillon Corvino**
