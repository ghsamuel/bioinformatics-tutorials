# Bioinformatics Tutorials

**Conceptual walkthroughs for working scientists — not just code.**

Every tutorial explains the *why* behind each decision: why this normalization, why this threshold, what the output actually means. Built for wet-lab scientists making the transition to computational analysis, and for computational biologists who want to understand the biology behind the methods.

> 🚧 **Work in progress.** Tutorials are live and complete. Two additional tutorials (CITE-seq, Survival Analysis) are in progress.

---

## Tutorials

| Tutorial | Methods | Dataset | Sections |
|---|---|---|---|
| [Bulk RNA-seq Differential Expression](https://ghsamuel.netlify.app/rnaseq_tutorial_final.html) | DESeq2 · Salmon · LFC shrinkage · GO & GSEA | Airway · Himes et al. 2014 | 15 |
| [scRNA-seq Analysis End-to-End](https://ghsamuel.netlify.app/scrna_tutorial_final.html) | Scanpy · QC · Clustering · Cell type annotation · Batch correction | PBMC 3k · 10x Genomics | 16 |
| [Cell-Cell Communication with CellChat](https://ghsamuel.netlify.app/cellchat_tutorial_final.html) | CellChat v2 · L-R inference · Network analysis · Condition comparison | Atopic dermatitis · NL vs LS | 15 |
| [Spatial Proteomics — IMC](https://ghsamuel.netlify.app/spatial_proteomics_tutorial_final.html) | Squidpy · arcsinh normalization · Neighborhood enrichment · Co-occurrence | Jackson 2020 · Breast cancer IMC | 12 |

**Coming soon**
- CITE-seq Multimodal Analysis — WNN integration, DSB normalization, dual annotation
- Survival Analysis — Kaplan-Meier, Cox proportional hazards, gene expression survival

---

## What makes these different

Most bioinformatics tutorials hand you a code block and move on. These don't.

Each tutorial includes:

- **Concept-first sections** — the biology and statistics before any code
- **Schematics** — original diagrams explaining data structures, pipeline flows, and method logic
- **Analogy blocks** — plain-language explanations for hard concepts
- **Callouts** — common mistakes, caveats reviewers catch, tips that save hours
- **Comparison tables** — when to use this method vs alternatives
- **Publication figure guidance** — what reviewers expect to see

---

## Datasets used

| Dataset | Source | Why this one |
|---|---|---|
| Airway smooth muscle | [GEO GSE52778](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE52778) | Classic DESeq2 benchmark, well-characterized biology |
| PBMC 3k | [10x Genomics](https://www.10xgenomics.com/datasets/3-k-pb-mc-s-from-a-healthy-donor-1-standard-1-1-0) | The canonical scRNA-seq learning dataset |
| Human skin — atopic dermatitis | [Figshare](https://figshare.com/projects/Example_data_for_cell-cell_communication_analysis_using_CellChat/157272) | Official CellChat tutorial dataset · NL vs LS conditions |
| Jackson 2020 breast cancer IMC | [Zenodo 3518284](https://doi.org/10.5281/zenodo.3518284) | Gold-standard public IMC dataset · pre-segmented · 352 patients |

---

## About

Built by [Glady Hazitha Samuel](https://ghsamuel.netlify.app), computational biologist at the University of Connecticut.

Research focus: alternative splicing and alternative polyadenylation in neuronal differentiation using PacBio long-read RNA-seq.

Other projects: [smartGSEA](https://github.com/ghsamuel/smartGSEA) · [PASplot Shiny App](https://github.com/ghsamuel/Shiny_app_PASplot) · [KOL Analytics Platform](https://kolmappers.netlify.app)

---

*If these tutorials helped you, a ⭐ on the repo is appreciated.*
