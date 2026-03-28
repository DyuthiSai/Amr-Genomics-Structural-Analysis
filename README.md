# 🧬 Genomic & Structural Analysis of Antimicrobial Resistance in VISA

🚀 End-to-end analysis of antimicrobial resistance combining genomics, epidemiology, and structural biology

---

## 📌 Overview

This project investigates antimicrobial resistance (AMR) in *Staphylococcus aureus*, focusing on **Vancomycin-Intermediate Staphylococcus aureus (VISA)** strains.

By integrating **NGS-based genomic analysis, epidemiological validation, and structural modeling**, the study explores how resistance emerges at both the **genetic and protein levels**.

---

## 🎯 Objectives

* Characterize **genetic diversity** using MLST and cgMLST
* Identify **antimicrobial resistance genes** using genomic pipelines
* Investigate **molecular resistance mechanisms** through structural modeling and simulations

---

## ⚙️ Workflow

### 🧬 Genomic Analysis (Nextflow Pipeline)

* Data retrieval from NCBI SRA
* Quality control using FastQC and ConFindr
* Genome assembly using SPAdes
* Genome annotation using Prokka
* Strain typing using MLST and cgMLST
* AMR gene detection using CARD and ResFinder

---

### 🌐 Validation using Pathogenwatch

* Species identification
* MLST and cgMLST confirmation
* SNP mutation analysis
* Plasmid incompatibility typing
* Phylogenetic analysis

---

### 🧪 Structural Analysis

* Selected key AMR genes: **blaZ** and **mecA**
* Protein modeling using Robetta / RoseTTAFold
* Molecular docking using Schrödinger
* Molecular dynamics simulations using GROMACS

---

## 📊 Key Results

* 🧬 Identified a **novel VISA strain (SRR25621661)** with unique allelic variations
* 💊 Detected **33 AMR genes across 10 antibiotic classes**, indicating multi-drug resistance
* 🌐 Validated genomic findings across independent tools
* 🌳 Phylogenetic analysis revealed genetic diversity among isolates
* 🧪 Structural analysis showed **reduced binding affinity of PBP2a to β-lactam antibiotics**

---

## 📁 Repository Structure

```
amr-genomics-structural-analysis/
│── README.md
│
│── results/
│   ├── genomics/
│   │   └── genomics_master.csv
│   ├── pathogenwatch/
│   │   └── pathogenwatch_master.csv
│   ├── structural/
│   │   └── structural_summary.csv
│   ├── qc/
│   │   └── qc_summary.csv
│
│── docs/
│   └── images/
│
│── pipeline/
│   └── nextflow_pipeline_info.md
```

---

## 📊 Results Summary

### 🧬 Genomics

* Integrated dataset combining assembly, annotation, MLST, and AMR results
* Identification of strain diversity and novel variants

### 🌐 Pathogenwatch

* Independent validation of AMR profiles
* Detection of SNP mutations and plasmid types

### 🧪 Structural Analysis

* Docking and MD simulations of:

  * β-lactamase–biapenem complex
  * PBP2a–ceftazidime complex

### 📊 Quality Control

* High-quality sequencing data across samples
* Minimal contamination and adapter presence

---

## 🖼️ Visual Results

### 🌳 Phylogenetic Analysis

<img width="956" height="424" alt="image" src="https://github.com/user-attachments/assets/ded273d0-32c1-4c7d-b7af-a389be99fb9e" />


### 🧬 Protein Modeling (PBP2a and Class-A β - Lactamase

<img width="437" height="349" alt="image" src="https://github.com/user-attachments/assets/72432b65-ca56-42bc-bcc2-35899f4ef580" />


### 💊 Docking Interaction

<img width="545" height="364" alt="image" src="https://github.com/user-attachments/assets/e8e031b1-0094-4c11-8398-4cbd8c70a966" />
<img width="652" height="354" alt="image" src="https://github.com/user-attachments/assets/a8a76a56-5148-42e4-9bd3-95e6f5768c8d" />
<img width="601" height="538" alt="image" src="https://github.com/user-attachments/assets/7d53a682-f96e-4a02-8717-6bed9b0eaa11" />
<img width="569" height="483" alt="image" src="https://github.com/user-attachments/assets/a558704f-fbbb-4339-9c4d-6f41943bd47f" />


### 📊 MD Simulation (RMSD)

<img width="1278" height="336" alt="image" src="https://github.com/user-attachments/assets/548e7604-041b-4718-af5b-9ef6aeac3f8a" />
<img width="1278" height="336" alt="image" src="https://github.com/user-attachments/assets/47a61b08-cb40-4229-b889-196111ed122c" />
<img width="479" height="348" alt="image" src="https://github.com/user-attachments/assets/f3dc608e-f109-4c8a-b217-f8927223d429" />
<img width="505" height="364" alt="image" src="https://github.com/user-attachments/assets/e99e25b6-510e-445b-877a-2489fc769a92" />

---

## 🔬 Key Insight

> Antimicrobial resistance is driven by both **genetic variation and structural adaptation**, requiring multi-level analysis to understand resistance mechanisms fully.

---

## 🧠 Technologies Used

* NGS Analysis: FastQC, ConFindr, SPAdes
* Annotation: Prokka
* AMR Detection: CARD, ResFinder
* Validation: Pathogenwatch
* Structural Biology: Schrödinger, GROMACS
* Workflow: Nextflow

---

## ⚠️ Data Availability

Due to size and sensitivity, raw sequencing data is not included.
Processed summaries and results are provided.

---

## 🔗 Pipeline Credit

Pipeline adapted from:
https://gitlab.com/antunderwood/multi-amr

---

## 👩‍💻 Author

Dyuthi Sai
M.Tech Computational Biology

---
