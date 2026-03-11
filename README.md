<div align="center">

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=0D6EFD&center=true&vCenter=true&width=750&lines=%F0%9F%8C%B9+BISMILLAHIRRAHMANIRRAHIM+%F0%9F%8C%B9)

# 🧬 Hey, I'm Sedat!`

### *"Single-cell & spatial transcriptomics — from clustering to biological clarity."* 🔬

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00C4B4&center=true&vCenter=true&width=750&lines=Single-Cell+%26+Spatial+Transcriptomics+🧬;Cell+Annotation+%7C+Biomarker+Discovery+🔍;Reproducible+Pipelines+%7C+HPC+Systems+⚙️;From+Cellular+Noise+to+Biological+Clarity+📊)


</div>

---

## 🧫 About Me

```python
scientist = {
    "name"       : "Sedat Kacar, PhD",
    "username"   : "sedatkacar56",
    "role"       : "Computational Biologist & Single-Cell Systems Thinker 🧬",
    "location"   : "Indiana University School of Medicine",
    "focus"      : ["Single-cell RNA-seq", "Spatial Transcriptomics", 
                    "Biomarker Discovery", "Multi-omics Integration"],
    "tools"      : ["R/Seurat", "Python/Flask", "HPC/SLURM", "Nextflow"],
    "mindset"    : "Reproducible pipelines over black-box magic.",
    "currently"  : "Turning noisy cellular data into structured biological insight 📊",
    "side_quest" : "Building automation tools & exploring deterministic AI systems",
    "motto"      : "If the data is clean and the logic is sound, the biology will speak.",
    "fun_fact"   : "I debug Seurat objects and life decisions with equal intensity 🐛"
}

```

---

## 🔬 Tech Stack & Tools

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Bioinformatics Tools**

