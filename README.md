# Pan-Cancer Profiling of LYVE1⁺ Perivascular Macrophages
Single-cell transcriptomic analysis of LYVE1⁺ perivascular macrophages and  fibroblast–macrophage cross-talk across multiple cancers. 

---

## Background

LYVE1⁺ macrophages are a specialized tissue-resident subset that occupy perivascular niches. They are known for their role in lymphatic remodeling, hyaluronan turnover, and vascular maintenance in healthy tissues. Recent single-cell studies have identified them as important regulators of angiogenesis, stromal organization, and immune suppression within tumors.

These macrophages (often co-expressing FOLR2, MRC1, and C1QC) line the vasculature and secrete factors such as VEGFA and ANGPT2, promoting vessel stability and shaping immune infiltration. Their perivascular position and signaling functions make them key players in the tumor microenvironment (TME), yet they remain underexplored across cancers.

Fibroblasts form another major stromal component of the TME. They secrete growth factors, cytokines, and extracellular-matrix proteins that regulate tumor growth and immune cell behavior. Their communication with macrophages helps establish vascular niches that influence tumor progression and therapy resistance.

Understanding this macrophage–fibroblast cross-talk can reveal conserved stromal signaling circuits that drive angiogenesis, immune modulation, and tissue remodeling across cancer types.

---

## Project Objectives

1. Identify LYVE1⁺ perivascular macrophages across single-cell datasets from multiple cancers.
2. Characterize their transcriptional signatures and heterogeneity.
3. Examine fibroblast–macrophage communication networks using **NicheNet**.
4. Integrate findings across datasets to detect conserved or cancer-specific pathways involved in stromal signaling.

---

## Tools and Datasets

- **R packages:** Seurat, dplyr, ggplot2, clusterProfiler, msigdbr, org.Hs.eg.db, nichenetr  
- **Data sources:** Public single-cell RNA-seq datasets (details to be added)

---

## Workflow Overview

1. Quality control, normalization, and clustering in Seurat  
2. Annotation of LYVE1⁺ macrophages and stromal cell subsets  
3. Proportion and signature analysis across cancers  
4. Ligand–target inference using NicheNet  
5. Visualization and biological interpretation

---

## Repository Layout


This repository is under active development; scripts and figures will be added progressively.

