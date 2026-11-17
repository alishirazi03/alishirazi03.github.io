# Syed Muhammad Ali Shirazi | Academic Portfolio & Technical Blog

[![Website](https://img.shields.io/website?url=https%3A%2F%2Falishirazi03.github.io&label=Live%20Site&style=flat-square&color=0d7463)](https://alishirazi03.github.io)
[![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-0f172a?style=flat-square&logo=github)](https://pages.github.com/)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0009--2379--2948-a6ce39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0009-0009-2379-2948)
[![ISCB Member](https://img.shields.io/badge/ISCB%20Member-%2346230-0d7463?style=flat-square)](https://www.iscb.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)

Source repository for the personal academic portfolio and technical bioinformatics blog of **Syed Muhammad Ali Shirazi**, BS Biosciences graduate from COMSATS University Islamabad working at the intersection of wet-lab molecular genetics and computational biology.

**🌐 Live Website:** [https://alishirazi03.github.io](https://alishirazi03.github.io)  
**📝 Technical Blog:** [https://alishirazi03.github.io/blog/](https://alishirazi03.github.io/blog/)  
**📄 Academic CV (PDF):** [CV_syed_muhammad_ali_shirazi.pdf](https://alishirazi03.github.io/CV_syed_muhammad_ali_shirazi.pdf)

---

## 📋 Overview

This website serves as a central hub for my postgraduate Master's applications (2027 intake) and research collaborations across **Bioinformatics, Computational Biology, Molecular Biosciences, and Biotechnology**.

### What This Repository Showcases
- 🧬 **Research Projects & Pipelines:** End-to-end computational genomics (`SARS-CoV-2`) and wet-lab case-control molecular genetics (`ATP8B1` SNP genotyping).
- 💻 **Technical Stack & Laboratory Capabilities:** Bioinformatics tools, programming & biostatistics (`Python`, `R`, `Bash`, `Galaxy`, `LaTeX`), and wet-lab protocols (`TETRA-ARMS PCR`, organic DNA extraction, gel electrophoresis).
- 🎓 **Verified Academic Credentials:** 134-credit BS in Biosciences (12-credit thesis awarded Grade A, HEC attested), IELTS Academic Band 7.5 (CEFR C1), and specialized certifications from UC San Diego, Johns Hopkins, and Stanford.
- 📝 **Long-Form Technical Writing:** Detailed tutorials and algorithmic walkthroughs on de novo genome assembly, viral phylogenetics, and bioinformatics workflows.
- 🎤 **Scientific Communication & Service:** Collegiate presentations, symposium participation, ISCB student membership, and community leadership.

---

## 🔬 Featured Research Projects

### 1. SARS-CoV-2 Genomic Analysis Pipeline (Jan 2026 - Mar 2026)
*From Raw Illumina Reads to Phylogenetic Dating & Antiviral Target Discovery*
- **De Novo Assembly & QC:** Reconstructed the complete **29,903 bp** viral genome from 2,512,682 paired-end reads (`SRR10971381`) using `SPAdes` and validated contiguity in `QUAST` (`N50: 29,903 bp`, `193.5x` mean depth, `37.97%` GC).
- **Functional Annotation & Diagnostics:** Annotated all **11 viral ORFs** with `Prokka` and designed 100% specific diagnostic RT-PCR primers targeting the Nucleocapsid (`N`) gene using `Primer3` and `NCBI BLAST`.
- **Comparative Genomics & Molecular Clock:** Aligned **100 complete SARS-CoV-2 genomes** with `MUSCLE` and `ViralMSA`, inferred maximum-likelihood trees in `FastTree` (`GTR+Gamma`), and estimated pandemic emergence (`tMRCA: Oct-Nov 2019`, $R^2 = 0.96$) in `LSD2`.
- **Metabolic Target Identification:** Mapped host-pathogen purine metabolism in `BioCyc`, identifying **guanylate kinase (EC 2.7.4.8)** as a candidate therapeutic chokepoint.
- 🔗 **Repository:** [Hacking-COVID-19-Applied-Bioinformatics-Genomic-Analysis](https://github.com/alishirazi03/Hacking-COVID-19-Applied-Bioinformatics-Genomic-Analysis)

### 2. Assessment of the Role of *ATP8B1* Gene in Gallstone Disease in the Pakistani Population (Sep 2025 - Feb 2026)
*Undergraduate Research Thesis (12 Credit Hours, Grade A) | Translational Genomics Lab, COMSATS*
- **Case-Control Cohort:** Investigated the *ATP8B1* P-type ATPase transporter variant `rs766737165 (T>A)` across **104 participants** (75 confirmed cholelithiasis patients and 29 healthy controls).
- **Wet-Lab Genotyping:** Isolated genomic DNA via phenol-chloroform extraction, designed inner and outer allele-specific primers in `Primer3` (validated via `BLAST`), and performed **TETRA-ARMS PCR** and agarose gel electrophoresis.
- **Biostatistical Modeling:** Evaluated genotype and allele distributions using Chi-square contingency tests and Hardy-Weinberg equilibrium models in `R` and `Excel`, establishing baseline local population data.
- 🔗 **Repository:** [ATP8B1-Gallstone-Study](https://github.com/alishirazi03/ATP8B1-Gallstone-Study)

---

## 📝 Technical Blog Series

| # | Article Title | Core Topics & Tools | Read Time |
| :--- | :--- | :--- | :--- |
| **01** | **[From Wet Lab to Code: My Journey into Bioinformatics](https://alishirazi03.github.io/blog/wetlab-to-code.html)** | Transitioning from bench PCR & DNA extraction to computational genomics pipelines | 20 min (5,000+ words) |
| **02** | **[Assembling a Pandemic: My First Genome Assembly](https://alishirazi03.github.io/blog/genome-assembly.html)** | FASTQ Phred scores, paired-end reads, de Bruijn graphs, `SPAdes`, `QUAST` (`N50`), `BLAST` | 18 min (4,500+ words) |
| **03** | **[Tools I Learned: A Bioinformatics Toolkit for Viral Genomics](https://alishirazi03.github.io/blog/tools-toolkit.html)** | Reference guide to 13 tools: `SPAdes`, `QUAST`, `Prokka`, `BLAST`, `MUSCLE`, `ViralMSA`, `FastTree`, `LSD2`, `BioCyc`, `Primer3`, `Taxonium`, `Jalview`, `Galaxy` | 15 min (3,500+ words) |

---

## ✨ Architecture & UI Features (v2.0)

Built with **zero external JavaScript frameworks** using semantic HTML5, custom CSS variables, and vanilla ES6 JavaScript for instant load times and clean maintainability:

- ⌨️ **Command Palette (`Ctrl+K` / `⌘K`):** Keyboard-accessible modal to jump across sections, download the PDF CV, copy contact details, or toggle themes.
- 🎛️ **Interactive Coursework Matrix:** Filter completed undergraduate coursework (134 credit hours) by discipline (*Molecular & Cellular*, *Bioinformatics & Quantitative*, *Biochemistry*, *Biomedical & Organismal*).
- 🔍 **Live Blog Search & Topic Filtering:** Client-side keyword filtering and category tabs on the blog index page.
- 🌗 **Persistent Dark / Light Theme:** Automatic system-preference detection and cross-page state synchronization via `localStorage` (`shirazi_theme`).
- 📐 **Editorial & Computational Typography:** Combines `Crimson Pro` (headings), `Plus Jakarta Sans` (body), and `JetBrains Mono` (genomic coordinates, tool badges, and code blocks).
- 🖨️ **Print-Optimized Stylesheet:** Dedicated `@media print` rules for clean document export.

---

## 📂 Repository Structure

```text
alishirazi03.github.io/
├── index.html                          # Main academic portfolio (v2.0)
├── CV_syed_muhammad_ali_shirazi.pdf    # Full academic Curriculum Vitae (PDF)
├── mypic.jpg                           # Profile photograph
├── favicon.ico                         # Site favicon
├── README.md                           # Repository documentation
└── blog/
    ├── index.html                      # Blog hub with live search & category filter
    ├── blog-style.css                  # Shared typography, code block & dark-mode styles
    ├── wetlab-to-code.html             # Article 01: Wet-lab to bioinformatics transition
    ├── genome-assembly.html            # Article 02: SARS-CoV-2 de novo assembly tutorial
    └── tools-toolkit.html              # Article 03: 13-tool viral genomics reference guide
