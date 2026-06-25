# Human-Gene-Analysis-BRCA1-Bioinformatics
Bioinformatics analysis of the human BRCA1 gene using NCBI, BLAST, EMBOSS Needle, Clustal Omega, UniProt, and phylogenetic analysis to study sequence conservation, homology, protein function, and evolutionary relationships.
This project focuses on the bioinformatics analysis of the human BRCA1 (Breast Cancer Type 1 Susceptibility Protein) gene. Various bioinformatics databases and tools were used to investigate gene sequence conservation, homologous sequences, protein function, and evolutionary relationships among species.

# BRCA1 Gene Analysis: Comparative Genomics and Evolutionary Study Using Bioinformatics Tools

## Project Overview

This project presents a comprehensive bioinformatics analysis of the human **BRCA1 (Breast Cancer Type 1 Susceptibility Protein)** gene. BRCA1 is a tumor suppressor gene that plays a critical role in DNA damage repair, cell cycle regulation, genomic stability, and cancer prevention.

Using publicly available biological databases and computational tools, homologous BRCA1 sequences from closely related primates were identified and analyzed to investigate sequence conservation, evolutionary relationships, and functional significance.

This project demonstrates a complete bioinformatics workflow commonly used in comparative genomics and molecular evolution studies.

---

## Research Objectives

- Retrieve and analyze the human BRCA1 gene sequence.
- Identify homologous BRCA1 sequences across species.
- Evaluate sequence similarity using BLAST.
- Perform Pairwise Sequence Alignment (PSA).
- Perform Multiple Sequence Alignment (MSA).
- Construct phylogenetic relationships among species.
- Analyze protein function and annotation data.
- Verify sequence consistency across international nucleotide databases.
- Interpret evolutionary conservation and biological significance.

---

## Biological Background

### BRCA1 Gene

| Attribute | Information |
|------------|------------|
| Gene Symbol | BRCA1 |
| Full Name | BRCA1 DNA Repair Associated |
| Gene ID | 672 |
| Organism | Homo sapiens |
| Gene Type | Protein Coding |
| Chromosome | 17q21.31 |
| Primary Function | DNA Damage Repair and Genome Stability |

BRCA1 is a key component of the homologous recombination repair pathway and helps maintain genomic integrity by repairing double-strand DNA breaks.

---

# Methodology

## Step 1: Gene Retrieval

The reference BRCA1 mRNA sequence was retrieved from the NCBI Nucleotide Database.

| Parameter | Value |
|------------|--------|
| Organism | Homo sapiens |
| Accession Number | NM_007294.4 |
| Sequence Type | mRNA |
| Length | 7088 bp |

---

## Step 2: Homology Search Using BLAST

The human BRCA1 sequence was used as a query in NCBI BLAST to identify homologous sequences from related species.

### Selected Homologous Sequences

| Organism | Sequence Description | Accession Number | Query Coverage | Identity | E-value |
|-----------|---------------------|------------------|---------------|----------|---------|
| Homo sapiens | BRCA1 transcript variant 1, mRNA | NM_007294.4 | 100% | 100.00% | 0.0 |
| Pan troglodytes (Chimpanzee) | BRCA1 transcript variant X1, mRNA | XM_009432080.5 | 100% | 99.15% | 0.0 |
| Gorilla gorilla gorilla (Western Gorilla) | BRCA1 transcript variant X1, mRNA | XM_031011552.3 | 100% | 98.89% | 0.0 |

These sequences were selected due to their extremely high sequence similarity and evolutionary proximity to humans.

---

## Step 3: Pairwise Sequence Alignment (PSA)

### Tool
EMBOSS Needle

### Comparison

Human BRCA1 (NM_007294.4)

vs

Chimpanzee BRCA1 (XM_009432080.5)

### Results

| Metric | Value |
|----------|---------|
| Alignment Length | 7212 |
| Identity | 7026/7212 (97.4%) |
| Similarity | 7026/7212 (97.4%) |
| Gaps | 139/7212 (1.9%) |
| Alignment Score | 39723.0 |

