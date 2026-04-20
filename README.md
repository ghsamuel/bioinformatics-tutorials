<div align="center">

# 🧬 Bioinformatics Tutorials

**Conceptual walkthroughs for working scientists — not just code.**

[![Bulk RNA-seq](https://img.shields.io/badge/Bulk_RNA--seq-Live-2d6a4f?style=flat-square)](https://ghsamuel.netlify.app/rnaseq_tutorial.html)
[![scRNA-seq](https://img.shields.io/badge/scRNA--seq-Live-c2410c?style=flat-square)]
(https://ghsamuel.netlify.app/scrna_tutorial)
[![CellChat](https://img.shields.io/badge/CellChat-Live-3b5bdb?style=flat-square)](https://ghsamuel.netlify.app/cellchat_tutorial.html)
[![Spatial](https://img.shields.io/badge/Spatial_Proteomics-Live-0f766e?style=flat-square)](https://ghsamuel.netlify.app/spatial_proteomics_tutorial.html)
[![Status](https://img.shields.io/badge/status-work_in_progress-f59e0b?style=flat-square)]()

</div>

---

Every tutorial explains the *why* behind each decision: why this normalization, why this threshold, what the output actually means. Built for wet-lab scientists making the transition to computational analysis, and for computational biologists who want to understand the biology behind the methods.

> 🚧 **Work in progress.** All tutorials are actively being written and updated — content, schematics, and code will continue to improve over time.

---

## 📚 Tutorials

| | Tutorial | Methods | Dataset |
|---|---|---|---|
| 🟢 | [**Bulk RNA-seq Differential Expression**](https://ghsamuel.netlify.app/rnaseq_tutorial_final.html) | DESeq2 · Salmon · LFC shrinkage · GO & GSEA | Airway · Himes et al. 2014 |
| 🟠 | [**scRNA-seq Analysis End-to-End**](https://ghsamuel.netlify.app/scrna_tutorial_final.html) | Scanpy · QC · Clustering · Annotation · Batch correction | PBMC 3k · 10x Genomics |
| 🔵 | [**Cell-Cell Communication with CellChat**](https://ghsamuel.netlify.app/cellchat_tutorial_final.html) | CellChat v2 · L-R inference · Network analysis · Comparison | Atopic dermatitis · NL vs LS |
| 🩵 | [**Spatial Proteomics — IMC**](https://ghsamuel.netlify.app/spatial_proteomics_tutorial_final.html) | Squidpy · arcsinh normalization · Neighborhood enrichment | Jackson 2020 · Breast cancer IMC |
| ⬜ | CITE-seq Multimodal Analysis *(coming soon)* | WNN integration · DSB normalization · Dual annotation | PBMC 5k · TotalSeq-B |
| ⬜ | Survival Analysis *(coming soon)* | Kaplan-Meier · Cox hazards · Gene expression survival | TCGA BRCA |

---

## ✦ What makes these different

Most bioinformatics tutorials hand you a code block and move on. These don't.

```
Each tutorial includes:

  ◆ Concept-first sections    — biology and statistics before any code
  ◆ Original schematics       — diagrams for data structures and pipelines
  ◆ Analogy blocks            — plain-language explanations for hard concepts
  ◆ Callout boxes             — mistakes, caveats, tips that save hours
  ◆ Comparison tables         — when to use this method vs alternatives
  ◆ Publication figure guide  — what reviewers expect to see
```

---

## 🗂 Datasets

| Dataset | Access | Notes |
|---|---|---|
| Airway smooth muscle | [GEO GSE52778](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE52778) | Classic DESeq2 benchmark |
| PBMC 3k | [10x Genomics](https://www.10xgenomics.com/datasets/3-k-pb-mc-s-from-a-healthy-donor-1-standard-1-1-0) | Canonical scRNA-seq dataset |
| Human skin — atopic dermatitis | [Figshare](https://figshare.com/projects/Example_data_for_cell-cell_communication_analysis_using_CellChat/157272) | NL vs LS · Official CellChat dataset |
| Jackson 2020 breast cancer IMC | [Zenodo 3518284](https://doi.org/10.5281/zenodo.3518284) | Pre-segmented · 352 patients |

---

## 👤 About

Built by **[Glady Hazitha Samuel](https://ghsamuel.netlify.app)** — computational biologist at the University of Connecticut working on alternative splicing and APA in neuronal differentiation using PacBio long-read RNA-seq.

<div align="left">

[![Portfolio](https://img.shields.io/badge/Portfolio-ghsamuel.netlify.app-2d6a4f?style=flat-square)](https://ghsamuel.netlify.app)
[![smartGSEA](https://img.shields.io/badge/R_Package-smartGSEA-c2410c?style=flat-square)](https://github.com/ghsamuel/smartGSEA)
[![PASplot](https://img.shields.io/badge/Shiny-PASplot-0f766e?style=flat-square)](https://github.com/ghsamuel/Shiny_app_PASplot)
[![KOL Analytics](https://img.shields.io/badge/Platform-KOL_Analytics-3b5bdb?style=flat-square)](https://kolmappers.netlify.app)

</div>

---

<div align="center">
<sub>If these tutorials helped you, a ⭐ is appreciated.</sub>
</div>