![Bioconductor](https://img.shields.io/badge/Bioconductor-3492C7?style=for-the-badge&logoColor=white)
![Biopython](https://img.shields.io/badge/Biopython-FFD43B?style=for-the-badge&logo=python&logoColor=black)
![Snakemake](https://img.shields.io/badge/Snakemake-00C4B4?style=for-the-badge&logoColor=white)
![Nextflow](https://img.shields.io/badge/Nextflow-23AA62?style=for-the-badge&logoColor=white)
![Galaxy](https://img.shields.io/badge/Galaxy-2C3E50?style=for-the-badge&logoColor=white)

**Data & ML**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4DBBD5?style=for-the-badge&logoColor=white)

**Dev & Cloud**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

</div>

---

## 🔬 Featured Projects

---

### WT vs Heme Rat Lung — Single-Cell RNA-seq (PARSE)

[![GitHub](https://img.shields.io/badge/GitHub-View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/sedatkacar56)

> *How does 4-week heme treatment rewire the endothelial landscape of the rat lung at single-cell resolution?*

**Problem**
Bulk RNA-seq masks the cell-type-specific transcriptional changes driven by heme — a potent vascular toxin released during hemolysis. Without single-cell resolution, the populations driving vascular injury remain invisible.

**Solution**
End-to-end scRNA-seq pipeline on PARSE Biosciences data (100K+ cells) comparing wild-type and heme-treated rat lung. Samples are integrated with RPCA batch correction, annotated via label transfer from a curated rat lung reference, and endothelial subtypes (gCapC, gCapD) are isolated for differential expression analysis.

| Step | Method |
|---|---|
| Integration | Reciprocal PCA (RPCA) via Seurat |
| Annotation | Label transfer from validated rat lung reference |
| Endothelial subtyping | Elhcall hierarchy: gCapC, gCapD, ELET |
| DEG analysis | Heme vs WT per endothelial subtype |

**Tech Stack**

![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![Seurat](https://img.shields.io/badge/Seurat-1A73E8?style=flat-square&logoColor=white)
![PARSE](https://img.shields.io/badge/PARSE_Biosciences-00C4B4?style=flat-square&logoColor=white)
![ggplot2](https://img.shields.io/badge/ggplot2-FF6B6B?style=flat-square&logoColor=white)

```
Platform:    PARSE Biosciences split-pool barcoding
Cells:       ~100,000+ across WT and Heme conditions
Integration: RPCA batch correction
Focus:       General capillary endothelial remodeling under heme stress
```

---

### Spatial Transcriptomics: Lymphedema Skin — Normal vs Treated

> *Can we map where gene expression changes happen inside tissue, not just which genes change?*

**Problem**
Standard scRNA-seq destroys spatial context — you lose exactly where in the tissue the transcriptional changes occur. In lymphedema, the spatial distribution of fibrotic and immune signals across skin layers is biologically critical.

**Solution**
End-to-end spatial transcriptomics pipeline on 10x Visium HD data (16µm bin resolution) from normal and treated mouse skin. Tissue sections are processed in both R (Seurat) and Python (Scanpy/Leiden), with spatially-resolved cluster maps, marker gene expression overlaid on histology images, and unsupervised clustering identifying region-specific signatures.

**Tech Stack**

![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![Seurat](https://img.shields.io/badge/Seurat-1A73E8?style=flat-square&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Scanpy](https://img.shields.io/badge/Scanpy-3B4CC0?style=flat-square&logoColor=white)
![10x Visium](https://img.shields.io/badge/10x_Visium_HD-FF6B35?style=flat-square&logoColor=white)

```
Platform:    10x Genomics Visium HD
Resolution:  16µm bins
Clustering:  Leiden (Python) + Seurat (R) parallel pipelines
Top markers: Col1a1, Col1a2, Col3a1, Sparc, Apoe, Apod
```

---

### seuratPassport — R Package

[![GitHub](https://img.shields.io/badge/GitHub-View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/sedatkacar56/seuratPassport)

> *You saved a Seurat object 3 months ago. What was it again? Which animal? Which condition? Was it normalized?*

**Problem**
Seurat objects accumulate silently: no internal record of what sample they came from, what processing steps were applied, or how they relate to other objects. Months later, a saved `.rds` file is uninterpretable without digging through old scripts.

**Solution**
An R package that stamps a persistent **passport** directly inside every Seurat object (`@misc$passport`). The passport stores animal metadata, experiment details, full lineage (parent → children), RDS registry numbers, and a timestamped processing log — and travels with the `.rds` file forever.

| Section | Contents |
|---|---|
| Identity | Object name, RDS number, creation date |
| Animal | Species, sex, age, condition, tissue |
| Experiment | Project, researcher, date, notes |
| Lineage | Parent object, children, full ancestry chain |
| Processing Log | Every step with cell count + timestamp |

**Tech Stack**

![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![Seurat](https://img.shields.io/badge/Seurat-1A73E8?style=flat-square&logoColor=white)
![Shiny](https://img.shields.io/badge/Shiny-1A73E8?style=flat-square&logo=r&logoColor=white)

```r
# Install in one line
source("https://raw.githubusercontent.com/sedatkacar56/seuratPassport/main/install.R")

# Stamp your object
WTHeme <- seuratPassport(WTHeme)

# Link child to parent automatically
EndoHeme <- seuratPassport(EndoHeme, parent = WTHeme)

# Read anytime
read_passport(EndoHeme)
```

---

---

### CDK5-Mediated EndMT — Single-Cell Perspective in Pulmonary Hypertension

> *How does nitration stress and CDK5 activation push endothelial cells into a mesenchymal identity in PAH?*

**Problem**
Endothelial-to-mesenchymal transition (EndMT) is a key driver of vascular remodeling in pulmonary arterial hypertension, but the cell-type-specific transcriptional programs linking CDK5 signaling to metabolic reprogramming remain unresolved at single-cell resolution.

**Solution**
Single-cell RNA-seq analysis dissecting how nitration stress and CDK5 activation drive EndMT in PAH lungs. Identifies endothelial sub-populations most susceptible to transition, characterizes glycolysis/oxidative phosphorylation shifts, and maps the CDK5 signaling axis at single-cell resolution — integrated with in vitro and in vivo experimental data.

**Tech Stack**

![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![Seurat](https://img.shields.io/badge/Seurat-1A73E8?style=flat-square&logoColor=white)
![ggplot2](https://img.shields.io/badge/ggplot2-FF6B6B?style=flat-square&logoColor=white)

```
Focus:    EndMT trajectory · CDK5 signaling axis · metabolic reprogramming
Disease:  Pulmonary Arterial Hypertension (PAH)
Status:   Ongoing (Jun 2025 – Present)
```

---

### GLUT4-Driven Pulmonary Hypertension — Single-Cell Transcriptomics

> *How does enhanced glucose uptake reshape the cellular landscape of the lung in PAH?*

**Problem**
GLUT4 overexpression alters glucose metabolism in the lung, but its cell-type-specific effects on mitochondrial dysfunction, proliferative signaling, and vascular remodeling are invisible in bulk data.

**Solution**
Single-cell RNA-seq analysis of GLUT4-overexpressing mouse lungs vs controls, resolving transcriptional changes at single-cell level to identify distinct cell populations, early molecular drivers of vascular remodeling, and metabolic imbalance signatures.

**Tech Stack**

![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![Seurat](https://img.shields.io/badge/Seurat-1A73E8?style=flat-square&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

```
Model:    GLUT4-overexpressing mouse lung
Focus:    Mitochondrial dysfunction · proliferative signaling · vascular remodeling
Status:   Ongoing (Mar 2025 – Present)
```

---

### SuGen/Hypoxia + Anaplerosis Inhibition — 500K Cell Atlas

[![GitHub](https://img.shields.io/badge/GitHub-View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/sedatkacar56/SugenProject)

> *How do 500,000 lung cells respond to chronic hypoxic stress and metabolic intervention across five experimental groups?*

**Problem**
Understanding how vascular and non-vascular lung compartments remodel across disease progression and treatment requires a dataset large enough to capture rare populations and time-dependent dynamics — not feasible with bulk or low-cell approaches.

**Solution**
Single-cell RNA-seq on 500,000+ lung cells across five groups: control, SuGen/hypoxia (2wk and 5wk), and SuGen + pyruvate carboxylase inhibition (PAA) at both timepoints. Captures cell-type-specific changes, transcriptional dynamics, and metabolic adaptation across disease stages.

**Tech Stack**

![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![Seurat](https://img.shields.io/badge/Seurat-1A73E8?style=flat-square&logoColor=white)
![PARSE](https://img.shields.io/badge/PARSE_Biosciences-00C4B4?style=flat-square&logoColor=white)

```
Cells:    500,000+ lung cells
Groups:   Control · SuGen/Hx 2wk · SuGen/Hx 5wk · SuGen+PAA 2wk · SuGen+PAA 5wk
Focus:    Anaplerotic flux · metabolic adaptation · vascular remodeling
Status:   Ongoing (Mar 2025 – Present)
```

---

### Sickle Cell Anemia Knockout Mouse — Lung scRNA-seq

[![GitHub](https://img.shields.io/badge/GitHub-View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/sedatkacar56/Sickle_Cell_Project)

> *How does sickle cell disease reshape the lung transcriptome, and does it differ between sexes?*

**Problem**
Sickle cell disease causes chronic vascular injury and hemolysis, but its cell-type-specific effects on the lung — particularly sex-based differences and rare cluster dynamics — are poorly characterized.

**Solution**
scRNA-seq analysis of male and female sickle cell anemia knockout mouse lungs, annotated using a rat lung reference atlas. Identifies rare clusters, sex-specific transcriptional shifts, differential gene expression, and cell-type dynamics via UMAP, heatmaps, and pathway analysis.

**Tech Stack**

![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![Seurat](https://img.shields.io/badge/Seurat-1A73E8?style=flat-square&logoColor=white)
![ggplot2](https://img.shields.io/badge/ggplot2-FF6B6B?style=flat-square&logoColor=white)

```
Model:    Sickle cell anemia knockout mouse lung (male + female)
Focus:    Sex-based differences · rare clusters · DEG analysis
Status:   Ongoing (Feb 2025 – Present)
```

---

### Stereo-seq Spatial Transcriptomics — Human PAH Lung

> *Where exactly in the diseased human lung do the most critical transcriptional changes occur?*

**Problem**
Single-cell RNA-seq resolves what changes, but not where. In PAH, the spatial organization of vascular, immune, and structural compartments in human lung tissue is as biologically meaningful as the gene expression itself.

**Solution**
Stereo-seq spatial transcriptomics analysis on human PAH lung slides. Annotated lung cell populations, identified DEGs, and spatially localized cell groups on fluorescently stained tissue — mapping nearly all cell types to their anatomical positions within the lung.

**Tech Stack**

![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Stereo-seq](https://img.shields.io/badge/Stereo--seq-6A0DAD?style=flat-square&logoColor=white)

```
Platform:  BGI Stereo-seq
Tissue:    Human PAH lung (FFPE sections)
Output:    Spatially resolved cell-type map · DEG localization
Period:    Mar 2024 – Oct 2024
```

---

### Rat Lung Single-Cell Atlas — 140,000 Cells

> *Without a rat lung reference, how do you annotate rat lung single-cell data robustly?*

**Problem**
Most scRNA-seq atlases cover human and mouse lung. The rat is the primary model organism in pulmonary hypertension research, yet no comprehensive annotated rat lung reference existed — making cell-type annotation across PH studies inconsistent and unreliable.

**Solution**
Built and annotated a comprehensive rat lung single-cell atlas from 140,000 cells (PARSE Biosciences), mapping all major pulmonary cell populations with molecular signatures. This atlas now serves as the reference for annotation across multiple downstream projects.

**Tech Stack**

![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![Seurat](https://img.shields.io/badge/Seurat-1A73E8?style=flat-square&logoColor=white)
![PARSE](https://img.shields.io/badge/PARSE_Biosciences-00C4B4?style=flat-square&logoColor=white)

```
Cells:    ~140,000 rat lung cells
Platform: PARSE Biosciences
Output:   Reference atlas used for label transfer across all subsequent rat lung projects
Period:   Jan 2024 – Jul 2024
```

---

### Sphk1 Knockout in Hypoxia — scRNA-seq

[![GitHub](https://img.shields.io/badge/GitHub-View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/sedatkacar56/SPHK1_project)

> *What happens to lung cell populations when Sphk1 is knocked out under hypoxic conditions?*

**Problem**
Sphingosine kinase 1 (Sphk1) plays a role in vascular tone and inflammation, but its cell-type-specific contribution to hypoxia-induced pulmonary remodeling — across smooth muscle, endothelial, pericyte, and fibroblast populations — is not fully resolved.

**Solution**
scRNA-seq analysis across four experimental groups (normal, hypoxia, Sphk1 KO, KO+hypoxia) to evaluate how Sphk1 deletion alters lung cell populations under normoxia and hypoxic stress. Cell-type-specific changes characterized across the full pulmonary cellular landscape.

**Tech Stack**

![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![Seurat](https://img.shields.io/badge/Seurat-1A73E8?style=flat-square&logoColor=white)
![ggplot2](https://img.shields.io/badge/ggplot2-FF6B6B?style=flat-square&logoColor=white)

```
Groups:   Normal · Hypoxia · Sphk1 KO · Sphk1 KO + Hypoxia
Focus:    Smooth muscle · endothelial · pericyte · fibroblast remodeling
Period:   Oct 2024 – Jan 2025
```

---

### Completed Projects

| Period | Project | Model | Focus |
|---|---|---|---|
| Sep 2024 – Jan 2025 | **Room Air vs Hypoxia — Young Rats (2wk)** | Rat lung (2-week-old) | Hypoxia-induced EC subtypes · DEG analysis |
| Mar 2024 – Nov 2024 | **Pecam+ SuGen Hypoxia — Male & Female** | Rat lung (sex-stratified) | Sex-specific immune response · endothelial subtyping |
| Feb 2024 – Oct 2024 | **Whole Lung SuGen Hypoxia** | Rat lung | Full cellular landscape under SuHx model |
| Apr 2024 – Oct 2024 | **Tie2-GFP Mouse Hypoxia** | GFP mouse lung | GFP+ endothelial tracking under hypoxia |
| May 2024 – Jul 2024 | **Age-Dependent Endothelial Variation (2, 6, 12wk rats)** | Rat lung (3 timepoints) | Age-related EC subset dynamics · DEG heatmaps |
| Jul 2023 – Aug 2024 | **Endothelial Cell Subsets Reference** | Multi-project | gCap, PVEC, PAE, lymphatic EC marker panel |
| Sep 2023 – Jul 2024 | **NFU Mutant RV/LV Cardiac scRNA-seq** | NFU mutant heart | RV vs LV cardiac cell populations in PH |

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=sedatkacar56&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=00C4B4&icon_color=00C4B4&text_color=FFFFFF" width="48%" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=sedatkacar56&theme=radical&hide_border=true&background=0D1117&ring=00C4B4&fire=FF6B6B&currStreakLabel=00C4B4" width="48%" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sedatkacar56&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=00C4B4&text_color=FFFFFF" width="48%" />

</div>

---

## 🐍 Contribution Snake

<div align="center">

![Snake animation](https://github.com/sedatkacar56/sedatkacar56/blob/output/github-contribution-grid-snake.svg)


</div>

---

## 🌐 Let's Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-sedatkacar56-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sedatkacar56)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sedat-kacar-phd-6863b812b)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sedatkacar56@gmail.com)

</div>

---

<div align="center">

🧬 &nbsp; `A` `T` `C` `G` &nbsp; — &nbsp; the four letters that wrote all of life &nbsp; — &nbsp; `A` `T` `C` `G` &nbsp; 🧬

*Thanks for visiting! May your p-values always be significant.* 😄

![Profile views](https://komarev.com/ghpvc/?username=sedatkacar56&color=00C4B4&style=flat-square)

</div>

---

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00C851&center=true&vCenter=true&width=750&lines=Alhamdulillah!)

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00C4B4&center=true&vCenter=true&width=750&lines=Alhamdulillah!;Expression.+Space.+Identity.)


