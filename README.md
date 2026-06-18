# RNA-Seq Project

A comprehensive RNA sequencing analysis pipeline for differential gene expression analysis, transcript quantification, and downstream functional interpretation.

## Repository Structure

```
RNA-Seq-project/
├── data/         # Raw and processed sequencing data (FASTQ, BAM, count matrices)
├── Articles/     # Relevant research papers, literature notes, and references
├── notes/        # Lab notes, analysis logs, and methodology documentation
├── workflow/     # Pipeline scripts (Snakemake/Nextflow), config files, and execution logs
├── scripts/      # Custom analysis and visualization scripts (R/Python)
├── results/      # Output figures, tables, reports, and final analysis results
└── references/   # Genome annotations, transcriptome indices, and metadata files
```

## Overview

This project is designed to:
- Perform quality control of raw RNA-seq reads
- Align reads to a reference genome/transcriptome
- Quantify gene/transcript expression levels
- Identify differentially expressed genes
- Conduct downstream functional enrichment and pathway analysis

## Getting Started

### Prerequisites

- **Tools**: FastQC, Trimmomatic, STAR/HISAT2, StringTie, featureCounts, DESeq2/edgeR
- **Languages**: R (≥ 4.0), Python (≥ 3.8), Bash
- **Package management**: Conda/Mamba environments recommended

### Installation

```bash
git clone https://github.com/ShivMC/RNA-Seq-project.git
cd RNA-Seq-project
```

## Usage

Each subdirectory contains its own README with detailed instructions. The main analysis workflow is documented in `workflow/`.

## License

This project is for educational and research purposes.

## Author

**Shivani Pawar** — [ShivMC](https://github.com/ShivMC)
