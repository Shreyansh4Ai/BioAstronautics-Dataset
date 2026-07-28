# 🦴 NASA OSDR OSD-980: Cold Stress and Simulated Microgravity Skeletal Response

## Study Overview

| Field | Details |
|---|---|
| **Study ID** | **OSD-980** |
| **NASA LSDS ID** | LSDS-178 |
| **NASA Task ID** | 19-675 |
| **Paper Title** | Cold stress during room temperature housing alters skeletal response to simulated microgravity (hindlimb unloading) in growing female C57BL6 mice |
| **Journal** | *Biochimie* (Volume 210, July 2023, Pages 61–70) |
| **DOI** | [10.1016/j.biochi.2022.12.009](https://doi.org/10.1016/j.biochi.2022.12.009) |
| **OSDR Link** | [https://osdr.nasa.gov/bio/repo/data/studies/OSD-980](https://osdr.nasa.gov/bio/repo/data/studies/OSD-980) |
| **Authors** | Carmen P. Wong, Adam J. Branscum, Aidan R. Fichter, Jennifer Sargent, Urszula T. Iwaniec, Russell T. Turner |
| **Organism** | *Mus musculus* (Female C57BL/6 mice) |
| **Model System** | Ground-based Hindlimb Unloading (HLU) & Ambient Housing Temperature ($22^\circ\text{C}$ vs. $32^\circ\text{C}$) |
| **Assay Types** | Micro-Computed Tomography ($\mu\text{CT}$) & Necropsy Mass Metrics |
| **Data Format** | Microsoft Excel (`.xlsx`) |
| **License** | Open Access / CC-BY 4.0 |

---

## Background & Scientific Rationale

Standard laboratory rodent housing temperatures (~$22^\circ\text{C}$ / $72^\circ\text{F}$) are significantly below thermoneutrality for mice (~$30\text{--}32^\circ\text{C}$ / $86\text{--}90^\circ\text{F}$). Room-temperature housing places rodents under chronic mild cold stress, elevating metabolic output and triggering sympathetically mediated thermogenesis. 

In spaceflight and simulated microgravity research (such as the standard ground-based **Hindlimb Unloading [HLU]** model), cold-induced changes in metabolic rate and sympathetic signaling can interact with or obscure mechanical unloading-induced bone loss.

This study evaluated the hypothesis that housing mice at thermoneutrality ($32^\circ\text{C}$) alters the skeletal response to hindlimb unloading compared to sub-chronically cold-stressed mice housed at standard room temperature ($22^\circ\text{C}$). High-resolution micro-computed tomography ($\mu\text{CT}$) was performed on the femur and humerus to map cortical geometry and cancellous trabecular micro-architecture across skeletal sites.

---

## Experimental Design & Groups

- **Animal Model**: Growing female C57BL/6 mice
- **Housing Temperature Conditions**:
  - `22°C`: Standard laboratory room temperature (sub-chronic cold stress)
  - `32°C`: Thermoneutral zone housing
- **Unloading & Control Groups**:
  - `Baseline`: Sacrificed at Day 0 for reference initial state
  - `Control`: Standard ambulatory housing
  - `HLU`: Hindlimb Unloaded (simulated microgravity model) for 14 days

### Skeletal Regions Evaluated
- **Femur**: Total bone, Diaphysis Cortical Bone, Distal Metaphysis Cancellous Bone, Distal Epiphysis Cancellous Bone
- **Humerus**: Total bone, Diaphysis Cortical Bone, Proximal Metaphysis Cancellous Bone, Distal Epiphysis Cancellous Bone

---

## File Inventory & Description

The primary dataset file is stored within this directory:

- **[`LSDS-178_microCT_19-675_Wong 2023_ Biochimie_For Deposit_12-17-25.xlsx`](./LSDS-178_microCT_19-675_Wong%202023_%20Biochimie_For%20Deposit_12-17-25.xlsx)**

### Worksheet Layout

| Sheet Name | Description | Key Parameters |
|---|---|---|
| **`Table`** | Executive summary of experimental parameters & group means | Overall study metrics summary |
| **`Necropsy Body Weight`** | Animal body mass at harvest | Body weight (g) |
| **`Necropsy Uterus Weight`** | Uterine mass at harvest | Uterus weight (mg) |
| **`uCT_Femur Total`** | Overall femoral volumetric $\mu\text{CT}$ measurements | Femur total volume & structural indices |
| **`uCT_Femur Diaphysis Cortical`** | Femur midshaft cortical bone geometry | Cross-sectional vol, Cortical vol, Marrow vol, Cortical thickness, $I_{\text{polar}}$ |
| **`uCT_Femur Metaphysis Cancellous`** | Distal femur metaphysis trabecular bone | $\text{BV/TV}$, $\text{Conn.D}$, $\text{Tb.N}$, $\text{Tb.Th}$, $\text{Tb.Sp}$ |
| **`uCT_Femur Epiphysis Cancellous`** | Distal femur epiphysis trabecular bone | $\text{BV/TV}$, $\text{Conn.D}$, $\text{Tb.N}$, $\text{Tb.Th}$, $\text{Tb.Sp}$ |
| **`uCT_Humerus_Total`** | Overall humerus volumetric $\mu\text{CT}$ measurements | Humerus total volume & structural indices |
| **`uCT_Humerus Diaphysis Cortical`** | Humerus midshaft cortical bone geometry | Cross-sectional vol, Cortical vol, Marrow vol, Cortical thickness, $I_{\text{polar}}$ |
| **`uCT_Humerus Metaphysis Canc`** | Proximal humerus metaphysis trabecular bone | $\text{BV/TV}$, $\text{Conn.D}$, $\text{Tb.N}$, $\text{Tb.Th}$, $\text{Tb.Sp}$ |
| **`uCT_Humerus Epiphysis Canc`** | Distal humerus epiphysis trabecular bone | $\text{BV/TV}$, $\text{Conn.D}$, $\text{Tb.N}$, $\text{Tb.Th}$, $\text{Tb.Sp}$ |

---

## Data Dictionary / Variables

| Metric | Symbol / Abbreviation | Units | Description |
|---|---|---|---|
| **Bone Volume Fraction** | $\text{BV/TV}$ | $\%$ | Ratio of mineralized bone volume to total tissue volume |
| **Connectivity Density** | $\text{Conn.D}$ | $1/\text{mm}^3$ | Structural connectivity of the trabecular network per unit volume |
| **Trabecular Number** | $\text{Tb.N}$ | $1/\text{mm}$ | Average number of trabeculae intersected per unit length |
| **Trabecular Thickness** | $\text{Tb.Th}$ | $\mu\text{m}$ | Mean thickness of individual trabeculae |
| **Trabecular Spacing** | $\text{Tb.Sp}$ | $\mu\text{m}$ | Mean distance between individual trabeculae |
| **Cross-Sectional Volume** | $\text{TV}$ | $\text{mm}^3$ | Total tissue envelope volume |
| **Cortical Volume** | $\text{BV}$ | $\text{mm}^3$ | Volume of mineralized cortical shell |
| **Marrow Volume** | $\text{MV}$ | $\text{mm}^3$ | Volume of medullary bone cavity |
| **Cortical Thickness** | $\text{Ct.Th}$ | $\mu\text{m}$ | Average thickness of cortical bone shell |
| **Polar Moment of Inertia** | $I_{\text{polar}}$ | $\text{mm}^4$ | Estimate of torsional rigidity of the bone diaphysis |

---

## Citation & Attribution

If you utilize this dataset in your research or secondary analysis, please cite both the original publication and the NASA OSDR repository entry:

### Primary Publication
> Wong, C. P., Branscum, A. J., Fichter, A. R., Sargent, J., Iwaniec, U. T., & Turner, R. T. (2023). Cold stress during room temperature housing alters skeletal response to simulated microgravity (hindlimb unloading) in growing female C57BL6 mice. *Biochimie*, 210, 61–70. [https://doi.org/10.1016/j.biochi.2022.12.009](https://doi.org/10.1016/j.biochi.2022.12.009)

### Dataset Repository
> NASA Open Science Data Repository (OSDR). Study OSD-980: *Cold stress during room temperature housing alters skeletal response to simulated microgravity (hindlimb unloading) in growing female C57BL6 mice*. Available at: [https://osdr.nasa.gov/bio/repo/data/studies/OSD-980](https://osdr.nasa.gov/bio/repo/data/studies/OSD-980)

---

## License

This dataset is made available under the Open Access / CC-BY 4.0 license via NASA OSDR.
