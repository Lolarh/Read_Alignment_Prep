# RNA-Seq Analysis Pipeline

This project provides a pipeline for RNA-Seq data analysis, including quality control of read using Cutadapt and FastQC, read alignment using STAR, and read quantification using HTSeq-count or FeatureCounts.

...

## Sample Information

### SRR26832288

- **SRR26832288** is a sample ID from the Sequence Read Archive (SRA), used in this project to demonstrate the RNA-Seq read alignment and quantification process.
- It represents an RNA-Seq experiment for which the reads have been aligned to a reference genome and subsequently quantified.
- You can look up this sample on the SRA database for additional details: [https://trace.ncbi.nlm.nih.gov/Traces/index.html?view=run_browser&acc=SRR26832288&display=metadata]

### SRA Tool Installation

+ Installation from SRA toolkit: [!apt-get install -y sra-toolkit]
  The SRA Toolkit is a collection of command-line utilities designed to facilitate access to the Sequence Read Archive (SRA), which is a large public repository of high-throughput sequencing data hosted by the National Center for Biotechnology Information (NCBI).
+ Convert to SRA file to FASTQ format using Fastq-dump
...

## Necessary Installations

Ensure you have the following tools installed:

+ CUTADAPT : This is typically used as a preprocessing step before alignment to a reference genome.
+ HTSeq-count: A Python-based tool for counting reads mapped to genomic features.
+ FeatureCounts: A Linux command-line program for read counting.
+ Samtools: A suite of tools for handling SAM/BAM files.

You can install these tools as follows:
- CUTADAPT: pip install cutadapt
- STAR: [Installation Instructions](https://github.com/alexdobin/STAR)
- HTSeq: `pip install HTSeq`
- Samtools: `apt-get install samtools`

### USAGE OF INSTALL TOOLS
The usage and command line necessary are indicated in the attached file


### Troubleshooting and Common Issues
+ Indexing Issues: Ensure sufficient storage space is available for the genome index.
+ Conversion Errors: Verify that SAM files are correctly formatted before conversion.



