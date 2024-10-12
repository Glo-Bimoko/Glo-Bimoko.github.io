---
title: "TB Genomics"
date: 2024-10-11
description: "An overview of my work in the TB genomics laboratory."
---


Tuberculosis (TB) remains a significant global health threat, and genomics has emerged as a critical tool in understanding the pathogen's biology, resistance mechanisms, and transmission dynamics. As part of my work in genomics, I have undertaken several projects focused on using genomic data to address challenges in TB control and treatment.
Project Overview

My TB genomics projects have focused on leveraging high-throughput sequencing technologies and bioinformatics tools to analyze Mycobacterium tuberculosis genomes. These projects aim to understand the genetic diversity of TB strains, detect mutations associated with drug resistance, and explore the epidemiology of TB in different populations.
Key Objectives:

    Detection of Drug-Resistant TB Strains: Identification of mutations in key genes such as katG, inhA, and rpoB, which are associated with resistance to first-line anti-TB drugs (e.g., isoniazid and rifampicin).
    Strain Typing and Phylogenetics: Phylogenetic analysis of TB strains to trace transmission pathways and determine the evolutionary relationships between different strains.
    Whole Genome Sequencing (WGS): Analysis of WGS data to identify novel mutations and genetic markers that can be used for diagnostic purposes or to inform treatment strategies.

Tools and Technologies

1. Nextflow:

As with my RNA-seq analysis pipeline, I have incorporated Nextflow to manage the complexity of my TB genomics workflows. Nextflow helps in orchestrating various tasks, from quality control to variant calling, ensuring reproducibility and scalability across different environments.

2. BWA:

For read alignment, BWA (Burrows-Wheeler Aligner) is used to align the sequencing reads to the reference genome of Mycobacterium tuberculosis. BWA ensures high-quality alignment, which is essential for downstream analyses like variant detection.

3. GATK:

The Genome Analysis Toolkit (GATK) is used for variant calling, particularly for detecting SNPs (single nucleotide polymorphisms) and indels (insertions/deletions). GATK is widely trusted for its accuracy in calling variants in microbial genomes.

4. Samtools:

Samtools is employed to handle the BAM files generated during the alignment process. It assists in sorting, indexing, and visualizing the alignment results, which is key to ensuring data integrity.

5. Prokka:

For annotation of bacterial genomes, Prokka is used to predict coding sequences, functional genes, and non-coding RNAs. This step is crucial for understanding the functional implications of detected variants and mutations.

6. Phylogenetic Analysis:

To explore the relationships between different TB strains, I use tools like IQ-TREE and BEAST for building phylogenetic trees. These tools help to understand the evolutionary dynamics of TB in specific regions or populations.
Case Studies

1. Drug-Resistant TB in South Africa:

In one of my projects, I analyzed genomic data from drug-resistant TB strains collected in South Africa. The project aimed to map out the prevalence of key drug-resistance mutations and identify patterns in transmission across different communities. Using WGS data, we were able to detect novel resistance mutations that had not been previously reported in the literature.

2. Molecular Epidemiology of TB:

Another project focused on using genomics to study the spread of TB within a confined population. Phylogenetic analysis revealed several clusters of closely related TB strains, suggesting localized outbreaks that required targeted public health interventions.
Conclusion

TB genomics is a vital area of research that combines cutting-edge sequencing technologies with bioinformatics to fight one of the world’s most deadly infectious diseases. Through my projects, I have contributed to a better understanding of TB genomics, particularly in the context of drug resistance and transmission dynamics. Moving forward, I aim to expand these projects by integrating new tools and approaches, such as metagenomics and transcriptomics, to further explore the complex biology of Mycobacterium tuberculosis.