### Interpretation

The extremely high identity score indicates strong evolutionary conservation of BRCA1 between humans and chimpanzees, reflecting its essential biological function.

---

## Step 4: Multiple Sequence Alignment (MSA)

### Tool
Clustal Omega

### Sequences Included

- NM_007294.4 (Human)
- XM_009432080.5 (Chimpanzee)
- XM_031011552.3 (Gorilla)

### Purpose

- Identify conserved nucleotide regions.
- Detect sequence variations.
- Study evolutionary conservation.

### Key Observation

Multiple highly conserved regions were observed across all three species, suggesting strong selective pressure to maintain BRCA1 functionality.

---

## Step 5: Guide Tree and Phylogenetic Analysis

### Tool
Clustal Omega

Phylogenetic analysis was performed using aligned BRCA1 sequences to infer evolutionary relationships.

### Findings

- Chimpanzee and Gorilla sequences clustered closely together.
- Human BRCA1 showed high similarity with both primate sequences.
- The tree supported the evolutionary relationships observed in BLAST and alignment analyses.

### Evolutionary Interpretation

The clustering pattern demonstrates a shared evolutionary ancestry and highlights the conserved nature of BRCA1 among primates.

---

## Step 6: Protein Analysis

### Database
UniProt

### Protein Information

| Attribute | Value |
|------------|--------|
| Protein Name | Breast Cancer Type 1 Susceptibility Protein |
| UniProt ID | P38398 |
| Length | 1863 Amino Acids |
| Annotation Score | 5/5 |
| Evidence Level | Protein Level |

### Functional Roles

- DNA damage repair
- Homologous recombination
- Tumor suppression
- Cell cycle checkpoint regulation
- Ubiquitination pathways

---

## Step 7: Database Verification

Sequence records were verified across the three major international nucleotide databases.

| Database | Accession Number | Status |
|------------|------------------|--------|
| NCBI | NM_007294.4 | Verified |
| ENA | NM_007294 | Verified |
| DDBJ | AY273801 | Verified |

### Importance

NCBI, ENA, and DDBJ are members of the International Nucleotide Sequence Database Collaboration (INSDC), ensuring synchronized sequence information worldwide.

---

# Results Summary

| Analysis | Major Finding |
|-----------|--------------|
| BLAST | High homology among primate BRCA1 sequences |
| PSA | 97.4% identity between Human and Chimpanzee |
| MSA | Conserved functional regions detected |
| Guide Tree | Closely related primate sequences clustered together |
| Phylogenetic Tree | Supported evolutionary relationships |
| UniProt | Confirmed DNA repair function of BRCA1 |

---

# Biological Significance

The conservation of BRCA1 across primates demonstrates its critical role in maintaining genomic stability. Conserved regions identified through sequence alignment are likely associated with functional domains essential for DNA repair mechanisms.

The study illustrates how comparative genomics can be used to understand molecular evolution, gene function, and species relationships.

---

# Bioinformatics Resources Used

- NCBI Gene
- NCBI Nucleotide
- BLAST (BLASTn)
- EMBOSS Needle (Pair Wise Sequence Allignment)
- Clustal Omega (Multiple Sequence Allignment)
- UniProt
- ENA
- DDBJ

---

# Skills Demonstrated

- Biological Database Mining
- Sequence Retrieval
- Comparative Genomics
- BLAST Analysis
- Pairwise Sequence Alignment
- Multiple Sequence Alignment
- Phylogenetic Analysis
- Protein Annotation
- Evolutionary Biology
- Bioinformatics Data Interpretation

---

# Future Work

- Conserved Domain Analysis
- Protein Structure Prediction (AlphaFold)
- Variant and SNP Analysis in BRCA1 gene
- Molecular Docking Studies in BRCA1 
- Functional Pathway Mapping
- Cancer Mutation Analysis in BRCA1

---

# Author

### Vansh Juneja

## Citation

If you find this project useful for learning bioinformatics workflows, please cite the corresponding databases and tools used in the analysis.
