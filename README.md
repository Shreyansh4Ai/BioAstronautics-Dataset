<div align="right">

[![Visitors](https://visitor-badge.laobi.icu/badge?page_id=OWNER.REPO&left_color=grey&right_color=blue&left_text=Visitors)](https://github.com/OWNER/REPO)

</div>

<div align="center">

# 🛰️ Curated Datasets for RPM and Simulated Microgravity Research

### *Because "just Google it" doesn't work when your subject is floating in a lab on Earth pretending it's in space* 🚀

[![Made with](https://img.shields.io/badge/built_with-systematic_review-9cf?style=for-the-badge)]()
[![Papers Reviewed](https://img.shields.io/badge/papers_reviewed-57-orange?style=for-the-badge)]()
[![Datasets Linked](https://img.shields.io/badge/datasets_linked-9-brightgreen?style=for-the-badge)]()
[![License](https://img.shields.io/badge/license-CC%20BY%204.0-lightgrey?style=for-the-badge)]()

</div>

---

## 1. 📖 Introduction

Space research is expensive, slow, and painfully hard to access — real microgravity is a scarce resource, gate-kept by national space agencies and multi-year mission timelines. So scientists on Earth do the next best thing: they build machines that *fake* it. Enter the **Random Positioning Machine (RPM)** and its cousins — clinostats, RWVs, RCCS bioreactors — devices that constantly reorient a sample so gravity averages out to (roughly) zero.

Dozens of research groups worldwide have used these machines to study how human, animal, plant, and microbial cells behave when gravity stops being a constant. The problem? Their findings are scattered across 50+ papers, a dozen journals, and just as many data repositories — with no single place that pulls it all together.

**This repository is that place.**

## 2. 🌌 About

This is a curated, structured, and continuously growing collection of **research papers and datasets** on RPM and simulated microgravity, built through a systematic literature review. Every entry has been read, tagged, and — where possible — traced back to its original raw dataset (gene expression, proteomics, imaging, or numerical data), so researchers, students, and reviewers can find and reuse this data without repeating the months of digging that went into finding it.

## 3. 🔬 Our Research

This project was completed as a research internship task, split into two linked deliverables:

| | Project 1 — Research Dataset Creation | Project 2 — AI Benchmark Pipeline |
|---|---|---|
| **Goal** | Perform a systematic literature review, extract variables from published studies, standardize terminology and units, and package it as an open, structured dataset | Formulate prediction/classification problems on the curated dataset, run EDA and preprocessing, and benchmark baseline ML models |
| **Output** | This repository — v1.0 of the open dataset + a detailed data dictionary | A reproducible training pipeline (Random Forest, XGBoost, Neural Network) with benchmark results |

## 4. 🛠️ Tools Used

| Tool | Purpose | Link |
|---|---|---|
| 🔎 **Elicit** | AI-powered literature search and structured data extraction from papers | [elicit.com](https://elicit.com) |
| 📊 **Consensus** | AI-powered search for evidence-based, yes/no research questions | [consensus.app](https://consensus.app) |
| 📚 **Zotero** | Reference management, de-duplication, and screening | [zotero.org](https://www.zotero.org) |
| 🧮 **Julius** | AI-powered data analysis, cleaning, and visualization | [julius.ai](https://julius.ai) |

## 5. 👥 Contributors

| Name | GitHub | Gmail |
|---|---|---|
| Shivam Tandon | [@tShivam25](https://github.com/tShivam25) | shivamtandonn@gmail.com |
| Shreyansh Puri Goswami | [@Shreyansh4Ai](https://github.com/Shreyansh4Ai) | goswami121shreyansh@gmail.com |
| Manoj Kumar Sinha | [@mksinha01](https://github.com/mksinha01) | mksinha77756@gmail.com |
| Dikesh Patel | [@heisdk25](https://github.com/heisdk25) |thedikesh@gmail.com |

**Research Supervisors & Mentors**

| Name | Role | Email ID |
|---|---|---|
| Dr. Saurabh Gupta | Research Supervisor and Mentor | sgupta.bme@nitrr.ac.in |
| Dr. Sumit Kumar Roy | Research Supervisor and Mentor | skroy.phd2022.bme@nitrr.ac.in |

## 6. 📑 Table of Contents

- [1. Introduction](#1--introduction)
- [2. About](#2--about)
- [3. Our Research](#3--our-research)
- [4. Tools Used](#4--tools-used)
- [5. Contributors](#5--contributors)
- [6. Table of Contents](#6--table-of-contents)
- [7. Dataset Table](#7--dataset-table)
- [8. Paper Details](#8--paper-details)

---

## 7. 📊 Dataset Table

> 57 papers reviewed · 9 with confirmed, linkable public datasets · full extraction details in each row below.

| # | Paper Title | Journal | DOI | Paper Link | Details | Type of Dataset | Dataset Link |
|---|---|---|---|---|---|---|---|
| 1 | Changes in Human Foetal Osteoblasts Exposed to the Random Positioning Machine and Bone Construct Tissue Engineering | International Journal of Molecular Sciences | `10.3390/ijms20061357` | [Link](https://doi.org/10.3390/ijms20061357) | [View Details](#paper-1) | — | *to be added* |
| 2 | Simulated Microgravity Influences VEGF, MAPK, and PAM Signaling in Prostate Cancer Cells | International Journal of Molecular Sciences | `10.3390/ijms21041263` | [Link](https://doi.org/10.3390/ijms21041263) | [View Details](#paper-2) | — | *to be added* |
| 3 | Temporary effects of random positioning on the function and plasticity of proliferating monocytes | Scientific Reports | `10.1038/s41598-025-26941-x` | [Link](https://doi.org/10.1038/s41598-025-26941-x) | [View Details](#paper-3) | — | *to be added* |
| 4 | Alterations of Growth and Focal Adhesion Molecules in Human Breast Cancer Cells Exposed to the Random Positioning Machine | Frontiers in Cell and Developmental Biology | `10.3389/fcell.2021.672098` | [Link](https://doi.org/10.3389/fcell.2021.672098) | [View Details](#paper-4) | — | *to be added* |
| 5 | Fluid Dynamics Appearing during Simulated Microgravity Using Random Positioning Machines | PLoS ONE | `10.1371/journal.pone.0170826` | [Link](https://doi.org/10.1371/journal.pone.0170826) | [View Details](#paper-5) | Numerical (Figure source data, XLSX) | [Link](https://doi.org/10.6084/m9.figshare.4555852) |
| 6 | Validation of Random Positioning Versus Clinorotation Using a Macrophage Model System | Microgravity, science and technology | `10.1007/s12217-019-9687-0` | [Link](https://doi.org/10.1007/s12217-019-9687-0) | [View Details](#paper-6) | — | *to be added* |
| 7 | Simulating microgravity using a random positioning machine for inducing cellular responses to mechanotransduction in human osteoblasts. | Review of Scientific Instruments | `10.1063/5.0056366` | [Link](https://doi.org/10.1063/5.0056366) | [View Details](#paper-7) | — | *to be added* |
| 8 | Simulated Microgravity Potentiates Hematopoietic Differentiation of Human Pluripotent Stem Cells and Supports Formation of 3D Hematopoietic Cluster | Frontiers in Cell and Developmental Biology | `10.3389/fcell.2021.797060` | [Link](https://doi.org/10.3389/fcell.2021.797060) | [View Details](#paper-8) | RNA-seq (FASTQ) | [Link](https://download.cncb.ac.cn/gsa-human/HRA001496) |
| 9 | Analysis of Statoliths Displacement in Chara Rhizoids for Validating the Microgravity-Simulation Quality of Clinorotation Modes | Microgravity, science and technology | `10.1007/s12217-017-9580-7` | [Link](https://doi.org/10.1007/s12217-017-9580-7) | [View Details](#paper-9) | — | *to be added* |
| 10 | Fluid and Bubble Flow Detach Adherent Cancer Cells to Form Spheroids on a Random Positioning Machine | Cells | `10.3390/cells12222665` | [Link](https://doi.org/10.3390/cells12222665) | [View Details](#paper-10) | — | *to be added* |
| 11 | Exposure to Random Positioning Machine Alters the Mineralization Process and PTX3 Expression in the SAOS-2 Cell Line | Life | `10.3390/life12050610` | [Link](https://doi.org/10.3390/life12050610) | [View Details](#paper-11) | — | *to be added* |
| 12 | Apoptosis Induction and Alteration of Cell Adherence in Human Lung Cancer Cells under Simulated Microgravity | International Journal of Molecular Sciences | `10.3390/ijms20143601` | [Link](https://doi.org/10.3390/ijms20143601) | [View Details](#paper-12) | — | *to be added* |
| 13 | Guidelines for use of the random positioning machine as a reduced-gravity analog | Scientific Reports | `10.1038/s41598-026-39316-7` | [Link](https://doi.org/10.1038/s41598-026-39316-7) | [View Details](#paper-13) | — | *to be added* |
| 14 | Changes in the Surface Expression of Intercellular Adhesion Molecule 3, the Induction of Apoptosis, and the Inhibition of Cell-Cycle Progression of Human Multidrug-Resistant Jurkat/A4 Cells Exposed to a Random Positioning Machine | International Journal of Molecular Sciences | `10.3390/ijms21030855` | [Link](https://doi.org/10.3390/ijms21030855) | [View Details](#paper-14) | — | *to be added* |
| 15 | Design of a novel 3DOF clinostat to produce microgravity for bioengineering applications | 2018 IEEE XXV International Conference on Electronics, Electrical Engineering and Computing (INTERCON) | `10.1109/INTERCON.2018.8526401` | [Link](https://doi.org/10.1109/INTERCON.2018.8526401) | [View Details](#paper-15) | — | *to be added* |
| 16 | Characterization of the random positioning machine as a microgravity simulator for biological applications | PLoS ONE | `10.1371/journal.pone.0351320` | [Link](https://doi.org/10.1371/journal.pone.0351320) | [View Details](#paper-16) | — | *to be added* |
| 17 | Impact of the rotational speed and counter electrode configuration on the performance of a rotating disc bioelectrochemical reactor (RDBER) operated as microbial electrolysis cell | bioRxiv preprint | `10.1101/2025.03.06.641858` | [Link](https://doi.org/10.1101/2025.03.06.641858) | [View Details](#paper-17) | — | *to be added* |
| 18 | Effects of angular frequency during clinorotation on mesenchymal stem cell morphology and migration | npj Microgravity | `10.1038/npjmgrav.2015.7` | [Link](https://doi.org/10.1038/npjmgrav.2015.7) | [View Details](#paper-18) | — | *to be added* |
| 19 | Simulated Microgravity and 3D Culture Enhance Induction, Viability, Proliferation and Differentiation of Cardiac Progenitors from Human Pluripotent Stem Cells | Scientific Reports (Sci Rep) | `10.1038/srep30956` | [Link](https://doi.org/10.1038/srep30956) | [View Details](#paper-19) | — | *to be added* |
| 20 | LIF-Free Embryonic Stem Cell Culture in Simulated Microgravity | PLoS ONE | `10.1371/journal.pone.0006343` | [Link](https://doi.org/10.1371/journal.pone.0006343) | [View Details](#paper-20) | — | *to be added* |
| 21 | Effects of microgravity on cell cytoskeleton and embryogenesis | International Journal of Developmental Biology | `10.1387/ijdb.052077sc` | [Link](https://doi.org/10.1387/ijdb.052077sc) | [View Details](#paper-21) | — | *to be added* |
| 22 | Effects of Simulated Microgravity on Human Umbilical Vein Endothelial Cell Angiogenesis and Role of the PI3K-Akt-eNOS Signal Pathway | PLoS ONE | `10.1371/journal.pone.0040365` | [Link](https://doi.org/10.1371/journal.pone.0040365) | [View Details](#paper-22) | — | *to be added* |
| 23 | Enhancement of Osteogenic Differentiation and Proliferation in Human Mesenchymal Stem Cells by a Modified Low Intensity Ultrasound Stimulation under Simulated Microgravity | PLoS ONE | `10.1371/journal.pone.0073914` | [Link](https://doi.org/10.1371/journal.pone.0073914) | [View Details](#paper-23) | — | *to be added* |
| 24 | Duration of simulated microgravity affects the differentiation of mesenchymal stem cells | Molecular Medicine Reports | `10.3892/mmr.2017.6357` | [Link](https://doi.org/10.3892/mmr.2017.6357) | [View Details](#paper-24) | — | *to be added* |
| 25 | Mechanisms of three-dimensional growth of thyroid cells during long-term simulated microgravity | Scientific Reports | `10.1038/srep16691` | [Link](https://doi.org/10.1038/srep16691) | [View Details](#paper-25) | — | *to be added* |
| 26 | Effect of Simulated Microgravity on E. coli K12 MG1655 Growth and Gene Expression | PLoS ONE | `10.1371/journal.pone.0057860` | [Link](https://doi.org/10.1371/journal.pone.0057860) | [View Details](#paper-26) | — | *to be added* |
| 27 | Simulated microgravity triggers epithelial mesenchymal transition in human keratinocytes | Scientific Reports | `10.1038/s41598-017-00602-0` | [Link](https://doi.org/10.1038/s41598-017-00602-0) | [View Details](#paper-27) | — | *to be added* |
| 28 | Effects of spaceflight and simulated microgravity on microbial growth and secondary metabolism | Military Medical Research | `10.1186/s40779-018-0162-9` | [Link](https://doi.org/10.1186/s40779-018-0162-9) | [View Details](#paper-28) | — | *to be added* |
| 29 | The influence of spaceflight and simulated microgravity on bacterial motility and chemotaxis | npj Microgravity | `10.1038/s41526-021-00135-x` | [Link](https://doi.org/10.1038/s41526-021-00135-x) | [View Details](#paper-29) | — | *to be added* |
| 30 | Effects of Simulated Microgravity on Ultrastructure and Apoptosis of Choroidal Vascular Endothelial Cells | Frontiers in Physiology | `10.3389/fphys.2020.577325` | [Link](https://doi.org/10.3389/fphys.2020.577325) | [View Details](#paper-30) | — | *to be added* |
| 31 | Simulated microgravity enhances CDDP-induced apoptosis signal via p53-independent mechanisms in cancer cells | PLOS ONE | `10.1371/journal.pone.0219363` | [Link](https://doi.org/10.1371/journal.pone.0219363) | [View Details](#paper-31) | — | *to be added* |
| 32 | Effect of miR-27b-5p on apoptosis of human vascular endothelial cells induced by simulated microgravity | ApoptosisApoptosis: An International Journal on Programmed Cell Death | `10.1007/s10495-019-01580-6` | [Link](https://doi.org/10.1007/s10495-019-01580-6) | [View Details](#paper-32) | — | *to be added* |
| 33 | A New System for Three-dimensional Clinostat Synchronized X-irradiation with a High-speed Shutter for Space Radiation Research | Biological Sciences in Space | `10.2187/bss.30.8` | [Link](https://doi.org/10.2187/bss.30.8) | [View Details](#paper-33) | — | *to be added* |
| 34 | Customized small-sized clinostat using 3D printing and gas-permeable polydimethylsiloxane culture dish | NPJ microgravity | `10.1038/s41526-023-00311-1` | [Link](https://doi.org/10.1038/s41526-023-00311-1) | [View Details](#paper-34) | — | *to be added* |
| 35 | Simulation of Microgravity by Magnetic Levitation and Random Positioning: Effect on Human A431 Cell Morphology | Microgravity Science and Technology | `10.1007/s12217-010-9185-x` | [Link](https://doi.org/10.1007/s12217-010-9185-x) | [View Details](#paper-35) | — | *to be added* |
| 36 | Simulated microgravity inhibits osteogenic differentiation of mesenchymal stem cells via depolymerizing F-actin to impede TAZ nuclear translocation | Scientific Reports | `10.1038/srep30322` | [Link](https://doi.org/10.1038/srep30322) | [View Details](#paper-36) | — | *to be added* |
| 37 | 3D cell culture using a clinostat reproduces microgravity-induced skin changes | npj Microgravity | `10.1038/s41526-021-00148-6` | [Link](https://doi.org/10.1038/s41526-021-00148-6) | [View Details](#paper-37) | — | *to be added* |
| 38 | Common Effects on Cancer Cells Exerted by a Random Positioning Machine and a 2D Clinostat | PLoS ONE | `10.1371/journal.pone.0135157` | [Link](https://doi.org/10.1371/journal.pone.0135157) | [View Details](#paper-38) | — | *to be added* |
| 39 | Differential gene expression profile and altered cytokine secretion of thyroid cancer cells in space | The FASEB Journal | `10.1096/fj.13-243287` | [Link](https://doi.org/10.1096/fj.13-243287) | [View Details](#paper-39) | — | *to be added* |
| 40 | Spaceflight and simulated microgravity cause a significant reduction of key gene expression in early T-cell activation. | American Journal of Physiology. Regulatory Integrative and Comparative Physiology | `10.1152/ajpregu.00449.2014` | [Link](https://doi.org/10.1152/ajpregu.00449.2014) | [View Details](#paper-40) | Numerical (Microarray, CEL/TXT) | [Link](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE33801) |
| 41 | Proteome Analysis of Human Follicular Thyroid Cancer Cells Exposed to the Random Positioning Machine | International Journal of Molecular Sciences | `10.3390/ijms18030546` | [Link](https://doi.org/10.3390/ijms18030546) | [View Details](#paper-41) | — | *to be added* |
| 42 | Simulated Microgravity Remodels Extracellular Matrix of Osteocommitted Mesenchymal Stromal Cells | International Journal of Molecular Sciences | `10.3390/ijms22115428` | [Link](https://doi.org/10.3390/ijms22115428) | [View Details](#paper-42) | — | *to be added* |
| 43 | Proteomic profile of cultured human endothelial cells after exposition to simulated microgravity | Acta Astronautica | `10.1016/j.actaastro.2020.10.014` | [Link](https://doi.org/10.1016/j.actaastro.2020.10.014) | [View Details](#paper-43) | — | *to be added* |
| 44 | Growth of Endothelial Cells in Space and in Simulated Microgravity - a Comparison on the Secretory Level. | Cellular Physiology and Biochemistry | `10.33594/000000071` | [Link](https://doi.org/10.33594/000000071) | [View Details](#paper-44) | — | *to be added* |
| 45 | Neocartilage Formation in 1 g, Simulated, and Microgravity Environments: Implications for Tissue Engineering | Tissue Engineering. Part A | `10.1089/ten.tea.2008.0624` | [Link](https://doi.org/10.1089/ten.tea.2008.0624) | [View Details](#paper-45) | — | *to be added* |
| 46 | Gene Expression Profiles of 2T3 Preosteoblasts in Microgravity Analog Systems: Comparison of the Random Positioning Machine and the Rotating Wall Vessel Bioreactor | The FASEB Journal | `10.1096/fasebj.20.5.A1250-a` | [Link](https://doi.org/10.1096/fasebj.20.5.A1250-a) | [View Details](#paper-46) | — | *to be added* |
| 47 | Plastid position in Arabidopsis columella cells is similar in microgravity and on a random-positioning machine | Planta | `10.1007/s004250000302` | [Link](https://doi.org/10.1007/s004250000302) | [View Details](#paper-47) | — | *to be added* |
| 48 | Functional alterations of root meristematic cells of <em>Arabidopsis thaliana</em> induced by a simulated microgravity environment | Journal of Plant Physiology | `10.1016/j.jplph.2016.09.011` | [Link](https://doi.org/10.1016/j.jplph.2016.09.011) | [View Details](#paper-48) | — | *to be added* |
| 49 | Novel, Moon and Mars, partial gravity simulation paradigms and their effects on the balance between cell growth and cell proliferation during early plant development | npj Microgravity | `10.1038/s41526-018-0041-4` | [Link](https://doi.org/10.1038/s41526-018-0041-4) | [View Details](#paper-49) | — | *to be added* |
| 50 | Gravity-Related Immunological Changes in Human Whole Blood Cultured Under Simulated Microgravity Using an In Vitro Cytokine Release Assay | Journal of Interferon and Cytokine Research | `10.1089/jir.2017.0065` | [Link](https://doi.org/10.1089/jir.2017.0065) | [View Details](#paper-50) | — | *to be added* |
| 51 | Cold stress during room temperature housing alters skeletal response to simulated microgravity (hindlimb unloading) in growing female C57BL6 mice | Biochimie | `10.1016/j.biochi.2022.12.009` | [Link](https://doi.org/10.1016/j.biochi.2022.12.009) | [View Details](#paper-51) | Numerical (micro-CT, XLSX/CSV) | [Link](https://osdr.nasa.gov/bio/repo/data/studies/OSD-980) |
| 52 | Long-term osteogenic differentiation of human bone marrow stromal cells in simulated microgravity: novel proteins sighted | Cellular and Molecular Life Sciences | `10.1007/s00018-022-04553-2` | [Link](https://doi.org/10.1007/s00018-022-04553-2) | [View Details](#paper-52) | Proteomics (LC-MS/MS, RAW) | [Link](https://www.ebi.ac.uk/pride/archive/projects/PXD033475) |
| 53 | Effects of simulated microgravity on the expression profiles of RNA during osteogenic differentiation of human bone marrow mesenchymal stem cells | Cell Proliferation | `10.1111/cpr.12539` | [Link](https://doi.org/10.1111/cpr.12539) | [View Details](#paper-53) | RNA-seq (TXT/FASTQ) | [Link](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE114117) |
| 54 | Simulated Microgravity Modulates Differentiation Processes of Embryonic Stem Cells | Cellular Physiology and Biochemistry | `10.1159/000443090` | [Link](https://doi.org/10.1159/000443090) | [View Details](#paper-54) | — | *to be added* |
| 55 | Proteomic analysis of the effects of simulated microgravity in human gastric mucosal cells | Life Sciences in Space Research | `10.1016/j.lssr.2021.10.001` | [Link](https://doi.org/10.1016/j.lssr.2021.10.001) | [View Details](#paper-55) | Proteomics (LC-MS/MS, RAW) | [Link](https://www.ebi.ac.uk/pride/archive/projects/PXD026675) |
| 56 | Simulated Microgravity Modulates Focal Adhesion Gene Expression in Human Neural Stem Progenitor Cells | Life | `10.3390/life12111827` | [Link](https://doi.org/10.3390/life12111827) | [View Details](#paper-56) | Numerical (Gene expression, XLSX) | Dataset available as ZIP (see repo /data folder) |
| 57 | Transcriptomic response of bioengineered human cartilage to parabolic flight microgravity is sex-dependent | npj Microgravity | `10.1038/s41526-023-00255-6` | [Link](https://doi.org/10.1038/s41526-023-00255-6) | [View Details](#paper-57) | RNA-seq (TXT/FASTQ) | [Link](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE206008) |
---

## 8. 📄 Paper Details

> Every paper reviewed for this project, with full extraction details. Dataset links are filled in where a public dataset was confirmed — the rest are marked for follow-up.


<a name="paper-1"></a>
### 📄 Paper #1 — Changes in Human Foetal Osteoblasts Exposed to the Random Positioning Machine and Bone Construct Tissue Engineering

| Field | Detail |
|---|---|
| **Journal** | International Journal of Molecular Sciences |
| **DOI** | [10.3390/ijms20061357](https://doi.org/10.3390/ijms20061357) |
| **Paper Link** | [https://doi.org/10.3390/ijms20061357](https://doi.org/10.3390/ijms20061357) |
| **Details** | hFOB 1.19 human foetal osteoblast cell line cultured on RPM vs 1g static controls; two time points (7 days, 14 days); n=30 per group for histological staining experiments; triplicate qPCR measureme... |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-2"></a>
### 📄 Paper #2 — Simulated Microgravity Influences VEGF, MAPK, and PAM Signaling in Prostate Cancer Cells

| Field | Detail |
|---|---|
| **Journal** | International Journal of Molecular Sciences |
| **DOI** | [10.3390/ijms21041263](https://doi.org/10.3390/ijms21041263) |
| **Paper Link** | [https://doi.org/10.3390/ijms21041263](https://doi.org/10.3390/ijms21041263) |
| **Details** | PC-3 prostate cancer cell line cultured on RPM vs 1g static controls; two time points (3 days, 5 days); AD and MCS subpopulations analyzed separately; triplicate qPCR per sample; TRIFMA run on supe... |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-3"></a>
### 📄 Paper #3 — Temporary effects of random positioning on the function and plasticity of proliferating monocytes

| Field | Detail |
|---|---|
| **Journal** | Scientific Reports |
| **DOI** | [10.1038/s41598-025-26941-x](https://doi.org/10.1038/s41598-025-26941-x) |
| **Paper Link** | [https://doi.org/10.1038/s41598-025-26941-x](https://doi.org/10.1038/s41598-025-26941-x) |
| **Details** | THP-1 cells: n=2-6 biological replicates per assay across 1, 3, and 7 day timepoints; PBMCs: n=5 donors (1 female, 9 male, ages 36-66). |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-4"></a>
### 📄 Paper #4 — Alterations of Growth and Focal Adhesion Molecules in Human Breast Cancer Cells Exposed to the Random Positioning Machine

| Field | Detail |
|---|---|
| **Journal** | Frontiers in Cell and Developmental Biology |
| **DOI** | [10.3389/fcell.2021.672098](https://doi.org/10.3389/fcell.2021.672098) |
| **Paper Link** | [https://doi.org/10.3389/fcell.2021.672098](https://doi.org/10.3389/fcell.2021.672098) |
| **Details** | 12 T25 flasks per condition (1g/RPM) for qPCR/protein analysis; 2×24 slide flasks for immunofluorescence per cell line; triplicate qPCR measurements; STRING network based on 20 analyzed genes. |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-5"></a>
### 📄 Paper #5 — Fluid Dynamics Appearing during Simulated Microgravity Using Random Positioning Machines

| Field | Detail |
|---|---|
| **Journal** | PLoS ONE |
| **DOI** | [10.1371/journal.pone.0170826](https://doi.org/10.1371/journal.pone.0170826) |
| **Paper Link** | [https://doi.org/10.1371/journal.pone.0170826](https://doi.org/10.1371/journal.pone.0170826) |
| **Details** | - "Bulk volume shear stress approximately 10mPa across simulated conditions." - "Wall shear stress approximately 50mPa at 40°/s." - "Wall shear stress approximately 100mPa at 60°/s." - "Wall shear ... |
| **Type of Dataset** | Numerical (Figure source data, XLSX) |
| **Dataset Link** | [https://doi.org/10.6084/m9.figshare.4555852](https://doi.org/10.6084/m9.figshare.4555852) |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-6"></a>
### 📄 Paper #6 — Validation of Random Positioning Versus Clinorotation Using a Macrophage Model System

| Field | Detail |
|---|---|
| **Journal** | Microgravity, science and technology |
| **DOI** | [10.1007/s12217-019-9687-0](https://doi.org/10.1007/s12217-019-9687-0) |
| **Paper Link** | [https://doi.org/10.1007/s12217-019-9687-0](https://doi.org/10.1007/s12217-019-9687-0) |
| **Details** | N=6 repeated experiments per mode; 45-minute recording per experiment; single cell line, single stimulant (zymosan) versus PBS negative control. |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-7"></a>
### 📄 Paper #7 — Simulating microgravity using a random positioning machine for inducing cellular responses to mechanotransduction in human osteoblasts.

| Field | Detail |
|---|---|
| **Journal** | Review of Scientific Instruments |
| **DOI** | [10.1063/5.0056366](https://doi.org/10.1063/5.0056366) |
| **Paper Link** | [https://doi.org/10.1063/5.0056366](https://doi.org/10.1063/5.0056366) |
| **Details** | 6-hour exposure period; adherent and suspension osteoblast populations compared to 1g controls (specific sample size/n not available from abstract). |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-8"></a>
### 📄 Paper #8 — Simulated Microgravity Potentiates Hematopoietic Differentiation of Human Pluripotent Stem Cells and Supports Formation of 3D Hematopoietic Cluster

| Field | Detail |
|---|---|
| **Journal** | Frontiers in Cell and Developmental Biology |
| **DOI** | [10.3389/fcell.2021.797060](https://doi.org/10.3389/fcell.2021.797060) |
| **Paper Link** | [https://doi.org/10.3389/fcell.2021.797060](https://doi.org/10.3389/fcell.2021.797060) |
| **Details** | -"2,061 differentially expressed genes (DEGs) identified in SMG4 vs NG4 comparison (741 up-regulated, 1,320 down-regulated)."  -"2,200 DEGs identified in SMG7 vs NG7 comparison (1,161 up-regulated,... |
| **Type of Dataset** | RNA-seq (FASTQ) |
| **Dataset Link** | [https://download.cncb.ac.cn/gsa-human/HRA001496](https://download.cncb.ac.cn/gsa-human/HRA001496) |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-9"></a>
### 📄 Paper #9 — Analysis of Statoliths Displacement in Chara Rhizoids for Validating the Microgravity-Simulation Quality of Clinorotation Modes

| Field | Detail |
|---|---|
| **Journal** | Microgravity, science and technology |
| **DOI** | [10.1007/s12217-017-9580-7](https://doi.org/10.1007/s12217-017-9580-7) |
| **Paper Link** | [https://doi.org/10.1007/s12217-017-9580-7](https://doi.org/10.1007/s12217-017-9580-7) |
| **Details** | n=11 rhizoids per clinorotation condition; n=4 rhizoids for the real-microgravity MAXUS-8 reference; measurements taken at 840-second and 20-minute timepoints; 5 different RPM modes/speeds tested. |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-10"></a>
### 📄 Paper #10 — Fluid and Bubble Flow Detach Adherent Cancer Cells to Form Spheroids on a Random Positioning Machine

| Field | Detail |
|---|---|
| **Journal** | Cells |
| **DOI** | [10.3390/cells12222665](https://doi.org/10.3390/cells12222665) |
| **Paper Link** | [https://doi.org/10.3390/cells12222665](https://doi.org/10.3390/cells12222665) |
| **Details** | 4 cell lines tested (primarily FTC-133); RPM speeds tested: 25°/s, 60°/s, 90°/s; pre-attachment periods of 24h and 48h; flow rates of 0.5 and 1.0 mL/min; n=3-5 independent experiments per condition... |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-11"></a>
### 📄 Paper #11 — Exposure to Random Positioning Machine Alters the Mineralization Process and PTX3 Expression in the SAOS-2 Cell Line

| Field | Detail |
|---|---|
| **Journal** | Life |
| **DOI** | [10.3390/life12050610](https://doi.org/10.3390/life12050610) |
| **Paper Link** | [https://doi.org/10.3390/life12050610](https://doi.org/10.3390/life12050610) |
| **Details** | SAOS-2 human osteosarcoma cell line; two conditions (OC- and OC+) each compared between normogravity and 5-day RPM exposure; viability assays n=25 from N=5 experiments; calcification/mineralization... |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-12"></a>
### 📄 Paper #12 — Apoptosis Induction and Alteration of Cell Adherence in Human Lung Cancer Cells under Simulated Microgravity

| Field | Detail |
|---|---|
| **Journal** | International Journal of Molecular Sciences |
| **DOI** | [10.3390/ijms20143601](https://doi.org/10.3390/ijms20143601) |
| **Paper Link** | [https://doi.org/10.3390/ijms20143601](https://doi.org/10.3390/ijms20143601) |
| **Details** | Experiments performed 6 times independently (results as means ± SD); TUNEL assay counted on 10 fields of view at 100x magnification per group; qRT-PCR samples measured in triplicate; western blot p... |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-13"></a>
### 📄 Paper #13 — Guidelines for use of the random positioning machine as a reduced-gravity analog

| Field | Detail |
|---|---|
| **Journal** | Scientific Reports |
| **DOI** | [10.1038/s41598-026-39316-7](https://doi.org/10.1038/s41598-026-39316-7) |
| **Paper Link** | [https://doi.org/10.1038/s41598-026-39316-7](https://doi.org/10.1038/s41598-026-39316-7) |
| **Details** | Comparison across 11 different rotation rate combinations (Table 1) for 40-minute average g-level; g-level mapping across rotation rates 1-70°/s for 25 minutes (Figure 3a-b); g-level at 7 different... |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-14"></a>
### 📄 Paper #14 — Changes in the Surface Expression of Intercellular Adhesion Molecule 3, the Induction of Apoptosis, and the Inhibition of Cell-Cycle Progression of Human Multidrug-Resistant Jurkat/A4 Cells Exposed to a Random Positioning Machine

| Field | Detail |
|---|---|
| **Journal** | International Journal of Molecular Sciences |
| **DOI** | [10.3390/ijms21030855](https://doi.org/10.3390/ijms21030855) |
| **Paper Link** | [https://doi.org/10.3390/ijms21030855](https://doi.org/10.3390/ijms21030855) |
| **Details** | Jurkat (n=7 for viability; n=3 for apoptosis; n=5 for cell cycle; n=5 for ICAM-3; n=3 for western blot) and Jurkat/A4 cells under RPM vs static 1g control conditions; multiple timepoints: 24, 48, 7... |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-15"></a>
### 📄 Paper #15 — Design of a novel 3DOF clinostat to produce microgravity for bioengineering applications

| Field | Detail |
|---|---|
| **Journal** | 2018 IEEE XXV International Conference on Electronics, Electrical Engineering and Computing (INTERCON) |
| **DOI** | [10.1109/INTERCON.2018.8526401](https://doi.org/10.1109/INTERCON.2018.8526401) |
| **Paper Link** | [https://doi.org/10.1109/INTERCON.2018.8526401](https://doi.org/10.1109/INTERCON.2018.8526401) |
| **Details** | Not available. This is a conference paper based on simulations. Full methodology and cellular dataset details require the paywalled text. |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-16"></a>
### 📄 Paper #16 — Characterization of the random positioning machine as a microgravity simulator for biological applications

| Field | Detail |
|---|---|
| **Journal** | PLoS ONE |
| **DOI** | [10.1371/journal.pone.0351320](https://doi.org/10.1371/journal.pone.0351320) |
| **Paper Link** | [https://doi.org/10.1371/journal.pone.0351320](https://doi.org/10.1371/journal.pone.0351320) |
| **Details** | MIMU angular velocity recordings: 5 recordings of 10 min each for Mode A (stochastic mode); computational simulations: 500 iterations of 5-hour simulated experiments per angular velocity value for ... |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-17"></a>
### 📄 Paper #17 — Impact of the rotational speed and counter electrode configuration on the performance of a rotating disc bioelectrochemical reactor (RDBER) operated as microbial electrolysis cell

| Field | Detail |
|---|---|
| **Journal** | bioRxiv preprint |
| **DOI** | [10.1101/2025.03.06.641858](https://doi.org/10.1101/2025.03.06.641858) |
| **Paper Link** | [https://doi.org/10.1101/2025.03.06.641858](https://doi.org/10.1101/2025.03.06.641858) |
| **Details** | 10 L RDBER batch experiments using a co-culture of Shewanella oneidensis and Geobacter sulfurreducens under varied rotational speeds and counter electrode configurations. |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-18"></a>
### 📄 Paper #18 — Effects of angular frequency during clinorotation on mesenchymal stem cell morphology and migration

| Field | Detail |
|---|---|
| **Journal** | npj Microgravity |
| **DOI** | [10.1038/npjmgrav.2015.7](https://doi.org/10.1038/npjmgrav.2015.7) |
| **Paper Link** | [https://doi.org/10.1038/npjmgrav.2015.7](https://doi.org/10.1038/npjmgrav.2015.7) |
| **Details** | Human mesenchymal stem cells from Lonza, PT-2501, confirmed mycoplasma-free; experimental groups at 0, 30, 60, and 75 rpm over 8 h; NGF chemotaxis condition used 100 ng/ml NGF gradients. |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-19"></a>
### 📄 Paper #19 — Simulated Microgravity and 3D Culture Enhance Induction, Viability, Proliferation and Differentiation of Cardiac Progenitors from Human Pluripotent Stem Cells

| Field | Detail |
|---|---|
| **Journal** | Scientific Reports (Sci Rep) |
| **DOI** | [10.1038/srep30956](https://doi.org/10.1038/srep30956) |
| **Paper Link** | [https://doi.org/10.1038/srep30956](https://doi.org/10.1038/srep30956) |
| **Details** | Human pluripotent stem cells including IMR-90 induced pluripotent stem cells and H7 and H9 human embryonic stem cells. |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-20"></a>
### 📄 Paper #20 — LIF-Free Embryonic Stem Cell Culture in Simulated Microgravity

| Field | Detail |
|---|---|
| **Journal** | PLoS ONE |
| **DOI** | [10.1371/journal.pone.0006343](https://doi.org/10.1371/journal.pone.0006343) |
| **Paper Link** | [https://doi.org/10.1371/journal.pone.0006343](https://doi.org/10.1371/journal.pone.0006343) |
| **Details** | Mouse ES cell line BRC6 from RIKEN BRC CELL BANK, derived from C57BL/6 mice. Experimental groups: normal 1G culture and simulated microgravity 3D-clinostat culture. Teratoma assay used C57BL/6 mice. |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-21"></a>
### 📄 Paper #21 — Effects of microgravity on cell cytoskeleton and embryogenesis

| Field | Detail |
|---|---|
| **Journal** | International Journal of Developmental Biology |
| **DOI** | [10.1387/ijdb.052077sc](https://doi.org/10.1387/ijdb.052077sc) |
| **Paper Link** | [https://doi.org/10.1387/ijdb.052077sc](https://doi.org/10.1387/ijdb.052077sc) |
| **Details** | Published spaceflight and clinostat studies on embryos, cells, and tissues in microgravity or altered gravity; no original experimental dataset is described in the provided text. |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-22"></a>
### 📄 Paper #22 — Effects of Simulated Microgravity on Human Umbilical Vein Endothelial Cell Angiogenesis and Role of the PI3K-Akt-eNOS Signal Pathway

| Field | Detail |
|---|---|
| **Journal** | PLoS ONE |
| **DOI** | [10.1371/journal.pone.0040365](https://doi.org/10.1371/journal.pone.0040365) |
| **Paper Link** | [https://doi.org/10.1371/journal.pone.0040365](https://doi.org/10.1371/journal.pone.0040365) |
| **Details** | Human umbilical vein endothelial cells (HUVEC-C), purchased from ATCC; cells generally from passages two to three. |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-23"></a>
### 📄 Paper #23 — Enhancement of Osteogenic Differentiation and Proliferation in Human Mesenchymal Stem Cells by a Modified Low Intensity Ultrasound Stimulation under Simulated Microgravity

| Field | Detail |
|---|---|
| **Journal** | PLoS ONE |
| **DOI** | [10.1371/journal.pone.0073914](https://doi.org/10.1371/journal.pone.0073914) |
| **Paper Link** | [https://doi.org/10.1371/journal.pone.0073914](https://doi.org/10.1371/journal.pone.0073914) |
| **Details** | Adipose-derived human mesenchymal stem cells and human fetal osteoblasts cultured in Opticell cartridges; Ad-hMSC groups n=4/group and osteoblast groups n=4/group. |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-24"></a>
### 📄 Paper #24 — Duration of simulated microgravity affects the differentiation of mesenchymal stem cells

| Field | Detail |
|---|---|
| **Journal** | Molecular Medicine Reports |
| **DOI** | [10.3892/mmr.2017.6357](https://doi.org/10.3892/mmr.2017.6357) |
| **Paper Link** | [https://doi.org/10.3892/mmr.2017.6357](https://doi.org/10.3892/mmr.2017.6357) |
| **Details** | Adult rat MSCs isolated from 10 male Wistar rats, 2 weeks old; cells seeded at 1x10^5 cells on 2.5x2.5 cm coverslips for clinostat experiments. |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-25"></a>
### 📄 Paper #25 — Mechanisms of three-dimensional growth of thyroid cells during long-term simulated microgravity

| Field | Detail |
|---|---|
| **Journal** | Scientific Reports |
| **DOI** | [10.1038/srep16691](https://doi.org/10.1038/srep16691) |
| **Paper Link** | [https://doi.org/10.1038/srep16691](https://doi.org/10.1038/srep16691) |
| **Details** | Human Nthy-ori 3-1 normal thyroid follicular epithelial cells and FTC-133 poorly differentiated follicular thyroid cancer cells; static 1g controls; RPM adherent cells; RPM multicellular spheroids;... |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-26"></a>
### 📄 Paper #26 — Effect of Simulated Microgravity on E. coli K12 MG1655 Growth and Gene Expression

| Field | Detail |
|---|---|
| **Journal** | PLoS ONE |
| **DOI** | [10.1371/journal.pone.0057860](https://doi.org/10.1371/journal.pone.0057860) |
| **Paper Link** | [https://doi.org/10.1371/journal.pone.0057860](https://doi.org/10.1371/journal.pone.0057860) |
| **Details** | Three separate vessels were maintained under each condition for simulated microgravity and normal gravity experiments. Growth curves were plotted from data of three experiments conducted separately... |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-27"></a>
### 📄 Paper #27 — Simulated microgravity triggers epithelial mesenchymal transition in human keratinocytes

| Field | Detail |
|---|---|
| **Journal** | Scientific Reports |
| **DOI** | [10.1038/s41598-017-00602-0](https://doi.org/10.1038/s41598-017-00602-0) |
| **Paper Link** | [https://doi.org/10.1038/s41598-017-00602-0](https://doi.org/10.1038/s41598-017-00602-0) |
| **Details** | Human immortalized HaCaT keratinocytes; no dataset size stated in provided text. |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-28"></a>
### 📄 Paper #28 — Effects of spaceflight and simulated microgravity on microbial growth and secondary metabolism

| Field | Detail |
|---|---|
| **Journal** | Military Medical Research |
| **DOI** | [10.1186/s40779-018-0162-9](https://doi.org/10.1186/s40779-018-0162-9) |
| **Paper Link** | [https://doi.org/10.1186/s40779-018-0162-9](https://doi.org/10.1186/s40779-018-0162-9) |
| **Details** | Published studies of microbial responses to spaceflight, simulated microgravity, low-shear modeled microgravity, clinorotation, and other ground-based microgravity simulators; no original dataset s... |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-29"></a>
### 📄 Paper #29 — The influence of spaceflight and simulated microgravity on bacterial motility and chemotaxis

| Field | Detail |
|---|---|
| **Journal** | npj Microgravity |
| **DOI** | [10.1038/s41526-021-00135-x](https://doi.org/10.1038/s41526-021-00135-x) |
| **Paper Link** | [https://doi.org/10.1038/s41526-021-00135-x](https://doi.org/10.1038/s41526-021-00135-x) |
| **Details** | Published ground-based and spaceflight studies on microbial microgravity responses, focusing on selected Gram-negative bacterial strains: Escherichia coli, Salmonella enterica serovar Typhimurium, ... |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-30"></a>
### 📄 Paper #30 — Effects of Simulated Microgravity on Ultrastructure and Apoptosis of Choroidal Vascular Endothelial Cells

| Field | Detail |
|---|---|
| **Journal** | Frontiers in Physiology |
| **DOI** | [10.3389/fphys.2020.577325](https://doi.org/10.3389/fphys.2020.577325) |
| **Paper Link** | [https://doi.org/10.3389/fphys.2020.577325](https://doi.org/10.3389/fphys.2020.577325) |
| **Details** | Human choroidal vascular endothelial cell line HL-CELL-0126 cultured under normal gravity or simulated microgravity; no sample size stated in provided text. |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-31"></a>
### 📄 Paper #31 — Simulated microgravity enhances CDDP-induced apoptosis signal via p53-independent mechanisms in cancer cells

| Field | Detail |
|---|---|
| **Journal** | PLOS ONE |
| **DOI** | [10.1371/journal.pone.0219363](https://doi.org/10.1371/journal.pone.0219363) |
| **Paper Link** | [https://doi.org/10.1371/journal.pone.0219363](https://doi.org/10.1371/journal.pone.0219363) |
| **Details** | All relevant data are stated to be within the manuscript and Supporting Information files. Experimental data include HepG2 cell-count assays with n = 5, quantitative RT-PCR averaged from four indep... |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-32"></a>
### 📄 Paper #32 — Effect of miR-27b-5p on apoptosis of human vascular endothelial cells induced by simulated microgravity

| Field | Detail |
|---|---|
| **Journal** | ApoptosisApoptosis: An International Journal on Programmed Cell Death |
| **DOI** | [10.1007/s10495-019-01580-6](https://doi.org/10.1007/s10495-019-01580-6) |
| **Paper Link** | [https://doi.org/10.1007/s10495-019-01580-6](https://doi.org/10.1007/s10495-019-01580-6) |
| **Details** | RNA-sequencing and qRT-PCR data from HUVECs cultured under 48 h simulated microgravity compared with rotation control groups; additional apoptosis and target-validation assays involving miR-1268a, ... |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-33"></a>
### 📄 Paper #33 — A New System for Three-dimensional Clinostat Synchronized X-irradiation with a High-speed Shutter for Space Radiation Research

| Field | Detail |
|---|---|
| **Journal** | Biological Sciences in Space |
| **DOI** | [10.2187/bss.30.8](https://doi.org/10.2187/bss.30.8) |
| **Paper Link** | [https://doi.org/10.2187/bss.30.8](https://doi.org/10.2187/bss.30.8) |
| **Details** | Gafchromic film dosimetry data for evaluating X-irradiation accuracy under standing and 3D clinostat rotation conditions; no cellular dataset stated in provided text. |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-34"></a>
### 📄 Paper #34 — Customized small-sized clinostat using 3D printing and gas-permeable polydimethylsiloxane culture dish

| Field | Detail |
|---|---|
| **Journal** | NPJ microgravity |
| **DOI** | [10.1038/s41526-023-00311-1](https://doi.org/10.1038/s41526-023-00311-1) |
| **Paper Link** | [https://doi.org/10.1038/s41526-023-00311-1](https://doi.org/10.1038/s41526-023-00311-1) |
| **Details** | Ovarian cancer cell lines OV-90, TOV-21G, and Caov-3; three-axis accelerometer measurements; tensile test data and static structural simulation results mentioned but not numerically detailed in the... |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-35"></a>
### 📄 Paper #35 — Simulation of Microgravity by Magnetic Levitation and Random Positioning: Effect on Human A431 Cell Morphology

| Field | Detail |
|---|---|
| **Journal** | Microgravity Science and Technology |
| **DOI** | [10.1007/s12217-010-9185-x](https://doi.org/10.1007/s12217-010-9185-x) |
| **Paper Link** | [https://doi.org/10.1007/s12217-010-9185-x](https://doi.org/10.1007/s12217-010-9185-x) |
| **Details** | Human epidermoid A431 cells grown on glass coverslips; cells used for EGF stimulation and RPM experiments were serum-starved for 24 h. Culture conditions included 37°C, CO2-independent medium, 7.5%... |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-36"></a>
### 📄 Paper #36 — Simulated microgravity inhibits osteogenic differentiation of mesenchymal stem cells via depolymerizing F-actin to impede TAZ nuclear translocation

| Field | Detail |
|---|---|
| **Journal** | Scientific Reports |
| **DOI** | [10.1038/srep30322](https://doi.org/10.1038/srep30322) |
| **Paper Link** | [https://doi.org/10.1038/srep30322](https://doi.org/10.1038/srep30322) |
| **Details** | Experimental in vitro data from rat bone marrow mesenchymal stem cells, including cell viability, apoptosis, F-actin imaging/fractal analysis, ALP activity, alizarin red staining, Runx2 real-time P... |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-37"></a>
### 📄 Paper #37 — 3D cell culture using a clinostat reproduces microgravity-induced skin changes

| Field | Detail |
|---|---|
| **Journal** | npj Microgravity |
| **DOI** | [10.1038/s41526-021-00148-6](https://doi.org/10.1038/s41526-021-00148-6) |
| **Paper Link** | [https://doi.org/10.1038/s41526-021-00148-6](https://doi.org/10.1038/s41526-021-00148-6) |
| **Details** | Experimental in vitro cell culture data from HaCaT keratinocytes, Hs27 fibroblasts, and HUVECs. Figure 1 reports HUVEC arrangement thickness with n = 8–9. Figure 2 reports spheroid viability and th... |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-38"></a>
### 📄 Paper #38 — Common Effects on Cancer Cells Exerted by a Random Positioning Machine and a 2D Clinostat

| Field | Detail |
|---|---|
| **Journal** | PLoS ONE |
| **DOI** | [10.1371/journal.pone.0135157](https://doi.org/10.1371/journal.pone.0135157) |
| **Paper Link** | [https://doi.org/10.1371/journal.pone.0135157](https://doi.org/10.1371/journal.pone.0135157) |
| **Details** | Two human follicular thyroid cancer cell lines: ML-1 and RO82-W-1. Data availability statement: all relevant data are within the paper. |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-39"></a>
### 📄 Paper #39 — Differential gene expression profile and altered cytokine secretion of thyroid cancer cells in space

| Field | Detail |
|---|---|
| **Journal** | The FASEB Journal |
| **DOI** | [10.1096/fj.13-243287](https://doi.org/10.1096/fj.13-243287) |
| **Paper Link** | [https://doi.org/10.1096/fj.13-243287](https://doi.org/10.1096/fj.13-243287) |
| **Details** | FTC-133 poorly differentiated thyroid cancer cells; 128 secreted cytokines profiled; microarray transcript data after 22 s parabolic flight microgravity and after 10 d on RPM or in space. |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-40"></a>
### 📄 Paper #40 — Spaceflight and simulated microgravity cause a significant reduction of key gene expression in early T-cell activation.

| Field | Detail |
|---|---|
| **Journal** | American Journal of Physiology. Regulatory Integrative and Comparative Physiology |
| **DOI** | [10.1152/ajpregu.00449.2014](https://doi.org/10.1152/ajpregu.00449.2014) |
| **Paper Link** | [https://doi.org/10.1152/ajpregu.00449.2014](https://doi.org/10.1152/ajpregu.00449.2014) |
| **Details** | Significantly increased gene expression in activated 1g/ground control samples for all six examined genes (Il2, Il2rα, Ifnγ, Tagap, Iigp1, Slamf1), with significant suppression of this activation-i... |
| **Type of Dataset** | Numerical (Microarray, CEL/TXT) |
| **Dataset Link** | [https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE33801](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE33801) |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-41"></a>
### 📄 Paper #41 — Proteome Analysis of Human Follicular Thyroid Cancer Cells Exposed to the Random Positioning Machine

| Field | Detail |
|---|---|
| **Journal** | International Journal of Molecular Sciences |
| **DOI** | [10.3390/ijms18030546](https://doi.org/10.3390/ijms18030546) |
| **Paper Link** | [https://doi.org/10.3390/ijms18030546](https://doi.org/10.3390/ijms18030546) |
| **Details** | FTC-133 human follicular thyroid carcinoma cells; 5 samples analyzed by mass spectrometry (12 T25 flasks total, pooled in groups of 3 per condition); Western blot validation used n=5 independent re... |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-42"></a>
### 📄 Paper #42 — Simulated Microgravity Remodels Extracellular Matrix of Osteocommitted Mesenchymal Stromal Cells

| Field | Detail |
|---|---|
| **Journal** | International Journal of Molecular Sciences |
| **DOI** | [10.3390/ijms22115428](https://doi.org/10.3390/ijms22115428) |
| **Paper Link** | [https://doi.org/10.3390/ijms22115428](https://doi.org/10.3390/ijms22115428) |
| **Details** | Not publicly available — the paper's own Data Availability Statement states 'Not applicable.' Human adipose-tissue-derived MSCs (intact and osteocommitted, minimum 3 independent experiments per ass... |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-43"></a>
### 📄 Paper #43 — Proteomic profile of cultured human endothelial cells after exposition to simulated microgravity

| Field | Detail |
|---|---|
| **Journal** | Acta Astronautica |
| **DOI** | [10.1016/j.actaastro.2020.10.014](https://doi.org/10.1016/j.actaastro.2020.10.014) |
| **Paper Link** | [https://doi.org/10.1016/j.actaastro.2020.10.014](https://doi.org/10.1016/j.actaastro.2020.10.014) |
| **Details** | Not confirmed — full text inaccessible; HUVEC cells under static vs. 24h RPM-simulated microgravity conditions, analyzed via LC-MS; exact sample sizes/replicates not available without full-text acc... |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-44"></a>
### 📄 Paper #44 — Growth of Endothelial Cells in Space and in Simulated Microgravity - a Comparison on the Secretory Level.

| Field | Detail |
|---|---|
| **Journal** | Cellular Physiology and Biochemistry |
| **DOI** | [10.33594/000000071](https://doi.org/10.33594/000000071) |
| **Paper Link** | [https://doi.org/10.33594/000000071](https://doi.org/10.33594/000000071) |
| **Details** | EA.hy926 cells; spaceflight samples (n=4 flight hardware units per timepoint, 5d and 12d real µg); RPM samples (n=5 slide flasks per group, matched 7d/14d time-temperature protocol); 1g ground cont... |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-45"></a>
### 📄 Paper #45 — Neocartilage Formation in 1 g, Simulated, and Microgravity Environments: Implications for Tissue Engineering

| Field | Detail |
|---|---|
| **Journal** | Tissue Engineering. Part A |
| **DOI** | [10.1089/ten.tea.2008.0624](https://doi.org/10.1089/ten.tea.2008.0624) |
| **Paper Link** | [https://doi.org/10.1089/ten.tea.2008.0624](https://doi.org/10.1089/ten.tea.2008.0624) |
| **Details** | Not fully confirmed — full text inaccessible. Porcine chondrocytes seeded into cylindrical culture chambers (n=8 total across ISS, RPM, and 1g conditions); 16-day culture period; histology, immunoh... |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-46"></a>
### 📄 Paper #46 — Gene Expression Profiles of 2T3 Preosteoblasts in Microgravity Analog Systems: Comparison of the Random Positioning Machine and the Rotating Wall Vessel Bioreactor

| Field | Detail |
|---|---|
| **Journal** | The FASEB Journal |
| **DOI** | [10.1096/fasebj.20.5.A1250-a](https://doi.org/10.1096/fasebj.20.5.A1250-a) |
| **Paper Link** | [https://doi.org/10.1096/fasebj.20.5.A1250-a](https://doi.org/10.1096/fasebj.20.5.A1250-a) |
| **Details** | 2T3 murine preosteoblast cell line; RWV exposure (22 rpm, 3 days) vs. static 1g controls; microarray n=3 per group (Affymetrix Mouse 430 2.0, ~40,000 genes); ALP activity assay n=6; ALP mRNA/PCR va... |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-47"></a>
### 📄 Paper #47 — Plastid position in Arabidopsis columella cells is similar in microgravity and on a random-positioning machine

| Field | Detail |
|---|---|
| **Journal** | Planta |
| **DOI** | [10.1007/s004250000302](https://doi.org/10.1007/s004250000302) |
| **Paper Link** | [https://doi.org/10.1007/s004250000302](https://doi.org/10.1007/s004250000302) |
| **Details** | Arabidopsis thaliana seedling root tips; four gravity conditions (1g Earth, 2D clinostat 1 rpm, 3D clinostat/RPM, spaceflight); columella cells classified into meristem, flanking, central, and peri... |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-48"></a>
### 📄 Paper #48 — Functional alterations of root meristematic cells of <em>Arabidopsis thaliana</em> induced by a simulated microgravity environment

| Field | Detail |
|---|---|
| **Journal** | Journal of Plant Physiology |
| **DOI** | [10.1016/j.jplph.2016.09.011](https://doi.org/10.1016/j.jplph.2016.09.011) |
| **Paper Link** | [https://doi.org/10.1016/j.jplph.2016.09.011](https://doi.org/10.1016/j.jplph.2016.09.011) |
| **Details** | Contacted the authors but they said that they don't have the dataset, as the research paper was written 20 years ago. |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-49"></a>
### 📄 Paper #49 — Novel, Moon and Mars, partial gravity simulation paradigms and their effects on the balance between cell growth and cell proliferation during early plant development

| Field | Detail |
|---|---|
| **Journal** | npj Microgravity |
| **DOI** | [10.1038/s41526-018-0041-4](https://doi.org/10.1038/s41526-018-0041-4) |
| **Paper Link** | [https://doi.org/10.1038/s41526-018-0041-4](https://doi.org/10.1038/s41526-018-0041-4) |
| **Details** | Arabidopsis thaliana seedlings (4-day-old, root meristematic cells); four/five conditions tested: simulated Moon gravity (0.17g) via RPM-HW and RPM-SW, simulated Mars gravity (0.38g) via RPM-HW and... |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-50"></a>
### 📄 Paper #50 — Gravity-Related Immunological Changes in Human Whole Blood Cultured Under Simulated Microgravity Using an In Vitro Cytokine Release Assay

| Field | Detail |
|---|---|
| **Journal** | Journal of Interferon and Cytokine Research |
| **DOI** | [10.1089/jir.2017.0065](https://doi.org/10.1089/jir.2017.0065) |
| **Paper Link** | [https://doi.org/10.1089/jir.2017.0065](https://doi.org/10.1089/jir.2017.0065) |
| **Details** | Human whole blood samples from n=10 subjects; cultured under RPM-simulated gravity (s-G) vs. control conditions; four cytokines measured (IL-2, IFN-γ, TNF-α, IL-10) in response to four stimuli (bac... |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-51"></a>
### 📄 Paper #51 — Cold stress during room temperature housing alters skeletal response to simulated microgravity (hindlimb unloading) in growing female C57BL6 mice

| Field | Detail |
|---|---|
| **Journal** | Biochimie |
| **DOI** | [10.1016/j.biochi.2022.12.009](https://doi.org/10.1016/j.biochi.2022.12.009) |
| **Paper Link** | [https://doi.org/10.1016/j.biochi.2022.12.009](https://doi.org/10.1016/j.biochi.2022.12.009) |
| **Details** | HLU-induced cortical bone loss in femur: present at both housing temperatures, but of greater magnitude at 22°C than at 32°C (exact percentages not confirmable without full-text access); cancellous... |
| **Type of Dataset** | Numerical (micro-CT, XLSX/CSV) |
| **Dataset Link** | [https://osdr.nasa.gov/bio/repo/data/studies/OSD-980](https://osdr.nasa.gov/bio/repo/data/studies/OSD-980) |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-52"></a>
### 📄 Paper #52 — Long-term osteogenic differentiation of human bone marrow stromal cells in simulated microgravity: novel proteins sighted

| Field | Detail |
|---|---|
| **Journal** | Cellular and Molecular Life Sciences |
| **DOI** | [10.1007/s00018-022-04553-2](https://doi.org/10.1007/s00018-022-04553-2) |
| **Paper Link** | [https://doi.org/10.1007/s00018-022-04553-2](https://doi.org/10.1007/s00018-022-04553-2) |
| **Details** | 4,312 total protein groups (PGs) identified; 481 DAPGs across four experimental classes after ANOVA (p<0.05) and Tukey's HSD post-hoc; PCA: PC1 explains 35% of variance, PC2 24% (59% combined); GO-... |
| **Type of Dataset** | Proteomics (LC-MS/MS, RAW) |
| **Dataset Link** | [https://www.ebi.ac.uk/pride/archive/projects/PXD033475](https://www.ebi.ac.uk/pride/archive/projects/PXD033475) |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-53"></a>
### 📄 Paper #53 — Effects of simulated microgravity on the expression profiles of RNA during osteogenic differentiation of human bone marrow mesenchymal stem cells

| Field | Detail |
|---|---|
| **Journal** | Cell Proliferation |
| **DOI** | [10.1111/cpr.12539](https://doi.org/10.1111/cpr.12539) |
| **Paper Link** | [https://doi.org/10.1111/cpr.12539](https://doi.org/10.1111/cpr.12539) |
| **Details** | 837 DEGs identified at day 2 (SMG vs. NG); 399 DEGs at day 7; 894 DEGs at day 14; proliferation inhibited at day 2 (early stage); osteogenic differentiation inhibited and adipogenic differentiation... |
| **Type of Dataset** | RNA-seq (TXT/FASTQ) |
| **Dataset Link** | [https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE114117](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE114117) |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-54"></a>
### 📄 Paper #54 — Simulated Microgravity Modulates Differentiation Processes of Embryonic Stem Cells

| Field | Detail |
|---|---|
| **Journal** | Cellular Physiology and Biochemistry |
| **DOI** | [10.1159/000443090](https://doi.org/10.1159/000443090) |
| **Paper Link** | [https://doi.org/10.1159/000443090](https://doi.org/10.1159/000443090) |
| **Details** | Not publicly available — no repository accession found; CGR8 mESC line; microarray analysis based on three independent experiments; qRT-PCR validation from a minimum of three biological replicates;... |
| **Type of Dataset** | *Not confirmed* |
| **Dataset Link** | *Not available yet — to be added* |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-55"></a>
### 📄 Paper #55 — Proteomic analysis of the effects of simulated microgravity in human gastric mucosal cells

| Field | Detail |
|---|---|
| **Journal** | Life Sciences in Space Research |
| **DOI** | [10.1016/j.lssr.2021.10.001](https://doi.org/10.1016/j.lssr.2021.10.001) |
| **Paper Link** | [https://doi.org/10.1016/j.lssr.2021.10.001](https://doi.org/10.1016/j.lssr.2021.10.001) |
| **Details** | 394 total differentially regulated proteins after 3 days of simulated microgravity (202 upregulated, 192 downregulated); 542 total differentially regulated proteins after 7 days (286 upregulated, 2... |
| **Type of Dataset** | Proteomics (LC-MS/MS, RAW) |
| **Dataset Link** | [https://www.ebi.ac.uk/pride/archive/projects/PXD026675](https://www.ebi.ac.uk/pride/archive/projects/PXD026675) |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-56"></a>
### 📄 Paper #56 — Simulated Microgravity Modulates Focal Adhesion Gene Expression in Human Neural Stem Progenitor Cells

| Field | Detail |
|---|---|
| **Journal** | Life |
| **DOI** | [10.3390/life12111827](https://doi.org/10.3390/life12111827) |
| **Paper Link** | [https://doi.org/10.3390/life12111827](https://doi.org/10.3390/life12111827) |
| **Details** | 28 DEGs at 6h simulated microgravity (FDR<0.1, |Log2FC|>0.58); 207 DEGs at 24h; only 53 DEGs when comparing across all 12 samples (low + high density) at 24h; floating aggregate formation: <10% of ... |
| **Type of Dataset** | Numerical (Gene expression, XLSX) |
| **Dataset Link** | Dataset available as ZIP (see repo /data folder) |

[⬆ Back to Dataset Table](#7--dataset-table)

---


<a name="paper-57"></a>
### 📄 Paper #57 — Transcriptomic response of bioengineered human cartilage to parabolic flight microgravity is sex-dependent

| Field | Detail |
|---|---|
| **Journal** | npj Microgravity |
| **DOI** | [10.1038/s41526-023-00255-6](https://doi.org/10.1038/s41526-023-00255-6) |
| **Paper Link** | [https://doi.org/10.1038/s41526-023-00255-6](https://doi.org/10.1038/s41526-023-00255-6) |
| **Details** | 410 significant DEGs (p<0.05, |FC|>2) between ground control and laboratory control groups; 30 significant DEGs in parabolic flight vs. ground control (all donors combined); top DEG: KTI12, 29.7-fo... |
| **Type of Dataset** | RNA-seq (TXT/FASTQ) |
| **Dataset Link** | [https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE206008](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE206008) |

[⬆ Back to Dataset Table](#7--dataset-table)

---

<div align="center">

*Grounded in literature. Built for orbit.* 🛰️

</div>
