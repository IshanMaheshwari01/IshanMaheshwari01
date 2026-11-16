# Ishan Maheshwari

I completed an MSc in Genomics Data Science from the University of Galway. Before that I studied computer engineering, so I like building analyses that someone else can actually rerun, not just a notebook that worked once on my laptop.

I'm based in Ireland and looking for roles in bioinformatics, computational biology and genomics data science.

## Background

- MSc Genomics Data Science, University of Galway, Ireland
- B.E. Computer Engineering, Gujarat Technological University, India

## What I use

![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white)
![Nextflow](https://img.shields.io/badge/Nextflow-0DC09D?style=flat&logo=nextflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

- Bulk and single-cell RNA-seq (DESeq2, pydeseq2, limma, Scanpy), GATK variant calling, GWAS, pathway enrichment
- Nextflow and Docker for pipelines, Make and pytest for smaller projects
- R (tidyverse, Bioconductor, Shiny) and Python (scanpy, pandas, scikit-learn, PyTorch)

## Projects

**[sle-pbmc-ml](https://github.com/IshanMaheshwari01/sle-pbmc-ml)**
Can a blood sample tell lupus patients apart from healthy people? I used 1.26 million single cells from 261 people. The tricky part was that disease status is mixed up with processing batch in this dataset, so most of the work went into checking how much of the accuracy is real once batch can't help.

**[amr-nano-context](https://github.com/IshanMaheshwari01/amr-nano-context)**
A Nextflow pipeline for nanopore metagenomics. For each antibiotic resistance gene it reports whether the gene is on a plasmid or a chromosome and which organism carries it. Tested on a real mock community where the right answer is known.

**[DeepVariantEffect](https://github.com/IshanMaheshwari01/DeepVariantEffect)**
Predicting whether a missense variant is harmful from the DNA sequence around it, using ClinVar labels and a DNA language model. Trained a CNN and a fine-tuned Nucleotide Transformer on 207k variants and benchmarked them against CADD, REVEL and AlphaMissense: sequence alone gets you to AUROC 0.78, well short of REVEL's 0.97.

**[gatk4-germline-pipeline](https://github.com/IshanMaheshwari01/gatk4-germline-pipeline)**
A Nextflow pipeline that follows the GATK germline steps: BWA-MEM, MarkDuplicates, BQSR, HaplotypeCaller and MultiQC. Runs locally, on SLURM or on AWS Batch.

**[single-cell-rnaseq-pbmc3k](https://github.com/IshanMaheshwari01/single-cell-rnaseq-pbmc3k)**
My first single-cell project. Starting from raw counts for 2,700 blood cells, I used Scanpy to find 8 immune cell types.

**[RNA-seq-differential-expression-analysis](https://github.com/IshanMaheshwari01/RNA-seq-differential-expression-analysis)**
Tumor vs normal breast tissue from the same 25 TCGA patients, analysed with pydeseq2 and gseapy.

## Contact

[LinkedIn](https://www.linkedin.com/in/ishanmaheshwari2001) · [Email](mailto:ishanmaheshwari02@gmail.com)
