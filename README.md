# Ishan Maheshwari

MSc Genomics Data Science student at the University of Galway, coming from a computer engineering background. I build pipelines that turn raw sequencing data – bulk RNA-seq, single-cell, long-read metagenomics, germline variants – into something a biologist can actually use.

Based in Ireland. Open to bioinformatics, computational biology, and genomics data science roles.

## Background

- MSc, Genomics Data Science – University of Galway, Ireland
- B.E., Computer Engineering – Gujarat Technological University, India

The computer engineering background is why most of these projects lean toward reproducible, containerized pipelines (Nextflow, Docker, Makefiles) rather than one-off notebooks.

## What I work with

![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white)
![Nextflow](https://img.shields.io/badge/Nextflow-24.04-0DC09D?style=flat&logo=nextflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

- RNA-seq differential expression (DESeq2, pydeseq2), single-cell RNA-seq (Scanpy), GWAS/population genomics, GATK germline variant calling, GO/pathway enrichment
- Pipeline tooling: Nextflow DSL2, Docker, Snakemake-style modular design, MultiQC
- R (tidyverse, Bioconductor, Shiny) and Python (scanpy, pandas, scikit-learn) about equally

## Projects

**[amr-nano-context](https://github.com/IshanMaheshwari01/amr-nano-context)** – Long-read metagenomic resistome profiling that reports *where* a resistance gene sits (plasmid vs. chromosome) and *which organism* carries it, not just that it's present. Validated against a real Oxford Nanopore mock-community run.

**[gatk4-germline-pipeline](https://github.com/IshanMaheshwari01/gatk4-germline-pipeline)** – Containerized germline variant-calling pipeline (BWA-MEM → BQSR → HaplotypeCaller → MultiQC) following GATK Best Practices, portable across local, SLURM, and AWS Batch.

**[single-cell-rnaseq-pbmc3k](https://github.com/IshanMaheshwari01/single-cell-rnaseq-pbmc3k)** – Recovers 8 immune cell populations from 2,700 unlabeled PBMC single-cell profiles using Scanpy – QC, clustering, marker genes, UMAP, all from raw counts.

**[RNA-seq-differential-expression-analysis](https://github.com/IshanMaheshwari01/RNA-seq-differential-expression-analysis)** – Differential expression and pathway enrichment on real public TCGA tumor-vs-normal RNA-seq data, built with pydeseq2 and gseapy.

## Currently learning

Doublet detection and batch integration for single-cell data, and how far I can push AWS Batch / cloud execution for the variant-calling pipeline on larger cohorts.

## Reach me

[LinkedIn](https://www.linkedin.com/in/ishanmaheshwari2001) · [Email](mailto:ishanmaheshwari02@gmail.com)
